### 1. Write a Car class with the following attributes:

    name
    color
    price
    tank size

### 2. Create a Car instance with the following information:

    Car name - Porsche Carrera 911
    Car color - green
    Car price - 50000
    Tank size - 65

Let the numbers price and tank size be in integer format.

### 3. Write a `__repr__` method such that the output is as follows:

```python 
>>> porsche 
>>> Car Porsche Carrera | Color green | Price: 50000€ | Tank size: 65l 
```

### 4. Suppose you have a list of cars which represents the cars available at the dealership. 

### Create a function `total_price` which takes a list of cars as an argument and it returns the total price of all cars available at the dealership.

Cars needed:

| Name                     | Color | Price  | Tank size |
|--------------------------|-------|--------|-----------|
| Porsche Carrera 911      | Green | 50000  | 65        |
| Bugatti Chiron           | Blue  | 300000 | 100       |
| Ferrari F8 Tributo       | Red   | 280000 | 78        |
| Skoda Octavia            | Turqoise | 25000  | 50     |

Example:

```python 
>>> total_price(cars)
>>> 655000
```

### 5. Create a function `most_expensive` which takes a list of cars as an argument and it prints the name and the price of the most expensive car from the list.

Example:
```python 
>>> most_expensive(cars)
>>> The most expensive is: Bugatti Chiron, 300000€.
```

### 6. Create a function `create_cars_dico` which takes a list of cars as an argument and it returns a dictionary in which car names are keys and values are tuples of other car attributes 

Example:
```python 
>>> create_cars_dico(cars)
>>> {'Porsche Carrera 911': ('green', 50000, 65), 'Bugatti Chiron': ('blue', 300000, 100), 'Ferrari F8 Tributo': ('red', 280000, 78), 'Skoda Octavia': ('turqoise', 25000, 50)}
```

### 7. What is the command to print the tank size of Skoda Octavia using the cars_dico dictionary?