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

GitHub is a source code version control repository.

## Question 3

```js
(false || true) && (false && true);
```

The value of the expression is false. The reason for tis is that (false || true) translates to "false or true", which evaluates to true.  (false && true) translates to false and true, which evaluates to false.  This leaves us with true && false, which evaluates to false.

## Question 4

```js
var x = 1;
while (x < 5) {
  x = x + x;
}
```

How many times does the loop run?  What's the value of `x` after the while loop?


The loop runs 3 times.  The value of 'x' after the while loop is 4.

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

The value of result is 5.  The first path  (return a + b) would be taken if a or b is greater than 0.  However, neither a nor b are greater than 0, so the second path (return a - b) is taken.  Since the value of a is 0 and the value of b is -5, this translates to 0 minus -5, which equals 5.


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

The above does not appear to be a valid expression.  For example, if we wanted to know the value of "role", the expression would be "teamMember.role;"  The expression as written above would not return a value.
