> 用双引号括起来的0个或多个字符就是一个字符串字面量  
> 例如：  
> `"hello"`  
> `"1"`  
> `""`  
> 
> ---
> 字符串变量：  
> String s；  
> String 是一个类，String 的变量是对象的管理者而非所有者  
> 就像数组变量是数组的管理者而非所有者一样  
> 
> ***
> `String s = new String("a string");`  
> 创建了一个String的对象  
> 用“a string”初始化这个对象  
> 创建管理这个对象的变量s  
> 让s管理这个对象  
> 
> - - -
> 初始化字符串变量  
> `String s = "hello";`  
> 编译器帮你创建一个String类的对象交给s来管理  
> 
> * * *
> 字符串连接  
> 用加号（+）可以连接两个字符串  
> `"hello"+"world"` -> `"helloworld"`  
> 当这个+的一边是字符串而另一边不是时，会将另一边表达为字符串然后做连接  
> `"I'm "+18` -> `I'm 18`  
> `1+2+"age"` -> `3age`  
> `"age"+1+2` -> `"age12"`  
> 
> ---
> ``` java
> String s = new String("Hello");		// 有字符串的管理者s，也有字符串的对象
> System.out.println(s);
> System.out.println(s+" world");
> System.out.println(s+12);
> System.out.println(s+12+24);
> System.out.println(s+(12+24));
> ```
> 
> ---
> 输入字符串  
> `in.next();`读入一个单词，单词的标志是空格  
> 空格包括空格、tab和换行  
> `in.nextLine();`读入一整行  
> 
> * * *
> ``` java
> import java.util.Scanner;
> 
> public class Demo47 {
> ```