kube_config
===========

Configuration files for my kubernetes cluster

Dashboard
---------

To get access token: `kubectl -n kubernetes-dashboard describe secret $(kubectl -n kubernetes-dashboard get secret | grep admin-user | awk '{print $1}')`
