Cycle "for" - function "range".
===============================
for, if, range
--------------
````````````ruby
m = int(input())
n = int(input())

if m % 2 != 0:
    for i in range(m, n-1, -2):
        print(i)
if m % 2 == 0:
    for i in range(m-1, n-1, -2):
        print(i)
`````````````````````
````````````ruby
m = int(input())
n = int(input())
for i in range(m, n+1):
    if i % 10 == 9:
        print(i)
    if i % 17 == 0:
        print(i)
    if i % 3 == 0 and i % 5 == 0:
        print(i)
`````````````````
        
