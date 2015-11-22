.. _api_ref:

=============
API reference
=============

Covariance Estimation
------------------
.. _estimation_api:
.. currentmodule:: pyriemann.estimation

.. autosummary::
    :toctree: generated/
    :template: class.rst

    Covariances
    ERPCovariances
    XdawnCovariances
    CospCovariances


Classification
------------------
.. _classification_api:
.. currentmodule:: pyriemann.classification

.. autosummary::
    :toctree: generated/
    :template: class.rst

    MDM
    FgMDM
    TSclassifier

Clustering
------------------
.. _clustering_api:
.. currentmodule:: pyriemann.clustering

.. autosummary::
    :toctree: generated/
    :template: class.rst

    Kmeans
    KmeansPerClassTransform
    Potato


Tangent Space
------------------
.. _tangentspace_api:
.. currentmodule:: pyriemann.tangentspace

.. autosummary::
    :toctree: generated/
    :template: class.rst

    TangentSpace
    FGDA

Spatial Filtering
------------------
.. _spatialfilter_api:
.. currentmodule:: pyriemann.spatialfilters

.. autosummary::
    :toctree: generated/
    :template: class.rst

    Xdawn

Channel selection
------------------
.. _channelselection_api:
.. currentmodule:: pyriemann.channelselection

.. autosummary::
    :toctree: generated/
    :template: class.rst

    ElectrodeSelection

Stats
------------------
.. _stats_api:
.. currentmodule:: pyriemann.stats

.. autosummary::
    :toctree: generated/
    :template: class.rst

    PermutationTest
    PermutationTestTwoWay
    DistanceMetric
    SeparabilityIndex
    SeparabilityIndexTwoFactor


Utils function
--------------

Utils functions are low level functions that implement most base components of Riemannian Geometry.

Distances
~~~~~~~~~~~~~~~~~~~~~~
.. _distance_api:
.. currentmodule:: pyriemann.utils.distance

.. autosummary::
    :toctree: generated/

    distance
    distance_euclid
    distance_riemann
    distance_logeuclid
    distance_logdet
    distance_kullback
    distance_kullback_sym


Mean
~~~~~~~~~~~~~~~~~~~~~~
.. _mean_api:
.. currentmodule:: pyriemann.utils.mean

.. autosummary::
    :toctree: generated/

    mean_covariance
    mean_euclid
    mean_riemann
    mean_logeuclid
    mean_logdet


Geodesic
~~~~~~~~~~~~~~~~~~~~~~
.. _geodesic_api:
.. currentmodule:: pyriemann.utils.geodesic

.. autosummary::
    :toctree: generated/

    geodesic
    geodesic_riemann
    geodesic_euclid
    geodesic_logeuclid


Tangent Space
~~~~~~~~~~~~~~~~~~~~~~
.. _ts_base_api:
.. currentmodule:: pyriemann.utils.tangentspace

.. autosummary::
    :toctree: generated/

    tangent_space
    untangent_space

Base
~~~~~~~~~~~~~~~~~~~~~~
.. _base_api:
.. currentmodule:: pyriemann.utils.base

.. autosummary::
    :toctree: generated/

    sqrtm
    invsqrtm
    expm
    logm
    powm