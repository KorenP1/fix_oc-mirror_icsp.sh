# fix_oc-mirror_icsp.sh
oc-mirror does not create a valid imageContentSourcePolicy and this script will fix it. Thanks.



Make sure the mapping.txt is in the same folder.

./fix_oc-mirror_icsp.sh

oc create -f cs-new.yaml

oc create -f icsp-new.yaml
