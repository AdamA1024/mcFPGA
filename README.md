# mcFPGA
### Hardware implementation of Monte Carlo simulation for pricing European Call options. Advantages:
 - Using PYNQ-z1 FPGA board to parallelize simulations, without the overhead created by managing multiple threads in traditional software.
 - Specialized units, for example for arithemtic, compared to general purpose units avaliable in CPU.
 - Higher energy efficiency and throughput, crucial for intensive applications like Monte Carlo.
 - Low-latency by locating data close to computation.
