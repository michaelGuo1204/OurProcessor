# OurProcessor
搞一个CPU，运行我们自己的程序
## 1. 项目设计
本项目需求
  1. CPU的基本电路设计
  2. 基于CPU的计算机系统设计
  3. 计算机操作系统设计

实施设想
  1. 基本电路设计
      此部分在Vivado软件上进行，要求
        1. RISCV**完备**
        2. 流水线设计
      时间允许，还可设计分支预测等功能
      
  2. 计算机系统设计
      此部分及后续操作系统设计均在qemu上进行，其中HDL-VM共模拟工具参考 [该工具](https://github.com/RSPwFPGAs/qemu-hdl-cosim)
    
    
  3. 操作系统设计
      此部分依照[NJU-ProjectN](https://github.com/NJU-ProjectN)实现，参阅[NJU文档](https://nju-projectn.github.io/ics-pa-gitbook/ics2021/)
