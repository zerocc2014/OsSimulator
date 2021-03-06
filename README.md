# OsSimulator
Simulated operating system written in Java 8.
# 
The OS will take in a specific configuration file and a specific meta data file to load and run an operating system.

### Example Configuration File

Start Simulator Configuration File <br/>
Version/Phase: 3.0 <br/>
File Path: Test_3a.mdf <br/>
Processor cycle time {msec}: 5 <br/>
Monitor display time {msec}: 22 <br/>
Hard drive cycle time {msec}: 150 <br/>
Projector cycle time {msec}: 550 <br/>
Keyboard cycle time {msec}: 60 <br/>
Memory cycle time {msec}: 10 <br/>
Scanner cycle time {msec}: 15 <br/>
System memory {kbytes}: 2048 <br/>
Memory block size {kbytes}: 128 <br/>
Projector quantity: 4 <br/>
Hard drive quantity: 2 <br/>
Log: Log to File <br/>
Log File Path: logfile_1.lgf <br/>
End Simulator Configuration File <br/>


### Example Meta Data File

Start Program Meta-Data Code: <br/>
S{begin}0; A{begin}0; P{run}11; M{allocate}2; <br/>
O{monitor}7; I{hard drive}8; O{projector}20; <br/>
M{allocate}4; A{finish}0; A{begin}0; O{projector}6; M{allocate}3; I{hard drive}7; <br/>
O{hard drive}2; O{hard drive}16; M{allocate}4; <br/>
P{run}6; O{projector}4; A{finish}0; A{begin}0; M{block}6; I{keyboard}17; <br/>
M{block}4; P{run}5; P{run}5; O{hard drive}6; <br/>
P{run}18; A{finish}0; S{finish}0. <br/>
End Program Meta-Data Code. <br/>

