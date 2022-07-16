# 一.static

### 1.static修饰成员变量

* 静态成员变量：有static修饰，属于类，只加载一次，可以被共享访问；访问格式：**类名.静态成员变量**
* 实例成员变量：无static修饰，属于对象；访问格式：**对象.实例成员变量**

### 2.static修饰方法

* 静态成员方法：有static修饰， 属于类，建议用类名访问，也可以用对象访问
* 实例成员方法：无static修饰，属于对象，只能用对象访问

注意：同一个类中，访问静态方法，类名可以不写

### 3.内存机制

![1657873357277](C:\Users\jwk\AppData\Local\Temp\1657873357277.png)

### 4.注意事项

![1657873420383](C:\Users\jwk\AppData\Local\Temp\1657873420383.png)

![1657874420357](C:\Users\jwk\AppData\Local\Temp\1657874420357.png)



### 5.代码块

* 静态代码块：有static修饰，属于类，与类一起优先加载一次，自动触发执行；静态代码块可以用于**初始化静态资源**。

![1657874823585](C:\Users\jwk\AppData\Local\Temp\1657874823585.png)

### 6.饿汉单例与懒汉单例

* 饿汉单例

![1657876809284](C:\Users\jwk\AppData\Local\Temp\1657876809284.png)

![1657877298857](C:\Users\jwk\AppData\Local\Temp\1657877298857.png)

* 懒汉单例

![1657876754669](C:\Users\jwk\AppData\Local\Temp\1657876754669.png)

![1657877272852](C:\Users\jwk\AppData\Local\Temp\1657877272852.png)