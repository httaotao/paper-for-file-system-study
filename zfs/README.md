# zfs相关论文和资料

### The Zettabyte File System

推荐理由: zfs的早期论文

### ZFS On-Disk Specification

推荐理由: zfs disk format结构体说明资料，如果有zfs基础，非常适合阅读，但很枯燥

### Introducing ZFS on Linux

推荐理由: zfs的运维手册, 可以理解一些操作
ps: 网上还有另外一本zfs on linux,那个是datta公司的书，英文书，也非常值得推荐看看,但是比较贵

### Unioning of the Buffer Cache and Journaling Layers with Non-volatile Memory

推荐理由: 理解zfs的事务原理的论文，原理思想和zfs txg非常类似，但是也有不一样的地方

### Low-Latency Synchronous IO For OpenZFS Using Persistent Memory

推荐理由: 21年 openzfs pmem 论文，非常优秀值得推荐阅读，建议有zfs基础

### The Slab Allocator: An Object-Caching Kernel Memory Allocator

推荐理由: Jeff先生的论文, zfs的metaslab和linux的slab都是这位大佬设计的, 值得看看

### Defragmentation Mechanisms for Copy-on-Write File-systems

推荐理由: defrag技术相关的论文，非常少见的，这个技术目前来说有利有弊, 可以结合Jeff先生的早期blog来理解。
          同时对于defrag的使用, 目前也有争议, openzfs官方大佬提过，建议使用快照和备份来替代可能会更加高效


