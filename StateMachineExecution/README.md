Run a model debug session with this model to illustrate the rules for which transition that will be triggered in case of hierarchical state machines.

Send these events: 
* t5 (internal transition - no state changes)
* t6
* t3 (what do you think will happen?)
* t2 (same thing)
* t6
* t7
* t6
* t7 (note different behavior than before, because C is now entered for the 2nd time)
* t2
