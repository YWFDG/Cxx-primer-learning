# Chapter1
## 1.1
just return 0
```
int main()
{
    return 0; 
}
```
## 1.2
提示用户输入两个数，然后输出它们的和
```
#include <iostream>

int main()
{
	std::cout << "Enter two numbers:" << std::endl;
	int V1 = 0, V2 = 0;
	std::cin >> V1 >> V2;
	std::cout << "The product of " << V1 << " and " << V2 << " is " << V1 * V2 << std::endl;
	return 0;

}
```
## 1.3
```C++
#include <iostream>
/*
*简单主函数
*读取两个数，求它们的和
*/
int main()
{
	//提示用户输入两个数
	std::cout << "Enter two numbers:" << std::endl;
	int V1 = 0, V2 = 0;      //保存我们读入的输入数据的变量
	std::cin >> V1 >> V2;    //读取输入数据
	std::cout << "The sum of " << V1<< " and " << V2 << " is " << V1 + V2 << std::endl;
	return 0;


}
```
```C++
/*
 *注释对/* */不能嵌套。
 *“不能嵌套”几个字会被认为是源码，
 *像剩余程序一样处理
 */
int main()
{
	return 0;
}
// /*
// *单行注释中的任何内容都会被忽略
// *包括嵌套的注释对也一样会被忽略
// */
```
