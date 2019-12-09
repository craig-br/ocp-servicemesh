 create subs with files
 1st elasticsearch
 2 jaeger
 3 kiali
 3 service mesh:w

oc new-project istio-system
oc create -f servmesh_cp_install.yml
oc create -f servmesh_member_roll.yml

oc new-project bookstore
oc apply -n bookinfo -f https://raw.githubusercontent.com/Maistra/bookinfo/maistra-1.0/bookinfo.yaml

