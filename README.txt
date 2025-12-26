26DEC25  PROJ2
 Some more practice with CLI. Today we started off by learning how to check Linux distro and Kernel ver.
 Then veared off into the rhubarb in regards to log files and the Stream Based Error Logging via STDERR.
  there are 3 pipes essentially tied to any program: an input , and output , and an error pipe. 
  STDIN , STDOUT , STDERROR . (1)  , (2) , (3)

We can use the > and the >> to either overwrite or append. then give it a pipe to grab data from and a file to either create or work with.
ls nofile.txt 2>> log.txt 

HUGE! 