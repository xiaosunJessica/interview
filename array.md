<!--
 * @Author: your name
 * @Date: 2018-08-10 15:13:32
 * @LastEditTime: 2020-10-16 15:34:54
 * @LastEditors: Please set LastEditors
 * @Description: In User Settings Edit
 * @FilePath: /summary/array.md
-->
# 数组

## 判断数组
Array.isArray用于确定是否时一个数组   

## 增加  
push添加到末尾  
unshift在开头添加元素


## 删除
pop删除最后一个  
shift删除第一个元素

## 创建和修改
Array.from从一个类似数组或可迭代对象中创建数组实例  Array.from('foo');  // ["f", "o", "o"]    
concat用于合并两个或多个数组。不修改现有数组，返回新数组  
reverse将数组元素位置颠倒  
sort排序，默认按照unicode升序  
slice选择一部分浅拷贝为一个新数组，原数组不变  
splice通过删除或添加元素来更改数组内容    

### 遍历数组
filter返回所提供函数实现测试的所有元素    
forEach方法对数组的每个元素执行一次提供的函数    
map该数组中每个元素都调用该方法并返回结果  
reduce对累加器和数组中每个元素应用一个函数(从左到右)  
reduceRight对累加器和数组中每个元素应用一个函数(从右到左)  


## 查找
every是否所有都通过制定函数的测试   
some测试数组中某些元素是否通过测试    
includes判断一个数组是否包含指定的值，包含返回true, 否则返回false   
indexOf返回数组中可以找到一个指定元素的第一个索引；如果不存在，返回-1    
indexOf返回数组中可以找到一个指定元素的最后一个索引；如果不存在，返回-1   

find返回数组中满足提供测试函数的第一个元素的值，否则返回undefined    
findIndex方法返回数组中提供测试函数的第一个元素的索引， 否则返回-1     

## arrayToString
join将数组的所有元素连接成一个字符串并返回该字符串    
toString返回一个字符串  


