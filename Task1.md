```python
# Task1 

# inputs
G = float(input(" Enter gravity = "))
ME = float(input('Enter mass of Earth = '))
MM = float(input('Enter mass of Moon = '))
r = float(input('Enter radius = '))

G = G*(10**-11)
ME = MM*(10**24)
MM = MM*(10**22)
r = r*(10**8)

# Mathematical equation
Fg = G * ME * MM / (r**2)

# Displaying result
print ("Gravititional Force = {} Newton ".format(Fg))
```

     Enter gravity = 8
    Enter mass of Earth = 4.7
    Enter mass of Moon = 7.44
    Enter radius = 3.56
    Gravititional Force = 3.494104279762656e+20 Newton 
    


```python

```
