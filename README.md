6.12  One  technique for implementing lottery scheduling works by assigning processes lottery tickets ,
which are used for allocating CPU time .Whenever a scheduling decision has to be made, a lottery ticket is
chosen at random, and the process holding that ticket gets the CPU. The BTV operating system implements 
lottery scheduling by holding a lottery 50 times each second, with each lottery winner getting 20 milliseconds
of CPU time (20 milliseconds × 50 = 1 second).  
