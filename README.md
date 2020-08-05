# 2020_Xilinx_Summer_School_Project
2020年新工科联盟-Xilinx暑期学校（Summer School）项目。
## 项目名称：
基于FPGA的CRC检验算法及AES加解密算法<br> 
## 项目简介：
CRC校验算法：能通过输入任意16位数据，并行输出其在CRC16/USB或CRC16-CCITT/FALSE的参数模型下的CRC校验码。<br> 
AES加解密算法：加解密的密钥长128bits，数据块固定128bits，以32bits为一个字长进行分组后实现加解密。<br> 
## 项目功能：
CRC校验算法可应用在信息通信过程中来判断信息传输是否发生错误，发送端将要发送的k位二进制码序列与规定的生成多项式作模2除法，生成r位的CRC校验码，构成一个新的k+r位的二进制码序列发送，接收端再将该序列与给定的生成多项式相除，通过判断余数是否为0，判断传输过程中数据是否产生差错。<br> 
AES加解密算法是最常见的对称加密算法，是美国联邦政府采用的区块加密标准，AES标准用来替代原先的DES，已经被多方分析且广为全世界所使用。加密方与解密方采用相同的128位密钥，完成数据的加密与解密，可以应用于保密系统中。
## 项目成员：
章程<br> 
李润发<br> 
## 项目软硬件工具：
### 软件
Vivado 2018.3<br> 
Arduino 1.8.13<br> 
CRC在线计算器<br> 
AES在线加解密计算器<br> 
### 硬件
SpartanEdge Accelerator Board<br> 
FPGA星号：xc7s15ftgb196<br> 
