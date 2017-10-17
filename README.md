# phy_addr
get_phy_addr : 网上抄过来的测试程序, 功能为 显示一个变量 :0x12345678 的虚拟地址和物理地址.
                  
实现原理, 打开该程序的/proc/pid/pagemap......待续


pid-va2phy : 通过虚拟地址和pid号计算物理地址.供其他进程调用获取.
