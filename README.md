# fix_oc-mirror_icsp.sh
oc-mirror does not create a valid imageContentSourcePolicy and this script will fix it. Thanks.

Make sure the mapping.txt is in the same folder.\n
./fix_oc-mirror_icsp.sh\n
oc create -f cs-new.yaml\n
oc create -f icsp-new.yaml
