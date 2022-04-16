
# 基础语法
1. 变量命名规则
* 构成：字母，数字，下划线
* 非关键字，非空格
```python
>>> var="Python程序设计"
>>> print(var)
Python程序设计
>>> 
>>> a=3
>>> b=5
>>> print(a+b)
8
```

2. 数据类型
* int
* float
* str
* bool
```python
type(123)
type(3.14)
type("abc")
type(False)
print(4+6,'4'+'6')
```

3. 字符串
* 单引号/双引号
* 转义字符
```python
s1="arya's a little girl"
s2='arya\'s a little girl'
s3='arya \
is a little girl'
s4='arya\nis a little girl'
s5='arya\t is a little girl'
s6="""arya
is a little girl"""
```
* 长度/切片  
string[start:end:steps] --> [start,end)
```python
s='0123456789'
print(len(s))

print( s[3] )  # start from index=0
print( s[3:5] )  # end not be contain
print( s[3:9:3] )
print( s[:3] ) # [0,3)
print( s[6:] ) # [6,len)

ss="Python非常有趣"
print( ss[:6] )
print( ss[6:] )
```
*   

4. 运算符
* 算术运算符
* 赋值运算符
* 比较/关系运算符
* 逻辑运算符
* 类型转换
```python
print( 2+3 , 2-3 , 2*3 , 2/3 , 2%3 , 2//3 )
print( 2**3 )

a=4
b=a

b+=a
b*=a

b == a
b != a 

print( '3'+'4' , int('3')+int('4') , float('3')+float ('4')  )

a='圆周率='
b='3.14'
print( a+str(b) )
print( a+repr(b) )

```

5. 输入与输出

```python
print("圆周率是{}嘛？".format(3.14))

p=input("请输入: ")
print('',p)

```




