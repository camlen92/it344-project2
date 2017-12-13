# it344-project2
IT 344 Operating Systems: BYOOS - Build your own OS

Each student will design and create their own operating system using available kernel, drivers, application packages and utilities.  In order to successfully complete this project you will need to do the following.

plan and specify an application that requires an OS.
research source documents for building a Free or Open-Source (FOSS)-based OS.
Option: Major Configuration of an existing OS such as Windows (consult TA/instructor)
select the features you desire in the final system.
specify and acquire an appropriate hardware platform for your design (lab computers and some special computers are available through the TA or the cage).
Recommend using separate USB-Drive
search for available software that implements the desired features,
collect the necessary modules (source code). 
compile/assemble the system,
test that all the desired modules/features/applications work together (debug as necessary),
present the final system in a brief demonstration that shows its key features.
submit a report describing your design
 
FOSS software base: We will use Free or Open Source Software (FOSS) because it allows you to do this type of design and build exercise. Proprietary software does not generally permit you to select and re-arrange modules, however you make select any software base you prefer but it is essential that you have access to the modules and some method of combining (compiling) them.

Note that while Linux is an obvious choice for this exercise, it is not the only choice. There are others.

If you have access to some special operating system software base that you would like to use, which doesn’t fit the above definition consult with the instructor or TA before proceeding.

Individual projects: Each student will complete this task individually but since it is probable that multiple students will be working on similar projects students may still cooperate to solve problems.

Minimum Solution:

Every system must have at least
    - A kernel with IO suitable for the specified system application
    - multiple software applications which access the IO and communicate with the user. 
    - file system
    - multi-tasking
    - memory management (except for embedded systems with no hardware support)
    - some form of networking communication
    - some means of updating, backing up and maintaining the system

That's the minimum. A typical system will probably have a complete OS with full memory management, file system, multi-tasking, Ethernet and wireless/Bluetooth/USB/IrDA/other support, hi-res monitor, multiple windowing apps, compiler and system maintenance utilities loaded, multi-user support, KLM support, etc.
