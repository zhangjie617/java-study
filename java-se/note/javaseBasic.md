#JAVA基础语法

##第一个JAVA程序

HelloWorld.java：

```java
public class HelloWorld{
  public static void main(String[] args){
    System.out.println("Hello world!");
  }
}
```

##数组

数组是带索引的数据项集合，通过索引来读取数据项。

示例：

```java

//定义与遍历
int[] arr = {1,2,3,4,5};

for(int i=0; i<arr.length; i++){
  System.out.printf(arr[i]);
}

//其它定义形式
//int[] arr = int[] {1,2,3,4,5};
//int[] arr = new int[] {1,2,3,4,5};
//int[] arr = int[5] {1,2,3,4,5};
//int[] arr = new int[5] {1,2,3,4,5};

```