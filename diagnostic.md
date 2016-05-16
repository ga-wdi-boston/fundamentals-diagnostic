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

_Graces-MacBook-Pro:~ grace$~/wdi/try$_

## Question 2

Describe GitHub, **briefly** in your own words.

_GitHub is a website that allows us to save code and share code with others throughtout the internet.  In addition, allows us to work on issues while making copies of your work so if the code you worked on is not the issue, you can revert back to the original and work on a different part._

## Question 3

```js
(false || true) && (false && true);
```

Is the value of this expression `true` or `false`?  Explain your answer.

_False due to the fact that repl.it said so.  If it is both true and false, then your answer will be false.  If your answer is both true, then your answer would be true._

## Question 4

```js
var x = 1;
while (x < 5) {
  x = x + x;
}
```

How many times does the loop run?  What's the value of `x` after the while loop?

_the loop will run 4 times and the value of x after the loop will equal 5_

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

_the result is going to be 5.  the reason for that is you have a double negative for b which the equations comes out to 0-(-5) which equates to 5._

## Question 6

```js
var groceryList = [
  'a loaf a bread',
  'a container of milk',
  'a stick of butter',
];
```

What is the value of `groceryList[2]`?

_2 loafs of bread, 2 contaniers of milk, 2 sticks of butter_

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

_exercise, Jason, JasonWeeks_
