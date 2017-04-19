# 常量与变量
# 变量的定义
* 什么是变量，变量就是内存中的一块存储区域，可以不断的存储同一类型的变化的数据。
* 如何定义变量，格式：数据类型 变量名 = 初始化值
* **举例：**
```c
class Demo
{
  public static void Main(string[] args)
  {
    //定义一个int类型的变量。请问改变量在内存中占用多少字节？
    int number = 10;
    //定义变量后我们可以使用这个变量，打印它，结果为10.
    System.Console.WriteLine(number);
    }
}
```
* 其中，int为数据类型，number为我们自定义的变量名，10则是这个变量的初始化值。那么如何变呢？
```c
class Demo
{
  public static void Main(string[] args)
  {
  //定义一个int类型的变量。
  int number = 10;
  //使变量改变数值。这样也可以叫做使用这个变量给它重新赋值。
  number = 20;
  //定义变量后我们可以使用这个变量，打印他，结果为20.
  System.Console.WiteLine(number);
   }
}
```

