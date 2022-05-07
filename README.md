# LAB#D Accelerated Algorithmic Trading Demo

## Build
<code> 
&emsp; cd AAT_demo/build/  

&emsp; ./buildall.sh
</code><br><br>

## Run Host Program
<code> 
&emsp; ./run.sh
</code><br><br>

## If you cannot run *.sh
<code> 
&emsp; chmod u+x buildall.sh (or run.sh)
</code><br><br>

## You have to reset the FPGA before running Host program
<code> 
&emsp; xbutil reset --device
</code><br><br>

## Reference
https://xilinx.github.io/XRT/2021.2/html/xrt_native_apis.html
https://github.com/Xilinx/Vitis_Accel_Examples/tree/master/host_xrt/streaming_free_running_k2k_xrt
