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

~/Users/grace/wdi/try

## Question 2

Describe GitHub, **briefly** in your own words.

GitHub is a website that allows users to track changes in their code by keeping track of commits which create copies of their code.  This allows the user to see different versions of their code and create a tidy and organized file.  The main benefit is the ability to track changes and to rewind to any point in the creation process of the file.

## Question 3

```js
(false || true) && (false && true);
```

Is the value of this expression `true` or `false`?  Explain your answer.

False.  The first expression in parentheses evaluates to true because true OR false evaluates to true and the second expression in parentheses evaluates to false because true AND false evaluates to false.  The overall expression true AND false therefore evaluates to false.

## Question 4

```js
var x = 1;
while (x < 5) {
  x = x + x;
}
```

How many times does the loop run?  What's the value of `x` after the while loop?

1. x = 1
2. x = 2
3. x = 4

The loop runs 3 times.

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

a = 0 and b = -5, so the else clause runs.  0 - (-5) = 5, so the value of result is 5.

## Question 6

```js
var groceryList = [
  'a loaf a bread',
  'a container of milk',
  'a stick of butter',
];
```

What is the value of `groceryList[2]`?

The value of groceryList[2] is 'a stick of butter'

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

teamMember['hobby'] = 'exercise'
teamMember['name'] = 'Jason' + 'Weeks'
teamMember['name']['surname'] = 'Weeks'
