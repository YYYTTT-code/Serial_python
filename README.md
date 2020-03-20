# Serial_python
基于python的串口上位机

数据内容：温度、湿度、风速、风向、气压

温度：一位小数 25.3
湿度：一位小数 52.8
风速：一位小数3.2m/s
量程：0～70m/s；分辨率：0.1m/s；准确度：±(0.3+0.03V)m/s
风向：角度值250.3   西北、东南
气压：一位小数1012.3hpa百帕

数据包格式：
年 月 日 时 分 秒 温度 湿度 风速 风向  气压  共30个数字
20 04 15 17 20 15 25.3 52.8 13.2  250.3 1012.3 

功能：
数据接收、检查、处理、显示、储存、绘图

