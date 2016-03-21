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

/Users/grace/try

## Question 2

Describe GitHub, **briefly** in your own words.

A place to store and retrieve code.  This enables version control and sharing of code.

## Question 3

```js
(false || true) && (false && true);
```

Is the value of this expression `true` or `false`?  Explain your answer.

False.  False or true is TRUE.  False and True is FALSE.  True and False is FALSE.

## Question 4

```js
var x = 1;
while (x < 5) {
  x = x + x;
}
```

How many times does the loop run?  What's the value of `x` after the while loop?

x is 1, then x is 2, then x is 4, but 4+4 > 5 so the loop breaks.  The loop runs three times in total.  The value of x is 4.

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

(0,-5) are passed to function assinged to variable strangeAdd.  a = 0, and it's not greater than 0, b = -5 and it's not greater than -5, so the first part of the if statement is false.  then the code executes the second part of the if statement.  0 - (-5_) = positive 5.  the result is positive 5.

## Question 6

```js
var groceryList = [
  'a loaf a bread',
  'a container of milk',
  'a stick of butter',
];
```

What is the value of `groceryList[2]`?

"a stick of butter".  groceryList is an array. all arrays begin with [0]. [2] is the third element of the array.

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

What is the value of `teamMember['hobby']`?  Of `teamMember['name']`?  Of `teamMember['name']['surname']`?

`teamMember['hobby']` = excercise; `teamMember['name']` = { given: 'Jason', surname: 'Weeks'}; teamMember['name']['surname'] = Weeks
