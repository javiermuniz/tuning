SST Development
===========

Installation
-------------

### EcuFlash
These tables and methods require EcuFlash (http://www.tactrix.com/index.php?option=com_content&view=category&layout=blog&id=36&Itemid=58).

Get your proper base XML:

Base files can be located in the base_maps directory. These are the same maps that are located on GoldenEvo's site (http://goldenevo.com/). I am simply putting them into github in order to track revision history.

Install the XML into the EcuFlash directory:

This is usually C:\Program Files (x86)\OpenECU\EcuFlash\rommetadata\mitsubishi\evo or C:\Program Files\OpenECU\EcuFlash\rommetadata\mitsubishi\evo for 64-bit and 32-bit OSes respectively.

### EcuFlash Crashing?

If you have issues with EcuFlash crashing after you have copied in the proper XML and attempted to load your ROM this is usually due to a missing include XML. To figure out which include is missing, open up the XML that you downloaded and look for a line that looks like this:

  <include>52690021</include>
  
Downloading and installing all of the base maps should fix any of these problems as well.