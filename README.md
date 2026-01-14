# TCL-Workshop

--------------------------------------------------------------------------------------------------------------

&nbsp;
<img width="896" height="627" alt="image" src="https://github.com/user-attachments/assets/c9120089-2464-4a21-af47-e8aec809ae52" />
&nbsp;

## Overview:

A Hands-On Workshop to Tackle Scripting based Questions in Synthesis, Physical design and STA roles. This transformative 10-day workshop equips participants with advanced TCL scripting skills for automating digital design flows. The journey begins with TCL fundamentals and extends into complex topics such as constraints parsing, memory module synthesis with Yosys, and quality of results (QOR) analysis. The program is tailored for professionals and students requiring industry-grade lab certification from VSD.

--------------------------------------------------------------------------------------------------------


## VSD TCL Workshop

Goal of this workshop is getting familiar with TCL programming.
We will implement a TCL-box with read csv file which is passed an an argument to the TCL program.
The prorgam will analyse input, run differen commands like yosys,... and generate a timing file at the end which is shown as output.


i try to use local wsl environment for workshop, i personally prefer it insted using a VM.

preparation of wsl for workshop:

i am using a ubuntu 24.04 installation on my pc in wsl environmaent!

``` cmd

PS C:\Users\mimo3> wsl -l -v
  NAME            STATE           VERSION
* Ubuntu-24.04    Running         2
  Ubuntu          Stopped         2
PS C:\Users\mimo3>

```

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
