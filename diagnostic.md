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

`/Users/grace/wdi/try`

## Question 2

Describe GitHub, **briefly** in your own words.

_A place where developers can share and build upon each other's code._

## Question 3

```js
(false || true) && (false && true);
```

Is the value of this expression `true` or `false`?  Explain your answer.

_False._  `(false || true)` _evaluates to true._  `(false && true)` _evaluates to false. This gives us a final expression of_ `false && true` _which evaluates to false._

## Question 4

```js
var x = 1;
while (x < 5) {
  x = x + x;
}
```

How many times does the loop run?  What's the value of `x` after the while loop?

_It will run 3 times. The value of 'x' after the while loop is 8._

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

_The value of result is 5._
_a is 0 and and therefore not greater than 0.  b is -5 and also not greater than 0.  Therefore, a - b will be returned.  0 - (-5) is equal to 5._

## Question 6

```js
var groceryList = [
  'a loaf a bread',
  'a container of milk',
  'a stick of butter',
];
```

What is the value of `groceryList[2]`?

_The value of_ `groceryList[2]` _is_ `a stick of butter`

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

_The value of_ `teamMember['hobby']` _is_ `exercise`
_The value of_ `teamMember['name']` _is_ `Object {given: 'Jason', surname: 'Weeks'}`
_The value of_ `teamMember['name']['surname']` _is_ `Weeks`
