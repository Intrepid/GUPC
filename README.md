# GNU Unified Parallel C (GNU UPC)
The GNU UPC toolset provides a compilation and execution environment for programs written in the UPC (Unified Parallel C) language. The GNU UPC compiler extends the capabilities of the GNU GCC compiler.

## Features
* UPC Language Specification version 1.3 compliant
* Based on GNU GCC
* GPL licensed
* Fast bit packed pointer-to-shared support
* Configurable pointer-to-shared representation
* Support for uniprocessor and symmetric multiprocessor systems
* Runtime support for Infiniband based clusters with Portals 4.0 library support.
* Support for many large scale machines and clusters in conjunction with Berkeley UPC runtime
* Runtime support for UPC collectives
* Runtime support for UPC thread affinity via Linux scheduling affinity and NUMA package
* Runtime support for the UPC Atomic Memory Operations library defined in the UPC Specification version 1.3.
* Runtime support for the UPC pointer-to-shared castability library defined in the UPC Specification version 1.3.
* Runtime support for the UPC asynchronous shared memory bulk copy operations library defined in the UPC Specification version 1.3.
* Runtime support for UPC thread backtrace
* Runtime support for parallel debugging tools with MPIR capabilities
* Runtime support for the STAT backtrace visualization tool

## Supported Platforms
At this time, GNU UPC is available on the following platforms:

* Intel x86_64, Linux 64 bit uniprocessor or multiprocessor systems (RHEL, SUSE, Fedora, CentOS, Ubuntu)
* Intel x86_64, Apple Mac OS X system
* Intel x86, Linux 32 bit systems (Redhat based distributions)
* IBM PowerPC, IBM Power6/Power7 Linux based systems (including PERCS)

If you would like to learn of future ports to other platforms, or would like to discuss the feasibility of implementing GNU UPC on a platform of interest to you, we recommend that you join the GNU UPC discussion list.

## Downloads
See the project "release" tab for the latest [source release](https://github.com/Intrepid/GUPC/releases).

## Berkeley UPCR Runtime Integration
The GUPC compiler can be used to compile UPC programs which are linked the GASNet based UPC runtime (called UPCR) developed by Berkeley (LBNL). The GUPC and Berkeley (UPCR) runtime combination is available on all platforms supported by GUPC. Use of the UPCR runtime increases the range of communication methods that can be used to implement UPC re- mote access and synchronization primitives. More information on the Berkeley UPCR project site at: the UPCR web site http://upc.lbl.gov/.

## License
GNU UPC is implemented as an extension to the GNU C Compiler (GCC) and is distributed under the terms of the GNU General Public License.

