# Format : CTF - Year - Name - points
### HeroCTF 2021 ping-pong - 45
The file name is output.txt

```
file = open('output.txt','r')
l = ''
for i in file:
    l+=i[1]
print(l)
```

Convert O in 0 and I in 1 followed by ascii convertion
> Flag : Hero{p1n6_p0n6_15_fun}