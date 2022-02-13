- [Variable](#variable)
- [Arthmetic operation](#arthmetic-operation)
- [List](#list)
- [Tuples](#tuples)
  - [Tuple to list convert](#tuple-to-list-convert)
- [Dictionaries](#dictionaries)

```python
#jupyter nbconvert --to markdown Practice.ipynb --output README.md

```

```python
# sting

s="hello world"
print(s)
print(type(s))
```

    hello world
    <class 'str'>

## multiple string

```python

# Using triple quotes
ms="""My name is jhon.
I am the owner of dev.com
Dev is very popular website in Developers community."""

print(ms)
#using Braket
ms=("my name is jhon"
"I am the owner of dev.com"
"Dev is very popular website in Developers community.")
print(ms)
#using backslash
ms="My name is jhon." \
"I am the owner of dev.com" \
"Dev is very popular website in Developers community."
print(ms)
```

    My name is jhon.
    I am the owner of dev.com
    Dev is very popular website in Developers community.
    my name is jhonI am the owner of dev.comDev is very popular website in Developers community.
    My name is jhon.I am the owner of dev.comDev is very popular website in Developers community.

## String concatention

### String Concatenation using + Operator

```python
s1='Apple'
s2='Banana'
s3='Orange'
s4=s1+s2+s3
print(s4)
# However,the arguments must be a string.
#Let's try to concatenate a string to integer:
print('Hello' +"" + str(2))
```

    AppleBananaOrange
    Hello2

```python
str2="Hello bappy"
print("%s is to stirng" %(str2)) # %s to stirng
print(type(str2))
int1=5555
print("%s is to Integer" %(int1)) # %s to INt
print(type(int1))
print('this is the print statement 1' ,end="")
print('this is the print statement 2')
print("hello \n"*20)
```

    Hello bappy is to stirng
    <class 'str'>
    5555 is to Integer
    <class 'int'>
    this is the print statement 1this is the print statement 2
    hello
    hello
    hello
    hello
    hello
    hello
    hello
    hello
    hello
    hello
    hello
    hello
    hello
    hello
    hello
    hello
    hello
    hello
    hello
    hello

## String Function

```python
Str="this is Borhan Uddin"
print(Str.capitalize())
print(Str.upper())
print(Str.lower())
#First word capitilize
print(Str.find("Borhan"))
print(Str.replace("Borhan Uddin","Borhan Uddin Bappy").capitalize())
```

    This is borhan uddin
    THIS IS BORHAN UDDIN
    this is borhan uddin
    8
    This is borhan uddin bappy

# Variable

```python
First_name = "Borhan Uddin"
Last_name =" Bappy "
full_name = First_name + Last_name
print( "hello "+ full_name)
```

    hello Borhan Uddin Bappy

# Arthmetic operation

```python
print("3 + 5 =",3+5)
print("3 * 5 =)",3*5 )
print("3 / 5 =",3/5)
print("3 // 5 =",3//5)
print("3 % 5 =",3%5)
print("This is a \" ")
```

    3 + 5 = 8
    3 * 5 =) 15
    3 / 5 = 0.6
    3 // 5 = 0
    3 % 5 = 3
    This is a "

# List

```python
University=['green university','daffodill university','dhaka university','jahangirnagor university','AIUB']
print(University[0])
University.append('Brack University')
print(University)
University.insert(1,'Daffodill University')
University.insert(2,'Dhaka University')
University[3]='Jahangirnagor University'
print(University)
University[3]='Jaganth University'
University.remove('jahangirnagor university')
print(University)
for uni in range(len(University)):
    if University[uni]=='green university':
       University[uni]='Green university'
    if University[uni]=='dhaka university':
        University[uni]='Dhaka University'
print(University)
print(University.index('AIUB'))
print(University.count('Dhaka University'))
University.remove('Dhaka University')
print(University.count('Dhaka University'))
print(University.pop(1))
print(University)
University.insert(1,'Daffodill University')
print(University)
univer=(University + ['NSU','MBSTU','NSTU'])
print(univer)
print(len(University))
print(len(univer))
print(max(University))
print(min(University))
```

    green university
    ['green university', 'daffodill university', 'dhaka university', 'jahangirnagor university', 'AIUB', 'Brack University']
    ['green university', 'Daffodill University', 'Dhaka University', 'Jahangirnagor University', 'dhaka university', 'jahangirnagor university', 'AIUB', 'Brack University']
    ['green university', 'Daffodill University', 'Dhaka University', 'Jaganth University', 'dhaka university', 'AIUB', 'Brack University']
    ['Green university', 'Daffodill University', 'Dhaka University', 'Jaganth University', 'Dhaka University', 'AIUB', 'Brack University']
    5
    2
    1
    Daffodill University
    ['Green university', 'Jaganth University', 'Dhaka University', 'AIUB', 'Brack University']
    ['Green university', 'Daffodill University', 'Jaganth University', 'Dhaka University', 'AIUB', 'Brack University']
    ['Green university', 'Daffodill University', 'Jaganth University', 'Dhaka University', 'AIUB', 'Brack University', 'NSU', 'MBSTU', 'NSTU']
    6
    9
    Jaganth University
    AIUB

# Tuples

```python
#tuple element does not change
tup1=(1,2,4)
print(tup1[2])

```

    4

## Tuple to list convert

```python
tup1=(2,4,5,6,22)
list1=list(tup1)
print(list1)

```

    [2, 4, 5, 6, 22]

# Dictionaries

```python
names={'Borhan':24,
'sharukh':22,
'Shoab':20,
'Ariful':18}
print(names['Shoab'])
names['Ariful']=21
print(names['Ariful'])
print(names.keys())

```

    20
    21
    dict_keys(['Borhan', 'sharukh', 'Shoab', 'Ariful'])
