# PCA-on-PYNQ-Z2
Accelerated Principal Component Analysis on PYNQ-Z2 SoC (FPGA + ARM)

<b>HLS bit files are from https://github.com/twaclaw/matmult/blob/master/hls/matmult.h#L19</b>

### Implemented Architecture: 
<img width="458" alt="Screen Shot 2023-05-12 at 12 38 33 AM" src="https://github.com/anshulmaurya/PCA-on-PYNQ-Z2/assets/32621016/1c4074fa-08cf-4dd1-b575-cd3d2c73b34c">

### Control Table for PL block:
<img width="270" alt="Screen Shot 2023-05-12 at 12 39 49 AM" src="https://github.com/anshulmaurya/PCA-on-PYNQ-Z2/assets/32621016/5d5f3f79-9e3f-4d2f-a2c9-356cf5a9343f">

### Achieved Speedup:
<img width="409" alt="Screen Shot 2023-05-12 at 12 40 48 AM" src="https://github.com/anshulmaurya/PCA-on-PYNQ-Z2/assets/32621016/afa79e3f-6c5e-4c28-8289-76e036978080">

### Computation difference between FPGA and CPU values (Due to difference in Floating Point Precision):
<img width="457" alt="Screen Shot 2023-05-12 at 12 41 19 AM" src="https://github.com/anshulmaurya/PCA-on-PYNQ-Z2/assets/32621016/1490ff74-1102-4ed7-b5de-577aa68473c9">
