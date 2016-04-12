# Cape Town taxis

Here's the data we have for Cape Town.

```javascript
var capeTownTaxis = [
  {
    "RegistrationNumber": "CA 123 456",
    "Route": "Cape Town - Bellville",
    "Fare": 13,
    "Trips": 9
  },
  {
    "RegistrationNumber": "CA 234 567",
    "Route": "Cape Town - Gugulethu",
    "Fare": 12,
    "Trips": 11
  },
  {
    "RegistrationNumber": "CA 123 456",
    "Route": "Cape Town - Gugulethu",
    "Fare": 12,
    "Trips": 11
  },
  {
    "RegistrationNumber": "CA 345 678",
    "Route": "Cape Town - Langa",
    "Fare": 8,
    "Trips": 13
  },
  {
    "RegistrationNumber": "CA 345 678",
    "Route": "Cape Town - Cape Town",
    "Fare": 13,
    "Trips": 10
  }
];
```

## What, *how* much?

Now let's use TDD to write code that answers these questions.

### Find the total of one attribute in a list of objects

How many trips did all the taxis make?

### Find the minimum of one attribute in a list of objects

What's the lowest number of trips that any taxi in Cape Town made?

### Find all the objects matching a specific condition

What records do we have for CA 123 456?

### Find the total of one attribute for objects in a list matching a condition

How many trips did CA 234 567 make?

### Find all the values of one attribute of objects matching a condition

What are the names of all the routes that CA 345 678 took?

### Perform a calculation on attributes of objects matching a condition

What are the total earnings for CA 234 567?

### Perform a calculation on attributes of grouped of objects

What are the total earnings for each taxi?