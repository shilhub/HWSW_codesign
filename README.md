# HWSW_codesign
Accelerating VGG16 DCNN with an FPGA

FPGA-based acceleration of the VGG16 model implemented through a combination of the PyTorch frontend in Python, connected to a
custom layer implemented in C++ and Xilinx/AWS F1 FPGAs. Optimizations (im2col-col2im, block matrix multiplication and addition
in kernel, event scheduling, multiple compute units) led to an acceleration of 160x.
