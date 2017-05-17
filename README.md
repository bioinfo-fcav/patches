# patches
Patches for Source Code Trees

* apply-patch-inparanoid_4.1.sh - Patch for InParanoid v.4.1. The extra requirement besides diamond and blast+ is sam2xml.pl ( https://github.com/dgpinheiro/bioinfoutilities/blob/master/sam2xml.pl ). To apply this patch you need to put the script in the same directory containing "./inparanoid_4.1" and just run "./apply-patch-inparanoid_4.1.sh". To run this script you need md5sum, openssl and gpg, in addition to the stand-alone InParanoid v.4.1 source code (http://software.sbc.su.se/cgi-bin/request.cgi?project=inparanoid). 
