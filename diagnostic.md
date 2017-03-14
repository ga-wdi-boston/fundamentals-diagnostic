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

/Users/grace/

## Question 2

Describe GitHub, **briefly** in your own words.

GitHub is an online repository for code that allows multiple people to work on the same project and control the version of the code that is published

## Question 3

```js
(false || true) && (false && true);
```

Is the value of this expression `true` or `false`?  Explain your answer.

False.  (false || true) evaluates to TRUE.  It must also be the same as (false && true), which evaluates to FALSE because we are using an AND comparison operator.  So, we would be comparing TRUE to FALSE, and that is incorrect.

## Question 4

```js
var x = 1;
while (x < 5) {
  x = x + x;
}
```

How many times does the loop run?  What's the value of `x` after the while loop?

3 times

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

result = 5;
We pass a = 0 and b = -5.  The condition if (a > 0 || b > 0) is FALSE because neither 0 nor -5 is greater than 0, so we evaluate (0 -(-5)), which is 5.

## Question 6

```js
var groceryList = [
  'a loaf a bread',
  'a container of milk',
  'a stick of butter',
];
```

What is the value of `groceryList[2]`?

groceryList[2] = 'a stick of butter';

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

teamMember['hobby'] = {'exercise'};
teamMember['name'] = {given: 'Jason', surname: 'Weeks'};
teamMember['name']['surname'] = {'Weeks'};
