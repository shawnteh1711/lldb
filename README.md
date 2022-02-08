# lldb
lldb debug

### Basic flow
#compile with the flag that makes lldb work by magic

gcc -g

#then run lldb on the executable

lldb a.out

#then put a breakpoint at any function you want to debug

b main

#then run the program

run

#move through the program with next

n

#if you want to repeat the last command (in this case next)
#then just hit enter and you'll move to the next line

#want to use the lldb gui? Well then you've come to the wrong
#place. The gui is confusing as fuck.

#you can look at variables with

print [var_name]

#or print all variables (frame all variables) with

fr v

#once you've looked at enough variables to see
#where you messed up, type exit and you'll be teleported
#back to your terminal

exit


#### Reference
1. [Video](https://www.youtube.com/watch?v=3BkEOvI36Ds)
