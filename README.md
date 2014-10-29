# build_raid

Quick script to build a RAID10 vol on my OpenBSD storage device.

It builds a striped (bioctl -c 0) mirror (bioctl -c 1).

**Warning**: This will blow away all data on the disks!