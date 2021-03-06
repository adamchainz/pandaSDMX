pandaSDMX
===========

Description: A Python- and pandas-powered client for statistical data and metadata exchange
Author: Dr. Leo <fhaxbox66@gmail.com>
License: Apache 2.0
Documentation: http://pandasdmx.readthedocs.org
Development website: https://github.com/dr-leo/pandasdmx/


Purpose of this project
====================
 
pandaSDMX is SDMX software 
that facilitates the acquisition and analysis of SDMX-2.1 compliant data and metadata.
These can be rendered in various formats:

* as a hierarchical data structure following closely the SDMX 2.1 information model
  Technically, the model is a layer on top of the XML structure rendered by
  SDMX web services.
* as arbitrary output generated by dedicated writers. 
  Currently, there is only one writer rendering data as pandas Series and DataFrames.
    
  
  
  Credits
  ===============
  
  pandaSDMX originally started as a fork of
  https://github.com/widukind/pysdmx.
  
Even if pandaSDMX would not have been possible without the
inspiring work done for that project, 
the author decided to rewrite it from scratch.
Therefore, pandaSDMX is now an independent project.
  
pandaSDMX ships with a patched version of aadict, 
a useful wrapper around the standard Python dict. It also contains sample data and metadata from
the SDMX user guide.   