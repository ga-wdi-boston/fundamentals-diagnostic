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

_Users/grace/wdi/try_

## Question 2

Describe GitHub, **briefly** in your own words.

_GitHub is a company/website that allows people to save and share code with each other... it's basically the Dropbox for developers._

## Question 3

```js
(false || true) && (false && true);
```

Is the value of this expression `true` or `false`?  Explain your answer.

_This expression is `false`. In order for `AND` statements to be `true`, both components must evaluate to `true`. Thus, while the first component is `true`, the second is `false`, leading the overall expression to evaluate to `false`._

## Question 4

```js
var x = 1;
while (x < 5) {
  x = x + x;
}
```

How many times does the loop run?  What's the value of `x` after the while loop?

_The loop runs three times, and the var x = 8 after the while loop._

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

_strangeAdd(0,-5) evaluates to 5 because neither `a` nor `b` are greater than 0... therefore the function skips the `if` statement and runs `return a - b`, and 0 - (-5) = 5._

## Question 6

```js
var groceryList = [
  'a loaf a bread',
  'a container of milk',
  'a stick of butter',
];
```

What is the value of `groceryList[2]`?

_'a stick of butter'_

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

_`teamMember[`hobby`]` is `exercise`; `teamMember[`name`]` is `Jason Weeks`;
`teamMember['name']['surname']` is `Weeks`._
