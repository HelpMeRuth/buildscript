# buildscript
* Place all the files in your kernel directory 
(use this kernel: https://github.com/cyanogenmod/android_kernel_motorola_msm8916)
* open terminal and type: "sudo ./build.sh"
* you will be prompted to place your toolchain in the created folder "Toolchain" above the kerneldir
* place your toolchain in it
* relaunch ./build.sh and all should go well
* final zip goes in Builds directory again above the kerneldir
* make sure you have setup your build environment correctly (Only works for 64 bit if you build for osprey)
* script uses anykernel
