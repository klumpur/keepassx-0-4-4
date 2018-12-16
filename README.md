# keepassx-0-4-4
Keepassx installation

#Download keepassx :

https://www.keepassx.org/downloads/0-4

#Installation

1- sudo apt-get install cmake

2- sudo apt-get install libxtst-dev build-essential libqt4-dev

3- sudo apt-get install libssl-dev

# Edit file random.cpp /src/lib/random.cpp
- add line below #include "random.h" to #include <unistd.h>

- save and exit

#Compile All

- cmake ./

- make

- sudo make install 



