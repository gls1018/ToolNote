

## 1. 如何缩放和居中图片

<img src="./assets/image-20260623045530984.png" alt="image-20260623045530984" style="zoom:80%;" />



上面是一张图片, 用Typora来写的话是\<img src="./assets/image-20260623045530984.png" alt="image-20260623045530984" style="zoom:80%;"/>



- Github中不支持 style = "zoom:80%"这样的语法.
- 直接删掉alt, 删掉style
- 添加 width = "50%"   表示按照原图片的50%来显示.



如何居中图片? 

将图片的链接放到\<p align="center"> \</p> 中即可



<p align="center"><img src="./assets/image-20260623045530984.png" width="50%" /> </p>



## 2. 如何正确显示 LaTex公式

- 使用行内公式注意前后空格 space \$ $ space



## 3. 如何使用图床





## 4. 如何正确显示上标和下标



- Github中Markdown 不支持 H\~2~o 这样的双引号来显示下标 H~2~o
- 显示下标只有两种方法
  - 使用LaTex, \$H_2O$表示  $H_2O$
  - 使用\<sub>  \</sub>标签



