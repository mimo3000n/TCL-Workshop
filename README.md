# TCL-Workshop
VSD TCL Workshop

Goal of this workshop is getting familiar with TCL programming.
We will implement a TCL-box with read csv file which is passed an an argument to the TCL program.
The prorgam will analyse input, run differen commands like yosys,... and generate a timing file at the end which is shown as output.


i try to use local wsl environment for workshop, i personally prefer it insted using a vdi.

preparation of wsl for workshop:

we have to install tcsh, yosys, build-essential (need for g++), cmake

``` cmd


sudo apt update
sudo apt upgrade

sudo apt install tcsh
sudo apt install build-essential
sudo apt install yosys
sudo apt  install cmake

 git clone https://github.com/OpenTimer/OpenTimer.git

cd OpenTimer
mkdir build
cmake ../ -DCMAKE_CXX_STANDARD=17
make
make test
```

wsl should be ready doing workshop, maybe i have to extend PATH findingOpenTimer binaries.





Day 1

create vsdsynth

implement error handling - no csv file ist passed to vsdsynth.tcl, file with is passed to vsdsynth doesnt exist, if "-help" ist passed to vsdsynth a usage msg should be print out

create tcl script "vsdsynth" via vim

Day 2

Day 3

Day 4

Day 5
