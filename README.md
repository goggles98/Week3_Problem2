# Week3_Problem2
Traffic Light using Moore

Initially the system remains on standby till 'start == 1', which happens after 4 seconds
The system reads this for one time step and at the 5th second goed to stop.

At stop, only 'stop == 1'. All the others go to 0. System remains at stop for 5 seconds.
System remains at get ready for '3 seconds' and then transitions to 'Go'.
THe system remains at "Go' for 5 seconds and the cycle is repeated backwards.
