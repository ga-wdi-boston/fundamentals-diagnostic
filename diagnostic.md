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

GitHub is a tool that allows multiple people to work on a web development project and is an efficient way to complete the project.  It enables a developer to keep track of changes made to a web app and allows the web app owner to accept or deny changes made by others.

## Question 3

```js
(false || true) && (false && true);
```

Is the value of this expression `true` or `false`?  Explain your answer.

false

## Question 4

```js
var x = 1;
while (x < 5) {
  x = x + x;
}
```

How many times does the loop run?  What's the value of `x` after the while loop?

4 times

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

The answer is 5 (a - b or 0 - (-5) ).  The answer is obtained by recognizing that the if statement is false.  That is, neither 0, nor -5 is strictly greater than 0. Therefore, you do not complete the return value within the if statement.

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

'teamMember'['hobby']' is 'exercise'
'teamMember['name']'? is an error because you do not specify if you are referring to the "given" or "surname"
`teamMember['name']['surname']`? is 'Weeks';
