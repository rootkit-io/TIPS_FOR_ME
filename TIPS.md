> Author : Jesse 

# STARTS NOW:

    ## If you have done a pentest burn the system completely so nothing left on there before going to a diffrent pentest because if something or some reports left things can go wrong.
    ## Use Bridged Network in VM's. Dont use Host-Only or NAT they can interfere with rev shell.
    ## Don’t store results and command logs on RPI Dropbox. Use /dev/shm, so when box reboots you don’t have the blue team trying to figure out what you done.
    ##One-liner to get hex instructions from objdump command:for i in $(objdump -d helloworld |grep "^ " |cut -f2); do echo -n '\x'$i; done; echo


  
