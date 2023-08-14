# Where to find what

**Author:** Sebastien Tourbier (@sebastientourbier)

**Date:** 2023 August 14th

Repository that references all achievements I have made during this last year. This might help one to be aware of all the tools and documentation that I have made available.

---

# Medical Informatics Platform (MIP)

## [`pytest-mip`](https://github.com/HBPMedical/pytest-mip)

Tool to test the up-and-running MIP `7.1.0` federations. For now it tests:
- public
- qa
- stroke (FERES)

**Documentation**:
- **Main page:** https://github.com/HBPMedical/pytest-mip#readme
- **Installation**: https://github.com/HBPMedical/pytest-mip#installation-instructions
- **How to run with Docker**: https://github.com/HBPMedical/pytest-mip#how-to-run-pytest-mip-using-the-docker-image
- **Add tests for a new MIP federation:** https://github.com/HBPMedical/pytest-mip#want-to-add-tests-for-a-new-mip-federation

## [`mip-dmp`](https://github.com/HBPMedical/mip-dmp)

Python tool with Graphical User Interface (GUI) to map datasets to a specific Common Data Elements (CDEs) metadata schema of a federation of the Medical Informatics Platform (MIP).

**Documentation**:
- **Main page:** https://hbpmedical.github.io/mip-dmp/
- **Installation**: https://hbpmedical.github.io/mip-dmp/installation.html
- **Commandline usage**: https://hbpmedical.github.io/mip-dmp/cmd_usage.html
- **GUI user guide**: https://hbpmedical.github.io/mip-dmp/ui_user_guide.html
- **Instructions for developers**: https://hip-infrastructure.github.io/datahipy/developer.html
- **Contributing guide**: https://hbpmedical.github.io/mip-dmp/contributing.html

## [`mip_schema`](https://github.com/HBPMedical/mip_schema)

Python package with commandline tools to manipulate Common Data Elements Metadata Schema for the Medical Informatics Platform (MIP). 

**Documentation**:
- **Main page**: https://github.com/HBPMedical/mip_schema#readme
- **How to install**: https://github.com/HBPMedical/mip_schema#how-to-install
- **Commandline tools usage**: https://github.com/HBPMedical/mip_schema#available-command-line-tools

## [`mip-feres`](https://github.com/HBPMedical/mip-feres)

Host well-documented notebooks and data that uses `mip_schema` and `mip-dmp` tools to support the curation / making of the CDEs metadata schema and the mapping of data coming from the different national registries of the FERES MIP federation.

**Documentation**:
- **Main page**: https://github.com/HBPMedical/mip-feres#readme
- **Installation**: https://github.com/HBPMedical/mip-feres#installation-of-python-environment-and-dependencies
- **How to run / edit the notebooks**: https://github.com/HBPMedical/mip-feres#how-to-run--edit-the-notebooks

---

# Human Intra-cerebral Platform (HIP)

## [`docker-elk`](https://github.com/HIP-infrastructure/docker-elk)

Setup a Elasticsearch/Logstash/Kibana stack with Docker and Docker-compose. This stack is responsible of the BIDS dataset indexing and search functionalities of the HIP. It can be installed on any platform that has Docker and Docker-compose installed.

**Documentation**:
- **Main page**: https://github.com/HIP-infrastructure/docker-elk#readme
- **Installation guidelines**: https://github.com/HIP-infrastructure/docker-elk#installation-guidelines
  - **First deployment**: https://github.com/HIP-infrastructure/docker-elk#first-elk-stack-deployment
  - **Re-deployment**: https://github.com/HIP-infrastructure/docker-elk#elk-stack-redeployment

## [`datahipy`](https://github.com/HIP-infrastructure/datahipy):

Containerized tool written in Python to handle neuroimaging and intracerebral data on the HIP adopting Brain Imaging Data Structure (BIDS). The tools provides commands to:
- interact with and create BIDS datasets
- interact with and create project datasets in the collaborative space of the HIP
- track changes with datalad versioning system
- publish BIDS datasets to the public space of the HIP
- clone public BIDS dataset available on the HIP to the user's private space

**Documentation**:
- **Main:** https://hip-infrastructure.github.io/datahipy
- **Installation:** https://hip-infrastructure.github.io/datahipy/installation.html
- **Commandline usage**: https://hip-infrastructure.github.io/datahipy/usage.html
- **Instructions for developers**: https://hip-infrastructure.github.io/datahipy/developer.html
- **Contributing guide**: https://hip-infrastructure.github.io/datahipy/contributing.html
  
## [`gateway`](https://github.com/HIP-infrastructure/gateway):

All methods that interact and create BIDS and collaborative project datasets with DataHIPy have been implemented in the [tools service](https://github.com/HIP-infrastructure/gateway/tree/master/src/tools) of the HIP Gateway.

Design specifications for the integration of dataset versioning and the development of public space inside the Gateway have been described in the following repo's issues:
  - https://github.com/HIP-infrastructure/gateway/issues/24
  - https://github.com/HIP-infrastructure/gateway/issues/25
  - https://github.com/HIP-infrastructure/gateway/issues/26
  - https://github.com/HIP-infrastructure/gateway/issues/27
  - https://github.com/HIP-infrastructure/gateway/issues/28
  - https://github.com/HIP-infrastructure/gateway/issues/29  

## [`hip`](https://github.com/HIP-infrastructure/hip):

Design specifications for the integration of dataset versioning and the development of public space inside the Gateway have been described in the following repo's issues:
- https://github.com/HIP-infrastructure/hip/issues/15
- https://github.com/HIP-infrastructure/hip/issues/16
- https://github.com/HIP-infrastructure/hip/issues/17
