# 更新日志
## Version1.0（2017.07.13）
1.拥有扫描目标主机端口功能，自动解析IP地址，并检测目标端口的开放状态。  
2.可以扫描内置的默认常见端口，也可以自定义需要扫描的端口。  

## Version1.1（2017.07.17）
1.增加自定义端口范围扫描功能，用于一次性扫描某范围内的所有端口。  
2.增加自定义端口扫描速率功能。

## Version2.1（2018.04.06）
1.第2版本支持Python3，并不兼容Python2，支持Python2的1号版本会继续更新。  
2.优化部分输入时的繁琐环节（如输入扫描端口范围需要添加括号，现已不需要）。  

## Version2.2（2019.05.30）
1.修复了一个导致程序偶尔无法运行的bug（似乎是编码问题）。  
2.为提高实用性和应对大范围扫描，新增了输出扫描结果功能（显示目标主机开放端口）。  
3.参考常见端口资料将默认扫描的端口数从6个提升到30个。
