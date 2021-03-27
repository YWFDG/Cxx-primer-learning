# Chapter 1
## Exercises Section 1.1
### 1.1
Visual Studio -cpp
### 1.2
```
int main()
{
    return -1; 
}
```
0xffffffff  0x代表十六进制 f(15)到二进制：1111  
0xffffffff = 1111 1111 1111 1111 1111 1111 1111 1111  
signed int -1=1000 0000 0000 0001 反码：1111 1111 1111 1110 补码：1111 1111 1111 1111   
十六位 三十二位 。。。？？？日后解决  
## Exercises Section 1.2
### 1.3
```C++
#include <iostream>

int main()
{
	std::cout << "Hello,world!" << std::endl;
}
```
### 1.4
```C++
#include <iostream>

int main()
{
	std::cout << "Enter two numbers:" << std::endl;
	int V1 = 0, V2 = 0;
	std::cin >> V1 >> V2;
	std::cout << "The sum of " << V1 << " and " << V2 << " is " << V1 * V2 << std::endl;
	return 0;
  
}
```
### 1.5
```#include <iostream>

int main()
{
	std::cout << "Enter two numbers:" << std::endl;
	int V1 = 0, V2 = 0;
	std::cin >> V1 >> V2;
	std::cout << "The sum of " << std::endl;
	std::cout <<  V1 << std::endl;
	std::cout << " and " << std::endl;
	std::cout <<  V2  << std::endl;
	std::cout << " is "<< std::endl;
	std::cout << V1 + V2 << std::endl;
	return 0;

}
```
### 1.6
```
std::cout << "The sum of " << V1; 
          << " and " << V2; 
	  << " is " << V1 + V2 << std::endl;
```
不合法 独立成句后，在输出运算符(<<)左侧没有ostream对象   
可在2、3句前添加ostream对象，或写在一句中，将输出请求连接起来   
## Exercises section 1.3
### 1.7

错误	C3872	“0x3002”: 此字符不允许在标识符中使用	1.2	c:\users\10923\source\repos\chapter1\1.2\1.2\1.2.cpp	5	
错误	C2143	语法错误: 缺少“;”(在“*”的前面)	1.2	c:\users\10923\source\repos\chapter1\1.2\1.2\1.2.cpp	6	
错误	C2143	语法错误: 缺少“;”(在“*”的前面)	1.2	c:\users\10923\source\repos\chapter1\1.2\1.2\1.2.cpp	6	
### 1.8
```std::cout << "/*";``` 合法，作为字符输出   
```std::cout << "*/";``` 合法，同上
```C++ std::cout << /*"*/"*/;``` 缺少右引号，改正为```std::cout << /*"*/"*/";// 中间的/*"*/为一对界定符```
```std::cout << /*"*/" /*"/*" */;``` 合法，输出```/*```
























