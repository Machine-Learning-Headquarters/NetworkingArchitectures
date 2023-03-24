# NetworkingArchitectures
High speed networks connecting clusters


## Why
Network switches seem to bottleneck a lot of builds and capable hardware is prohibitively expensive.  

Is it possible to make more affordable network switches in the 10 Gb range? Is this a copper interface or optical?  



## Required blocks:
  <li>CPU to control messages and protocol  </li>
  <li>FPGA to support high speed interface and possibly process signal to feed to the CPU  </li>
  
 
 
 ## More specifically, what are we designing.
 
 A network switch with 48 ports that can handle high speed ethernet. This might start at 1 GHz and we'll see what it takes for 10 GHz.  
 
 A starting design might be an 8 port 1 GHz switch and see what it takes to expand ports and speed.  
 
 [Texas Instruments reference design](<https://www.ti.com/solution/data-center-switches#tech-docs> "Other networking resources available on TI as well")

 [PANIC](https://www.usenix.org/conference/osdi20/presentation/lin)

 [FPGA NIC](https://spiral.imperial.ac.uk/bitstream/10044/1/86136/2/fpga2020switch.pdf)
