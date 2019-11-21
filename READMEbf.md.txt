Brainflayer
===========

Brainflayer is a Proof-of-Concept brainwallet cracking tool that uses


Repositories:

$ sudo apt-get update

$ sudo apt-get install build-essential

$ sudo apt-get install git

$ sudo apt-get install make

$ sudo apt-get install autotools-dev

$ sudo apt-get install zlib1g-dev

$ sudo apt-get install libssl-dev

$ sudo apt-get install libgmp-dev

$ sudo apt-get install libgmp3-dev

$ sudo apt-get libcurl4-openssl-dev

$ sudo apt-get install libtool

$ sudo apt-get install autoconf

$ sudo apt-get install automake

$ sudo apt-get install pkg-config

$ sudo apt-get install libgtk-3-dev

$ sudo apt-get libjansson-dev

$ sudo apt-get update

$ sudo apt-get update

~$ cd brainflayer

~$ make all


EXECUTION:


Precompute the bloom filter:


./hex2blf yourlist.txt.hex yourlist.hex


./hex2blf example.hex example.blf


============================================


Run Brainflayer:


./brainflayer -v -b example.blf -i dictionary.txt


==== Advanced======



./brainflayer -v -I 0000000000000000000000000000000000000000000000000000000000000001 -b example.blf
./key256 | ./brainflayer -v -c cu -b example.blf -o found.txt


