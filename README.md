# local_manifests
This is the local_manifests.xml file that should be used to build Tipsy. 

Compared to the .dependencies, this ads : 
- dataservices => enables to get data over GSM/LTE network 
- vendor files => allows to boot phone :-)

It should be mentioned that a fix to get the data to be recovered once lost (because i.e. I was in a tunnel) should also be added. 
The fix can be found here : https://github.com/TipsyOs-Devices/device_oneplus_oneplus3/commit/229e45f19cbc11b4ba2b57a4c68103e54a7eac4c

Be advised : when applying the patch with sepolicy (last file to edit), the file has to be created and the first line has to be left out. 
