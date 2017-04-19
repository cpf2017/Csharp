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
* 其它类型：
```c
class Demo
{
  public static void Main(string[] args)
  {
    //各种整型变量举例，注意初始化值不能超过其取值范围。
    int number = 10;
    sbyte s = -3;
    short sh = 32766;
    uint ui = 15;
    long lo = 485566842;

    //浮点型变量举例
    float f = 2.523f;  //float类型的变量一定要在初始值后面加上后缀 f，否则会被认为是double类型导致等号左右两边类型不一样而报错。
    double dou = 100.25;  //double类型不需要任何后缀。

    //bool类型变量举例，注意bool类型只有两个值
    bool bo = true;

    //char类型变量举例，注意char类型的特点
    char ch = 'a';
    char c = '8';

    //字符串类型变量举例，注意字符串类型的特点
    string str = "abcdefg";
    string stri = "500";

    //可以把每一个变量的值都打印出来，在这里我们值打印两个，其余的大家自己尝试
    System.Console.WriteLine(bo);
    System.Console.WriteLine(str);
  }
}
```




