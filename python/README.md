# sting


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
print('Hello'  +str(2))
```

    AppleBananaOrange
    Hello2
    


```python

```
