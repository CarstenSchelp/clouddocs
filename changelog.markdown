---
layout: default
---

# Change Log
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/)
and this project adheres to [Semantic Versioning](http://semver.org/).

## 2019-06-05

### Security
* [Mitigation of MDS](./notices/mds)

### Changed
* HyperThreading on all compute hosts disabled
* CPU overcommiting enabled on all CPU compute hosts allocated to the coomon pool of resources

### Updated
* All images in the Marketplace to mitigate [MDS](./notices/mds)

## 2018-12-11

### Security
* [Mitigation of L1TF](./notices/L1TF)


## 2018-04-23

### Changed
* Restored the template and log tabs on the VM's tab for the user view (UI)

## 2017-10-06

### Removed
* Old DNS domain name discontinued (vm.surfsara.nl) 

## 2017-01-24

* Upgraded to OpenNebula 5.2, this includes a new look and feel for the user interface

## 2016-10-26

### Updated
* Ubuntu 14.04 (server/desktop) images to mitigate [dirty cow bug](https://www.ubuntu.com/usn/usn-3106-2/)
* Centos 6.8 image to mitigate [dirty cow bug](https://access.redhat.com/security/vulnerabilities/2706661)
* Centos 7.2 image to mitigate [dirty cow bug](https://rhn.redhat.com/errata/RHSA-2016-2098.html)

## 2016-10-05

### Added
* Ubuntu 16.04.1 server image.
* Ubuntu 16.04.1 [GPU visualization](gpu-visualization) image. 

## 2016-10-02

### Updated
* Centos image from 6.7 to 6.8

## <a name="cl-20160912"></a>2016-09-12

### Changed
* Domain from vm.surfsara.nl to surf-hosted.nl for new VM's.


