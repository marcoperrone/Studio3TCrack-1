## Studio3TCrack

English | [中文](https://github.com/linG5821/Studio3TCrack/blob/master/README.zh-CN.md)

#### Studio 3T

  Studio 3T is a powerful MongoDB database management tool that provides GUI visualization operations. It can completely let you say goodbye to the command line. The software provides the applicable version for a period of 30 days!

#### Studio3TCrack Introduce

  First of all, I would like to express my apology. This project bypasses the license test, which means Studio 3T can be used indefinitely.However, ***Pro*** and ***Enterprise*** functionality has not been modified，This program is for study and communication only,If necessary, please purchase the legitimate [Studio 3T](https://studio3t.com)

#### Other introduced

 Similarly, windows64 is also available with a.exe executable that you can Clone from this repository to get what you need.The build use [exe4j](https://www.ej-technologies.com/), which you can get from the website and build your own 32-bit executable if you need to.

#### How to Use?


##### package replace:
  1. backup data-man-mongodb-ent-2019.3.0.jar package

  2. Copy the data-man-mongodb-ent-2019.3.0.jar from the project to the installation directory and replace the original package

  3. Run the official binary executable

  ps: Mac Appear damaged
  Security and privacy->Open any source
  No hava any source  terminal execute ```sudo spctl --master-disable```

##### command mode:

  1. Attention!!!Attention!!!Now you can easily skip validation without using any jar packages and just run the command

  2. Copy a file path named data-man-mongodb-xxxxx.jar from Studio3T installation directory.。

  3. Execute in any directory java -cp path(The path copied above must be absolute) t3.dataman.mongodb.app.ad

  4. Mac
    java -XstartOnFirstThread -cp path(The path copied above must be absolute) t3.dataman.mongodb.app.ad

   ```bash
   # ! /bin/bash
   nohup java -cp path(The path copied above must be absolute) t3.dataman.mongodb.app.ad >/dev/null 2>&1 &
   ```
#### Version Update
    2019.7.26: 1. The data-man-mongodb package that can be directly replaced can be directly copied to the installation directory for replacement, and then the official binary                executable file can be directly provided. This package version 2019.3.0
               2. Problem: custom Settings cannot be saved, but connection information can be saved
               3. You can use the functions of enterprise edition on windows: click help->license manager to input the anything and then click ok to use the functions of enterprise edition
    2019.6.27: Update starts as a script command, removing code-level control
    studio-3t-start-2019.2.1:Updated the code implementation, using new ideas to adapt to the new version of Studio 3T version 2019.2.1
    Usage: Same as before,No spaces in the path, special characters
    Build: This time directly packaged executable jar files contain all dependency packages that can be used directly. Check release

#### Photo Guide



![image1](./images/1.png)

![image2](./images/2.png)

![image3](./images/3.png)

![image4](./images/4.png)