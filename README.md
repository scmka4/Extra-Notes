# Extra-Notes

input
1.运行次数（1一次/2无限次） 2.动作（1重新输入/2退出）

无限运行通用代码；
while(scanf()==..){
  while（不在范围里的条件）
    重新输入数据；
  if（退出循环的特殊条件）
    break；
}


1.2+2.1
一次运行重新输入
scanf（）；
while(不在范围里面的条件)
  重新输入数据；
or
while（scanf（）&&。。。）
  break；
  
1.2+2.1
scanf（）；
while(退出循环条件)
  while（不在范围里的条件）
    重新输入数据；
  其他代码；

1.2+2.2
while（scanf（）==//校验所输入的数据类型）
  if（退出循环的条件）
    break；

