# NetworkingArchitectures
High speed networks connecting clusters


Network switches seem to bottleneck a lot of builds and capable hardware is prohibitively expensive.  

Is it possible to make more affordable network switches in the 10 Gb range? Is this a copper interface or optical?  

Required blocks:
  CPU to control messages and protocol  
  FPGA to support high speed interface and possibly process signal to feed to the CPU  
  
 
 
 More specifically, what are we designing.
 
 A network switch with 48 ports that can handle high speed ethernet. This might start at 1 GHz and we'll see what it takes for 10 GHz.  
 
 A starting design might be an 8 port 1 GHz switch and see what it takes to expand ports and speed.  
 
 [Texas Instruments reference design](<https://www.ti.com/solution/data-center-switches#tech-docs> "Other networking resources available on TI as well")
