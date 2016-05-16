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

Github is an open-sourced, collaborative online hosting site that allows developers to host their own projects and share the 'inner-workings' (aka code) with others.

## Question 3

```js
(false || true) && (false && true);
```

Is the value of this expression `true` or `false`?  Explain your answer.

'false';
The first parenthesis evaluates to true (it's an 'OR' statement with at least one true argument therefore, it is true).
The second parenthesis evaluates to false (it's an 'AND' statement and in order to be true, both arguments need to be true).
After evaluating both sides, the expression is now true && false. The value of this expression is false.

## Question 4

```js
var x = 1;
while (x < 5) {
  x = x + x;
}
```

How many times does the loop run?  What's the value of `x` after the while loop?

The loop runs 3 times.
x = 8

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

5
a = 0 is not greater than 0. -5 is not greater than 0.
The first condition fails, thus a - b is returned. In that case, 0 - -5 = 5.

## Question 6

```js
var groceryList = [
  'a loaf a bread',
  'a container of milk',
  'a stick of butter',
];
```

What is the value of `groceryList[2]`?

'a stick of butter'

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

'teamMember ['hobby']' = 'exercise'
'teamMember ['name']' = {given: 'Jason', surname:
Weeks'}
'teamMember ['name'] ['surname'] = 'Weeks'
