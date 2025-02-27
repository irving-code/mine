### Java基本语法

* **main方法** 相当于c中的int main

  ~~~java
  public static void main(String[] args){
      
  } 
  ~~~

* **输出语句**

  ~~~java
  System.out.println("HelloWorld");
  ~~~

  * 去掉ln就不会换行了

* **注释**  与c语言一样（多了个文档注释）【待补充】

* **关键字**

  * class用于创建/定义一个类 后面跟随类名

* **字面量（类似于常量）**

![image-20250121191107427](C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20250121191107427.png)

补充：\t 制表符：将前面字符串的长度补齐到8、

* **变量**/

  * 与c一致

  * 不初始换变量在c中会取字母c的存储值，java中会报错

  * ![image-20250121213149205](C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20250121213149205.png)	

  * *需要加后缀的变量*

    * 定义long类型的变量
      * 在数据值加L为后缀（最好是大写）		

    * 定义float类型变量
      * 数据值后加F为后缀

  * 其余变量不需要加后缀

  * 取值范围只需要记忆byte即可

  * 取值范围大小 *double>float>long>int>short>byte*

  * boolean（布尔类型）定义的变量数据只有true和flase两种

    

* **进制**

  * 二进制 以0b开头
  * 十进制
  * 八进制  以0开头
  * 十六进制  以0x开头

* **命名**

  * ![image-20250122173448559](C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20250122173448559.png)

    ![image-20250122173516019](C:\Users\Lenovo\AppData\Roaming\Typora\typora-user-images\image-20250122173516019.png)

####