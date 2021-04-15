## Publications

## 二级

### 三级

#### 四级

test gitee :100:
test gitee :100:

> An awesome project.

行内公式 $\frac{1}{2}$
$$
\begin{aligned}
f(x) f(\pmb{x}) \pmb{X} \boldsymbol{x} 
\end{aligned}\tag{1}
\\\\ 
$$

#### 😁

```java
printf("hello world!");
int main(void )
Vector<String>
```

```cpp
for 
vector<>
    int main
    float
    double
	printf()
```

```matlab
function HelloWorld()

%输出Hello，World！

%   Detailed explanation goes here

disp('Hello,World!');

end
```

```python
#!/usr/bin/python
# -*- coding: UTF-8 -*-
 
# 定义函数
def printme( str ):
   "打印任何传入的字符串"
   print str
   return
 
dict = {'Name': 'Zara', 'Age': 7, 'Class': 'First'}
 
print "dict['Name']: ", dict['Name']
print "dict['Age']: ", dict['Age']
```

**粗**

*斜*

<font  color="red">This is some text!</font>

!> a

- 啊

  - [是](#四级)

<table>
	<tr >
	    <td  colspan="3">事务1</td>
	    <td  colspan="3">事务2</td>
	</tr>
	<tr >
	    <td  colspan="3">begin;</td>
	    <td  colspan="3">begin;</td>
	</tr>
    <tr >
	    <td  colspan="3">set session transaction isolation level READ COMMITTED;//修改隔离级别</td>
	    <td  colspan="3">set session transaction isolation level READ COMMITTED;//修改隔离级别</td>
	</tr>
	<tr >
	    <td colspan="3">select * from t_isolation_level where id = 99;</td>
	    <td rowspan="3" colspan="3"></td>
	</tr>
	<tr>
	    <td>id</th>
	    <td>name</th>
	    <td>class_id</th>  
	</tr>
	<tr>
	    <td>1</th>
	    <td>范统</th>
	    <td>99</th>  
	</tr>
<tr>
	    <td rowspan="2" colspan="3"></th> 
	    <td  colspan="3">insert into t_isolation_level VALUES(2,'菜镶',99);</th>  
	</tr>
	<tr >
	<td colspan="3">commit;</th>  
	</tr>
	<tr >
	    <td colspan="3">select * from t_isolation_level where id = 99;</td>
	    <td rowspan="4" colspan="3"></td>
	</tr>
	<tr>
	    <td>id</th>
	    <td>name</th>
	    <td>class_id</th>  
	</tr>
	<tr>
	    <td>1</th>
	    <td>范统</th>
	    <td>99</th> 
	    	<tr>
	    <td>2</th>
	    <td>菜镶</th>
	    <td>99</th>  
	    </tr>
	  <td colspan="3">commit;</th>  
	   <td rowspan="5" colspan="3"></td>
</table>
::warning::

::ss::