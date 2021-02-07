# Crisps

You can eat and get fat. Just by 1 line of 
code you can start your profile and start to eat crisps. More fat more powerfull!!

## Installation

The pip code for installing Crisps:

```
pip install crisps
```

## How to use Crisps?

In version 0.0.2 you have to write this code for your profile:

```python
profilename = crisps.new("Your Name", "Your kilogram", "Your height") 
```
***DON'T PLACE DOTS IN Height***

### Printing Your Info:

You just need to print like this

```python
print(profilename.name) #You can replace the name with kilogram/height
```

### Eating food
 
For eat food you have to name your profile name ***app*** or it wont work!

```python
import crisps

app = crisps.new("Explame", 45, 156)
app.eat(45)
print(app.kilogram)
```
You will get 90 kilogram because 45 + 45 = 90. That Easy!

### Doctor Control ?

Yeah it's a strange idea but i made that. In order to go doctor we will use app as the profile name again same as eating.

```python
#same code as eating
app.doctor()
```

So after we eating all the crisps we are 90 kilogram so we are fat. The math for it is : "height - 100 if kilogram > height : fat else normal"
