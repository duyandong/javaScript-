# javaScript概述

## 程序语言

* 基础逻辑处理部分
 * 变量 数据类型  (数据存储)
 * 分支和循环   运算符	  (逻辑操作)
 * 函数（对语言的拓展）
 ```javascript
 var vr = 1;          // Number
 var vr = 1.2;        //Number
 var vr = '11';        //String
 var vr = false;       //boolean
 var vr = [1,2,3];    //Array
 var vr = {a:1,b:2}   //cbject
 var vr = fuction(){} //Function
 var vr = undefined
 var vr = Null

###  运算符
 + - * / %
 === != > < <= >= 
 && || !
 ###分支语句
 if()
 if()else
 if()else if()else if()

   
    
switch(){
	case 1：
	break;
	case 1;
	break;
	default;
	break;
}
### 循环语句
for(var i=0;i<5;i++){
     console.log(i); 
   }


   while{
     
   }


   do{

   }while()
### 函数
function xx (){
	
}
var fn =funxtion( x1,x2){
		//arguments
	
}
fn(a,b)

//  函数的常用方法
//  字符串中的常用方法
//  函数对象中的方法    bind apply call
//	对象的增删改查  原型链
//  数字对象身上的方法  toFixed
//  Math对象身上的方法

 functionA(c){
 	this.X=c;
}
var obj = new A(1);
 ```
## 针对特定用途的部分
  >当js来浏览器运行的那一刻
  >浏览器会创建一个window对象
  >Window对象中很多属性和方法
  >这些属性和方法不用加window.就可以使用
  dom对象   dom集合

  
###  选取元素
* var el=documnet.getElementsByClassName()
* var el=documnet.getElementsByTagName()
* var el=documnet.getElementById()
* var el=documnet.getElementsByName()  
###  筛选元素
*
*

###  样式操作
* innerHTML 
* el.style.color
###  获取位置信息

###  操作属性
*
*
*
*
###  节点操作
###  获取元素信息