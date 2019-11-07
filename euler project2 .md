
Euler Project.2 Solution
##Amin Rezvanpour##


```python
a=[1,2]
b=[]
for i in range(1,4000000):
    if i==a[-1]+a[-2]:
        a.append(i)
for j in a:
    if j%2==0:
        b.append(j)
        sum(b)
print(sum(b))
```

    4613732
    
