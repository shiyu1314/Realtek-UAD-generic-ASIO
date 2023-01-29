# Realtek-UAD-generic-ASIO

禁用驱动签名命令
 
 bcdedit -set loadoptions DISABLE_INTEGRITY_CHECKS
 
 bcdedit -set TESTSIGNING ON
 
 退出测试模式
 
 bcdedit -set TESTSIGNING off
