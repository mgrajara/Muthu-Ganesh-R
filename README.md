# Muthu-Ganesh-R
Second round written test - Shortest path to transfer bags between Gates to reach the destination

I developed this assignment in such a way it works exactly the same way as given in sample Input.

As various Input sections are put in different classes, maintanence and evolution of this project is quite easy. To include a new feature, we just need to modify the respective class / corresponding hashmap to accommodate the changes.

Say, Two flight with same id but originates at different time in a day. As per the current expectation this is not required and I coded the same way. If incase the same flight scheduled two times in a day, then we can accomadate it by just modifying the depMap HashMap key to include "flightId+time".
