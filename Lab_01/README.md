## Zynq UltraScale+ MPSoC
***Introduction***
Zynq® UltraScale+™ MPSoC, the next generation Zynq device, is designed with the idea of using the right engine for the right task. 
The Zynq UltraScale+ MPSoC comes with versatile processing system (PS) integrated with a highly flexible and high performance PL section (which means
the PL logic cells also comes integrated with a few high speed performance peripherals.(PCI express, Interlaken, 100G Ethernet, system monitor, Video Codec Unit).
All on a single system on chip (SoC).  its PS block includes engines such as 
1. Dual core ARM Cortex A53-based Application Processing unit (APU)
2. Dual core RPU cortex R5F( Floating Point Unit extension) Real time based processing unit (RPU)
3. Dedicated PMU Platform management unit and configuration security Unit (CSU)
4. A bunch of high speed peripherals including DP and SATA.

***Development tool: Vitis, Vivado, Petalinux***
**Vivado:** Development system tool for FPGA implementation.
**Vitis:** its an unified software platform for developing embedded software for targeted embedded processor.
**Petalinux:** its a toolsets for an embedded Linux system development kit.Linux tool flow which enables complete configuration, build and deploy environment for Linux OS. So you can customize, build and deploy your own Linux OS for xilinx based devices.

**Process**
1. HW system developing usign the vivado tools along  with IP integrator those included specifying the zynq ultrascale+ PS, peripherals, interconnection of these components along with their respective detailed configuration.
2. Vitis can be used for SW development, hardware accelerator and  platform development.
***The Zynq UltraScale+ PS can be booted and run without programming the PL. However, to use any soft IP in the fabric, or to bond out PS peripherals using EMIO, you must program the PL using the Vitis IDE or the Vivado hardware manager***

