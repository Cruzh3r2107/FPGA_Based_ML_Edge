# FPGA_Based_ML_Edge
This is the capstone project for MECPS under the guidance Prof. Eli Bozorgzadeh, department of Center for Cyber Physical Systems. This project is about running machine learning algorithm on the Xilinx Kria KV260. 

Abstract: FPGAs are energy-efficient alternatives to GPUs as accelerators to be deployed in 
edge computing systems. In this project, a network of embedded devices such as raspberry 
pis are wirelessly connected to an edge node which is an FPGA device to accelerate the vision 
algorithms running on the images sent by the end devices. Students learn how to handle 
multiple accelerators running on an FPGA at the same time. Also, they explore how to allocate 
accelerators and schedule the requests to the accelerators. The accelerators are ML-based 
vision algorithms. They also investigate whether the ML applications should run on the enddevice or the edge if the queue to access the FPGA edge accelerators are too long. 

Learning Objectives:
1. Study and analysis:
a. FPGA design tools
b. FPGA ML engine to generate hardware accelerators
c. Transmit images from end devices to FPGA edge node
2. Implementation:
a. Implement FPGA ML accelerators on FPGAs
3. Optimization:
a. Policies for allocating multiple accelerators on FPGA if needed
b. Policies to process the accelerator requests from the end devices
Technology and Tools:
• C/C++ and embedded Linux
• AMD/Xilinx Kria KV260 Vision AI development board
• 3-4 Raspberry pi boards (if needed)
• Some prior experience with FPGA tools such a AMD Vitis is preferred but not required
Project Illustration:
![image](https://github.com/user-attachments/assets/d7da3869-2996-4de7-adbf-59f21edd4ea0)

KV-260 SPECIFICATIONS: 
RAM : DDR 4GB
ETHERNET: 10/100/1000 Mb/s
Primary boot memory: 512 Mb QSPI
Secondary boot memory: microsD card (in our case 32 gb) 

