# openshift-proxy-pull-test
This repository contains the Dockerfile building the openshift-proxy-pull-test image.  If the http proxy is set by controller config,  [MCO](https://github.com/openshift/machine-config-operator) will validate the proxy by pulling this image through the proxy.  The proxy is valid, if the image can be successfully pulled.
