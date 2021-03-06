============
GeoDataFrame
============
.. currentmodule:: geopandas

A ``GeoDataFrame`` is a tabular data structure that contains a column
which contains a ``GeoSeries`` storing geometry.

Constructor
-----------
.. autosummary::
   :toctree: api/

   GeoDataFrame

Reading and writing files
-------------------------

.. autosummary::
   :toctree: api/

   GeoDataFrame.from_file
   GeoDataFrame.from_features
   GeoDataFrame.from_postgis
   GeoDataFrame.to_file
   GeoDataFrame.to_json
   GeoDataFrame.to_parquet
   GeoDataFrame.to_feather
   GeoDataFrame.to_postgis

Projection handling
-------------------

.. autosummary::
   :toctree: api/

   GeoDataFrame.crs
   GeoDataFrame.set_crs
   GeoDataFrame.to_crs

Active geometry handling
------------------------

.. autosummary::
   :toctree: api/

   GeoDataFrame.rename_geometry
   GeoDataFrame.set_geometry

Aggregating and exploding
-------------------------

.. autosummary::
   :toctree: api/

   GeoDataFrame.dissolve
   GeoDataFrame.explode

Plotting
--------

.. autosummary::
   :toctree: api/

   GeoDataFrame.plot


Spatial index
-------------

.. autosummary::
   :toctree: api/

   GeoDataFrame.sindex

Interface
---------

.. autosummary::
   :toctree: api/

   GeoDataFrame.__geo_interface__

All pandas ``DataFrame`` methods are also available, although they may
not operate in a meaningful way on the ``geometry`` column. All methods
listed in `GeoSeries <geoseries>`__ work directly on an active geometry column of GeoDataFrame.

