

# Exercises: JavaScript loops

Paste your answers into this file.

<br>

## Print every number from 0 to 10

```
for (var i=0; i<=10; i++){
console.log(i);
}

```

<br>

## Print every number from 10 to 0

```
for (var i=10; i>=0; i--){
console.log(i);
}

```

<br>

## Print every number from 4 to -16

```
for (var i=4; i>=-16; i--){
console.log(i);
}

```

<br>

## Print every fifth number from 8 to 41

```
for (var i = 8; i <= 41; i += 5){
  console.log(i);
}

```

<br>

## The classic Fizzbuzz Program

For every `number` between 1 and 100...

If the `number` is evenly divisible by 3, print "Fizz"

If the `number` is evenly divisible by 5, print "Buzz"

If the `number` is evenly divisible by 3 AND evenly divisible by 5, print "Fizzbuzz"


```
for (var i=1; i<=100; i++){
  var resultOutput = '';
  if (i % 3 === 0) 
	{resultOutput += 'Fizz';}
if (i % 5 === 0) 
	{resultOutput += 'Buzz';}
if (i % 3 !== 0 && i % 5 !== 0)
	{resultOutput += i;}
  console.log(resultOutput);
}

```

<br>


## The even/odd reporter

Write a for loop that will iterate from 0 to 20. For each iteration, it will check if the current number is even or odd, and report that to the screen (e.g. "2 is even").

```
for (var i=0; i<=20; i++){
  if (i % 2 == 0){
    console.log(`${i} is Even`); 
    } else console.log(i);
}

```

<br>

## Multiplication Tables

Write a for loop that will iterate from 0 to 10. For each iteration of the for loop, it will multiply the number by 9 and log the result (e.g. "2 * 9 = 18").

Bonus: Use a nested for loop to show the tables for every multiplier from 1 to 10 (100 results total).


```
for (var i=0; i <=10; i++){
  console.log(`${i} * 9 = ${i*9}`);
}

for (var i=0; i <=10; i++){
  for (var n=0; n <=100; n++){
  console.log(`${i} * ${n} = ${i*n}`);
  }
}
```

<br>

## The Grade Assigner

Check the results for every value from 60 to 100 - so your log should show "For 89, you got a B. For 90, you got an A.", etc.

```

for (var i=60; i<=100; i++){
  if (i >= 60 && i <= 69){
    console.log(`For ${i}, you got a D.`)
  } else
  if (i >= 70 && i <= 79){
    console.log(`For ${i}, you got a C.`)
  } else
  if (i >= 80 && i <= 89){
    console.log(`For ${i}, you got a B.`)
  } else
  if (i >= 90 && i <= 100){
    console.log(`For ${i}, you got a A.`)
  }
}

```
