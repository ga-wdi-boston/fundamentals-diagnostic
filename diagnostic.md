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


What is the full path to the current directory?

_Replace this text with your answer._
/Users/grace/wdi

## Question 2

Describe GitHub, **briefly** in your own words.

_Replace this text with your answer._
files sharing and saving, like a database

## Question 3

```js
(false || true) && (false && true);
```

Is the value of this expression `true` or `false`?  Explain your answer.

_Replace this text with your answer._
False, false || true is true, false && true is false, so true && false is false

## Question 4

```js
var x = 1;
while (x < 5) {
  x = x + x;
}
```

How many times does the loop run?  What's the value of `x` after the while loop?

_Replace this text with your answer._
4

## Question 5

```js
var strangeAdd = function strangeAdd(a, b) {
  if (a > 0 || b > 0) {
    return a + b;
  }
  return a - b;
};

var result = add(0, -5);
```

What is the value of result?  Explain your answer.

_Replace this text with your answer._
-5
function strangeAdd assigning the value of a and b.
if a > 0 or b > 0, either case is true, both not true so a + b, 0+(-5)=-5

## Question 6

```js
var groceryList = [
  'a loaf a bread',
  'a container of milk',
  'a stick of butter',
];
```

What is the value of `groceryList[2]`?

_Replace this text with your answer._
a stick of butter

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

What is the value of `teamMember['hobby']`?  Of `teamMember['name']`?  Of `teamMember['name']['surname']`?

_Replace this text with your answer._
value of teamMember hobby is exercise
value of teamMember name is JasonWeeks
value of teamMember name surname is JasonWeeks Weeks
