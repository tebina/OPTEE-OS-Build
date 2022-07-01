# OP-TEE OS Build

Makefiles to build OPTEE OS on zynqmp platforms (tested on ZCU106) using recent petalinux versions (tested on Petalinux v2020.2) 

### Requirements : 

* Petalinux 2020.2

* Xillinx ZCU106 BSP or Xillinx ZCU102 BSP [Download](https://www.xilinx.com/support/download/index.html/content/xilinx/en/downloadNav/embedded-design-tools/2020-2.html)

### How to build :

* Copy the BSP file in the project root folder 

```
📦op-tee-os-build (root folder)
 ┣ 📂build
 ┣ 📜BSP file
 ┗ 📜README.md
 ```
 
 Quick build instuctions : 
 
* `cd build`
* `make -f toolchains.mk`
* `make -f zynqmp.mk`
