---
title: My NAS Making Documentation
index_img: /img/nas.jpg
banner_img: /img/nas.jpg
date: 2023-12-24 18:38:31
tags:
categories : [Electronics, Computer]
---

Making NAS or Network Attached Storage is not easy, especially if your PC is ancient, here is my journey documented on the quest of making NAS with my old pc

---

What is NAS?
Network Attached Storage (NAS) is a type of dedicated file storage device that provides local-area network (LAN) nodes with file-based shared storage through a standard Ethernet connection. NAS devices are often used to store and share data among multiple users, and they typically provide access to files using protocols such as NFS (Network File System) or SMB/CIFS (Server Message Block/Common Internet File System).

There are several software options available for setting up and managing Network Attached Storage (NAS) devices. These software solutions often provide features such as file sharing, data protection, remote access, and more. 
RAID (Redundant Array of Independent Disks) is a storage technology that combines multiple physical hard drives into a single logical unit. The goal of RAID is to improve data reliability, performance, or both, depending on the specific RAID level used. RAID accomplishes this by distributing or mirroring data across the drives in the array. There are several RAID levels, each with its own characteristics:

    RAID 0 (Striping):
        Data is divided into blocks, and each block is written to a different drive in the array.
        Offers increased performance by allowing multiple drives to work in parallel.
        No redundancy; if one drive fails, all data in the array is lost.

    RAID 1 (Mirroring):
        Data is duplicated across two or more drives.
        Provides fault tolerance by maintaining an identical copy of the data on each drive.
        Good for data redundancy and reliability but doesn't offer increased performance.

    RAID 5 (Striping with Parity):
        Data is striped across multiple drives, and parity information is distributed.
        Offers a balance between performance and data redundancy.
        Can withstand the failure of a single drive without data loss.

    RAID 6 (Striping with Double Parity):
        Similar to RAID 5, but with an additional parity block for increased fault tolerance.
        Can withstand the failure of two drives without data loss.
        Provides higher fault tolerance than RAID 5 but may have a higher write overhead.

    RAID 10 (Combination of RAID 1 and RAID 0):
        Combines mirroring (RAID 1) and striping (RAID 0).
        Provides both performance improvement and data redundancy.
        Can withstand the failure of one or more drives, depending on the specific configuration.

    RAID 50 and RAID 60:
        Combines RAID 5 or RAID 6 with RAID 0 for striping.
        Offers a balance between performance and fault tolerance by striping data across multiple RAID 5 or RAID 6 arrays.

The choice of RAID level depends on factors such as the desired level of data protection, performance requirements, and the number of available drives. RAID is commonly used in servers, storage arrays, and network-attached storage (NAS) devices to enhance data reliability and performance.

More to follow