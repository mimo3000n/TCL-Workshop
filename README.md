# TCL-Workshop
VSD TCL Workshop

Goal of this workshop is getting familiar with TCL programming.
We will implement a TCL-box with read csv file which is passed an an argument to the TCL program.
The prorgam will analyse input, run differen commands like yosys,... and generate a timing file at the end which is shown as output.


create vsdsynth

implement error handling - no csv file ist passed to vsdsynth.tcl, file with is passed to vsdsynth doesnt exist, if "-help" ist passed to vsdsynth a usage msg should be print out

create tcl script "vsdsynth" via vim
