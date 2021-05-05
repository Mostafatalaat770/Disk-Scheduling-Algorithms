# Disk-scheduling

# About

Disk scheduling is done by operating systems to schedule I/O requests arriving for the disk. Disk scheduling is also known as I/O scheduling.
This program works as a simulation to a disk using some scheduling algorithms and compares the number of disk head movments between them.

# Problem Statement:

It is required to simulate some of disk scheduling algorithms. The required
algorithms to be implemented are as follows:

- First In First Out (FIFO)
- SCAN
- C-SCAN

# Algorithms

## FIFO

The simplest form of disk scheduling is, of course, the (FIFO) algorithm. This
algorithm is intrinsically fair, but it generally does not provide the fastest service.

## SCAN

In the SCAN algorithm, the disk arm starts at one end, and moves towards the
other end, servicing requests as it reaches each cylinder, until it gets to the other
end of the disk. At the other end, the direction of head movement is reversed, and
servicing continues. The head continuously scans back and forth across the disk.

## C-SCAN

C-SCAN is a variant of SCAN designed to provide a more uniform wait time.
Like SCAN, C-SCAN moves the head from one end of the disk to the other,
servicing requests along the way. When the head reaches the other end, however, it
immediately returns to the beginning of the disk without servicing any requests on
the return trip.
