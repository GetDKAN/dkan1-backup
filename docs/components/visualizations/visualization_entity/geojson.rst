GeoJSON
=======
.. warning::

	Under Development. Do not use on production.

Enable the geojson bundle:

.. code-block:: php

	$ drush -y visualization_entity_geojson_bundle
	$ drush cc all


Create Visualization
--------------------
+ Look for **Content -> Add Content -> Resource** in the admin menu and click on it.

+ Upload a geojson data file for the resource

.. image:: https://dkan-documentation-files.s3.us-east-2.amazonaws.com/dkan1/geojson-step-01.png

+ Fill the required fields, enter 'geojson' in the format field, and **save** the resource

.. image:: https://dkan-documentation-files.s3.us-east-2.amazonaws.com/dkan1/geojson-step-03.png

+ Look for **Structure -> Entity Types -> Visualization -> Geojson Visualization -> Add Geojson Visualization** in the admin menu and click on it.

+ Set a **title**
+ Select the **resource** containing the **geojson** data file you uploaded

.. image:: https://dkan-documentation-files.s3.us-east-2.amazonaws.com/dkan1/geojson-step-04.png

+ Click **Save** & Enjoy!

.. image:: https://dkan-documentation-files.s3.us-east-2.amazonaws.com/dkan1/geojson-step-05.png
