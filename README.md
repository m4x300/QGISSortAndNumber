Sort and Number plugin
=================

Description
-----------

This plugin was coded in response to the recurrent issue of numbering a sorted attribute table, which has (currently) no simple workaround in QGIS. It creates a new field that contains the order of features, after sorting by up to 3 criteria.

UI
--

First, select the vector layer you want to number. Then, select the fields you want to order. First field has priority on second field, which has priority on third field. Default order is ascending. Check the box next to a field to choose a descending order.  Finally, enter the name of the numbering field to create. Default is 'order'.


