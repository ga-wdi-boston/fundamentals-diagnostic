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

/Users/Graces/wdi/try

This can be found by entering "pwd" into the terminal.

## Question 2

Describe GitHub, **briefly** in your own words.

GitHub is a source control tool, which means it is useful for saving revision history and allowing people to work on multiple versions of code simultaneously and then merge their work later.  It can be used to save code in repositories which people can download their own versions of (forks) and suggest edits to the original code (pull requests).

## Question 3

```js
(false || true) && (false && true);
```

Is the value of this expression `true` or `false`?  Explain your answer.

False.  The OR statement (||) on the left evaluates to true because only one condition must be true in order for the entire expression to evaluate to true.  The AND statement (&&) on the right evaluates to false, because both conditions must be true in order for the entire expression to evaluate to true.  The AND statement that combines both the OR and the AND statement returns false, because the first AND statement returned false.

## Question 4

```js
var x = 1;
while (x < 5) {
  x = x + x;
}
```

How many times does the loop run?  What's the value of `x` after the while loop?

The loop runs 3 times, and the value of x is 8 after the loop.

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

The function strangeAdd takes two arguments, a and b.
a is passed 0. 0 is equal to 0; this evaluates to false.
b is passed -5. -5 is less than 0; this evaluates to false.
Since both options of the OR statement are false, the expression evaluates to false, and a-b is returned.
0 - (-5) = 5.

result = -5.

## Question 6

```js
var groceryList = [
  'a loaf a bread',
  'a container of milk',
  'a stick of butter',
];
```

What is the value of `groceryList[2]`?

groceryList[2] is storing the string 'a stick of butter'.

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

teamMember['hobby'] is 'exercise'

teamMember['name'] is the associative array
{
  given: 'Jason',
  surname: 'Weeks'
}

teamMember['name']['surname'] is 'Weeks'

"Hi Chris!"
