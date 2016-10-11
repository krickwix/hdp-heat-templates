# hdp-heat-templates
Automatically provision &amp; deploy a HortonWorks Data Platform on OpenStack
Requires a centos7 image with os-collect-config and ansible elements installed.
Default parameters can be changed in hdp_env.yaml
```
openstack stack create -t hdp.yaml -e hdp_env.yaml -e hdp_registry.yaml myHDPCluster
```
