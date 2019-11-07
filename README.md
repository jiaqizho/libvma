[![GitHub version](https://badge.fury.io/gh/mellanox%2Flibvma.svg)](https://badge.fury.io/gh/mellanox%2Flibvma)
[![Coverity Scan Build Status](https://scan.coverity.com/projects/8025/badge.svg)](https://scan.coverity.com/projects/libvma)

### Introduction
Mellanox's Messaging Accelerator (VMA) boosts performance for message-based and streaming applications such as those found in financial services market data environments and Web2.0 clusters. It allows application written over standard socket API
to run over Ethernet and/or Infiniband from user-space with full network stack bypass. 
  
The [VMA architecture](https://github.com/Mellanox/libvma/wiki/Architecture) page includes additional information.  

### Download
Get all download and installation information [here](https://github.com/Mellanox/libvma/wiki/Downloads).  
or some quick instruction in order to [build VMA from source](https://github.com/Mellanox/libvma/wiki/Build-Instruction).  
  
### Technical Support
Have a question? please open a [github issue](https://github.com/Mellanox/libvma/issues) or contact support@mellanox.com.  

### Additional Information
* Refer to the libvma [README.txt](https://github.com/Mellanox/libvma/blob/master/README.txt)
* Main VMA page on Mellanox.com: http://www.mellanox.com/vma/
* Check out the rest of the Wiki pages in this project

### SPDK Information
* Refer to the [spdk](https://github.com/spdk/spdk)
* Why we need spec version of VMA? Bacuase we all know spdk base on dpdk, and dpdk have rte have some conflict with VMA , so i custom this spec version for spdk use.
