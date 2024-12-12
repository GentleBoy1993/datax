# datax
 datax在配置clickhouse导数是报错(可以配置clickhouse数据源)
 
 WARN  ConfigParser - 插件[clickhousereader,clickhousewriter]加载失败，1s后重试... Exception:Code:[Framework-12], Description:[DataX插件初始化错误, 该问题通常是由于DataX安装错误引起，请联系您的运维解决 .].  - 插件加载失败，未完成指定插件加载:[clickhousewriter, clickhousereader] 
 
 原因是datax3.0没有clickhouse组件,需要自己把组件放到相应位置(/opt/datax/datax/plugin/reader,/opt/datax/datax/plugin/writer)
 ![image](https://github.com/user-attachments/assets/6393a717-4712-47f6-be1e-504418c7416f)
![image](https://github.com/user-attachments/assets/334d939d-aa4e-4eb6-bc18-16c3d69d4451)
![image](https://github.com/user-attachments/assets/cffaa7c2-aa21-4d52-9ef3-04adf2caacf7)
