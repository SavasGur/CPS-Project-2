# CPS-Project-2
Cyberphysical Systems and IoT Security Project 2 files.

## Installation
1. First the repository has to be downloaded fully.
2. The saved simulations can be found in results in their consecutive names given to the folders.
3. Cooja simulator can be run with commands <br>
   $  cd Contiki-3.0/tools/cooja <br>
   $  ant run
5. The simulations can be opened directly inside Cooja.

# Changes made in order to reproduce the paper

## DIS Flooding Attacker Node
The idea is the same as the Z1 mote code given in the class, rpl-timers.c and rpl-private.h files have been modified to allow a DIS flooding attack by a normal mote c file (udp-client.c) added to a mote in the simulation. <br>
Modified files are in the DIS-flooding folder.

##  IDS implementation
-IDS codes can be found in /Contiki-3.0/core/net/rpl/rpl-icmp6.c <br>
(modified lines or added code has been given with comments)
