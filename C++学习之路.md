## C++学习之路

一、

*1.编译型语言和解释型语言*

![image-20230604153654217](C:\Users\范少杰1\AppData\Roaming\Typora\typora-user-images\image-20230604153654217.png)

一次性翻译和一句一句翻译的区别，一次性翻译执行的效率高



*2.代码的运行*

![image-20230604153416157](C:\Users\范少杰1\AppData\Roaming\Typora\typora-user-images\image-20230604153416157.png)

源代码经编译器（一次性）转化为目标代码，将库文件中的代码链接到目标代码形成可执行代码



*3.数据类型的本质*

告诉计算机数据占用多大的空间

4.模板类vector简介

![image-20230607174900542](C:\Users\范少杰1\AppData\Roaming\Typora\typora-user-images\image-20230607174900542.png)

![image-20230607174948869](C:\Users\范少杰1\AppData\Roaming\Typora\typora-user-images\image-20230607174948869.png)

![image-20230607175005015](C:\Users\范少杰1\AppData\Roaming\Typora\typora-user-images\image-20230607175005015.png)

5.指针

​	一种特殊的数据类型，“指向”另一种数据类型的复合类型。存放另一个数据对象在内存中的“地址”。

![image-20230729180102619](C:\Users\范少杰1\AppData\Roaming\Typora\typora-user-images\image-20230729180102619.png)

​	内存中的显示：

![image-20230729183203720](C:\Users\范少杰1\AppData\Roaming\Typora\typora-user-images\image-20230729183203720.png)

​	![image-20230729194239399](C:\Users\范少杰1\AppData\Roaming\Typora\typora-user-images\image-20230729194239399.png)

![image-20230729194247157](C:\Users\范少杰1\AppData\Roaming\Typora\typora-user-images\image-20230729194247157.png)

​	通过指针访问对象：解引用操作符（*）

![image-20230729195013233](C:\Users\范少杰1\AppData\Roaming\Typora\typora-user-images\image-20230729195013233.png)

​	野指针和空指针的区别： 野指针未初始化，具有随机性，危险

​											空指针不指向任何的数据对象，指向特定的0地址（有系统决定），											安全

​	void* 指针：只能进行地址的存放和比较，不能进行数据的访问。即不能进行解引用操作。



​	指向常量的指针和指针常量的区别：指向常量的指针本身是变量，但是不能修改指向的内存的															数据，指针常量本身是常量，只能指向一块固定的内存。



​	指针和数组： 数组名本身就是一个指针。指向第一个数组元素。

![image-20230731174917416](C:\Users\范少杰1\AppData\Roaming\Typora\typora-user-images\image-20230731174917416.png)

![image-20230731175005490](C:\Users\范少杰1\AppData\Roaming\Typora\typora-user-images\image-20230731175005490.png)

​	指针数组和数组指针：

![image-20230731183024879](C:\Users\范少杰1\AppData\Roaming\Typora\typora-user-images\image-20230731183024879.png)



 引用：本质是别名，不为其分配内存。







