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
## Exercise Section 1.2
### 1.3
```
#include <iostream>

int main()
{
	std::cout << "Hello,world!" << std::endl;
}
```
### 1.4
```
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

























