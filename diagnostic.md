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
GitHub is an online source management system using GIT. This is used to store code repositories and manage version control. Often used to manage the code for open source projects.

## Question 3

```js
(false || true) && (false && true);
```

Is the value of this expression `true` or `false`?  Explain your answer.
FALSE.
The || is the logical OR operator and the && is the logical AND operator.
If false OR true...then true (logical operator).
If false and true...then false.
If true and false...then false.


## Question 4

```js
var x = 1;
while (x < 5) {
  x = x + x;
}
```

How many times does the loop run?  What's the value of `x` after the while loop?
n1: x = 1 + 1 (2)
n2: x = 2 + 2 (4)
n3: x = 4 + 4 (8)
This runs 3 times with a final result of 8.


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
if (0 > 0 OR -5 > 0)
0 - - 5 = 5
The parameters evaluate as FALSE and calculate a returned value of a-b (5).

## Question 6

```js
var groceryList = [
  'a loaf a bread',
  'a container of milk',
  'a stick of butter',
];
```

What is the value of `groceryList[2]`?
a stick of butter. Arrays are 0 based.

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
1) exercise
2) Jason Weeks
3) Jason Weeks, Weeks
