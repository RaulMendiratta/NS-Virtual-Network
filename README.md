# NS-Virtual-Network
This a bash script file to create a virtual network using linux namespaces and openvswitch.

This was used to test the tcp congestion algorithms implemented in linux.
Each node in the network is a linux namespace.

Network scheme:

C1        S1
  \      /
   R1--R2
  /      \
C2        S2
