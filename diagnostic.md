![General Assembly Logo](http://i.imgur.com/ke8USTq.png)

# Diagnostic

## Question 1

```sh
Graces-MacBook-Pro:~ grace$ mkdir wdi
Graces-MacBook-Pro:~ grace$ cd wdi
Graces-MacBook-Pro:wdi grace$ pwd
/Users/grace/wdi
Graces-MacBook-Pro:wdi grace$ mkdir try
Graces-MacBook-Pro:wdi grace$ cd try
Graces-MacBook-Pro:try grace$
```

What is the full path to the current directory?

/Users/grace/wdi/try

## Question 2

Describe GitHub, **briefly** in your own words.

GitHub is an online repository that allows users to store, share, and comment on each others code.

## Question 3

```js
(false || true) && (false && true);
```
Is the value of this expression `true` or `false`?  Explain your answer.
False;
(false || true) = T
(false && true) = F
T && F = F

## Question 4

```js
var x = 1;
while (x < 5) {
  x = x + x;
}
```

How many times does the loop run?  What's the value of `x` after the while loop?
value of x = 8, loop runs 3 times

-evaluate X<5 (x=1);
-if it is true that x<5, add x to x and assign x that new value;
-evaluate that the new value of x is less than 5;
-do this until X<5 is flase;

## Question 5

```js
var strangeAdd = function(a, b) {
  if (a > 0 || b > 0) {
    return a + b;
  }
  return a - b;
};

var result = strangeAdd(0, -5);
```
What is the value of result?  Explain your answer.

The answer is 5.

var result(strangeAdd) passes the values 0 and -5 to the strangeAdd function.
the given values return a false in the if statement.
a-b (0-(-5))=5

## Question 6

```js
var groceryList = [
  'a loaf a bread',
  'a container of milk',
  'a stick of butter',
];
```

What is the value of `groceryList[2]`?

"a stick of butter"

groceryList[2] is asking for the third item in the array because items in an array are counted starting with 0


## Question 7

```js
var teamMember = {
  role: 'consultant',
  name: {
    given: 'Jason',
    surname: 'Weeks'
  },
  hobby: 'exercise'
};
```

What is the value of `teamMember['hobby']`?  Of `teamMember['name']`?  Of
`teamMember['name']['surname']`?

None of these will return a value. use the dot notation
to determine hobby use 'teamMember.hobby'
to determine name use 'teamMember.name'
