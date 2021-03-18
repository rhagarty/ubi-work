# ubi-work

UBI - Universal Base Image
* works on OpenShift and k8s

igc - IBM Garage commands

Work items:

* build a custom image (JanusGraph)
* Fork or clone the JanusGraph image
* change dockerfile using toolkit
* whenever JanusGraph image is update, pull latest changes and rebuild
* rebuild = kick of pipeline in tekton
* learn starter kit tutorial (cloudnativetoolkit.dev)

2 approaches:

1. Start with starter kit
    * python (JanusGraph is java)
    * sub out /src with new code from sample code
    * tests will not work
    * run toolkit

2. Take sample app and then add in meta data to get to work
    * meta data probably from starter kit
    * `igc enable` will populate repo with stuff toolkit will need 


Cloud-Native Toolkit Guide : https://cloudnativetoolkit.dev/

Tutorial on how to how to build a UBI from a starter kit:
https://github.ibm.com/TT-ISV-org/images/blob/main/toolkit/build-starter-kit.md

What is the toolkit?

