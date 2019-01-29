

Health Points
=============

This is my observation from the actual O2Jam client itself.
The HP starts with 100, I've confirmed this from the memory address that points to the HP bar value.
Each difficulty will have it's own value for each judgement.

Easy Difficulty
---------------

* Miss : -5
* Bad : -1
* Good: +0.2
* Cool : +0.3

Normal Difficulty
-----------------

* Miss : -4
* Bad : -0.7
* Good: +0.1
* Cool : +0.2

Hard Difficulty
---------------

* Miss : -3
* Bad : -0.5
* Good: 0
* Cool : +0.1

Additional Info
---------------

If pill(s) count > 1, remove 1 pill for each bad taken and convert it to cool until it reaches 0.



