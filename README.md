# File System

[1.Local File System](#local-file-system)

​	[1.1 Kernel File System](#kernel-file-system)

​	[1.2 User-Space File System](#user-space-file-system)

[2.Distributed File System](#distributed-file-system)

​	[2.1 General Purpose File System](#general-purpose-file-system)

​	[2.2 High Performance Computing](#high-performance-computing-hpc)

​		[2.2.1 Burst Buffer File System](#burst-buffer-file-system)

[3.Surveys](#surveys)

## Local File System

### Kernel File System

[Linux File System](https://www.kernel.org/doc/html/latest/filesystems)

[1991 SOSP] **The Design and Implementation of a Log-Structured File System**. [[PDF](https://people.eecs.berkeley.edu/~brewer/cs262/LFS.pdf)]

[1995] **Design and Implementation of the Second Extended Filesystem**. [[PDF](http://e2fsprogs.sourceforge.net/ext2intro.html)]

[1998] ext3: **Journaling the Linux ext2fs Filesystem**. [[PDF](https://pdos.csail.mit.edu/6.828/2020/readings/journal-design.pdf)]

### User-Space File System

> FUSE: **F**ilesystem in **USE**rspace, https://github.com/libfuse/libfuse

[2004 ATC] **Wayback: A User-level Versioning File System for Linux**. [[PDF](https://www.usenix.org/legacy/publications/library/proceedings/usenix04/tech/freenix/cornell/cornell.pdf)]

[2017 FAST] **To FUSE or Not to FUSE: Performance of User-Space File Systems**. [[PDF](https://www.usenix.org/system/files/conference/fast17/fast17-vangoor.pdf)]

## Distributed File System

### General Purpose File System

[1987 SOSP & 1988 TOCS] AFS: **Scale and performance in a distributed file system**. [[PDF](https://dl.acm.org/doi/pdf/10.1145/35037.35059)]

[1985] **Design and Implementation of the Sun Network Filesystem**. [[PDF](http://citeseerx.ist.psu.edu/viewdoc/download;jsessionid=06C4017AA8BFD7230B528C0F94A21B1D?doi=10.1.1.14.473&rep=rep1&type=pdf)]

[2003 SOSP] GFS: **The Google file system**. [[PDF](https://dl.acm.org/doi/pdf/10.1145/945445.945450)]

[2006 OSDI] **Ceph: A Scalable, High-Performance Distributed File System**. [[PDF](https://www.usenix.org/legacy/events/osdi06/tech/full_papers/weil/weil.pdf)]

[2010 MSST] **The Hadoop Distributed File System**. [[PDF](https://www.storageconference.us/2010/Papers/MSST/Shvachko.pdf)]

[2010 OSDI] **Finding a needle in Haystack: Facebook’s photo storage**. [[PDF](https://www.usenix.org/legacy/events/osdi10/tech/full_papers/Beaver.pdf)]

[2011 ATC] **TidyFS: A Simple and Small Distributed File System**. [[PDF](https://www.usenix.org/legacy/events/atc11/tech/final_files/Fetterly.pdf)] [[Slides](https://www.usenix.org/legacy/events/atc11/tech/slides/fetterly.pdf)]

[2019 SOSP] **File systems unfit as distributed storage backends: lessons from 10 years of Ceph evolution**. [[PDF](https://dl.acm.org/doi/pdf/10.1145/3341301.3359656)]

[2021 FAST] **Facebook’s Tectonic Filesystem: Efficiency from Exascale**. [[PDF](https://www.usenix.org/system/files/fast21-pan.pdf)]

### High Performance Computing (HPC)

[2000] **PVFS: A Parallel File System for Linux Clusters**. [[PDF](https://www.usenix.org/legacy/publications/library/proceedings/als00/2000papers/papers/full_papers/carns/carns.pdf)]

[2002 FAST] **GPFS: A Shared-Disk File System for Large Computing Clusters**. [[PDF](https://www.usenix.org/legacy/publications/library/proceedings/fast02/full_papers/schmuck/schmuck.pdf)]

[2003] **Lustre: Building a File System for 1,000-node Clusters**. [[PDF](https://www.kernel.org/doc/ols/2003/ols2003-pages-380-386.pdf)]

[2008 FAST] **Scalable Performance of the Panasas Parallel File System**. [[PDF](https://www.usenix.org/legacy/events/fast08/tech/full_papers/welch/welch.pdf)]

#### Burst Buffer File System

[2016 SC] BurstFS: **An Ephemeral Burst-Buffer File System for Scientific Applications**. [[PDF](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7877147)]

[2018 CLUSTER & 2020 JCST] **GekkoFS – A temporary distributed file system for HPC applications**. [[CLUSTER PDF](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8514892)] [[JCST PDF](https://link.springer.com/content/pdf/10.1007/s11390-020-9797-6.pdf)] [[Codes](https://storage.bsc.es/gitlab/hpc/gekkofs)]

### Surveys

[1989] **A Survey of Distributed File Systems**. [[PDF](https://www.cs.cmu.edu/~satya/docdir/satya89survey.pdf)]

[2008 NCM] **A Taxonomy and Survey on Distributed File Systems**. [[PDF](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=4623994)]

[2015] **Analysis of Six Distributed File Systems**. [[PDF](https://hal.inria.fr/hal-00789086/file/a_survey_of_dfs.pdf)]

[2015] A Survey on Distributed File System Technology.

[2016 ICCCA] **Evolution and Analysis of Distributed File Systems in Cloud Storage: Analytical Survey**. [[PDF](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7813828)]
