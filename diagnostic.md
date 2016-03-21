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

/Users/Benjamski/wdi/fundamentals-diagnostic/diagnostic.md

## Question 2

Describe GitHub, **briefly** in your own words.

A server used to store copies of files and their changes. To store them or
share/collaborate with others.

## Question 3

```js
(false || true) && (false && true);
```

Is the value of this expression `true` or `false`?  Explain your answer.

False while the operants are the same (in inverse placement) || (or) and &&(and)
are different operators. Because there's no == or === I think it doesn't
evaluate to anything (i think)

## Question 4

```js
var x = 1;
while (x < 5) {
  x = x + x;
}
```

How many times does the loop run?  What's the value of `x` after the while loop?

The value of x is 8, it runs 8 times. while it is less than 5 it adds the value
of x into itself.

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

5. a and b are both NOT greater than 0 (0 and -5) so the second return is issued
which subtracts -5 from 0, evaluating to 5

## Question 6

```js
var groceryList = [
  'a loaf a bread',
  'a container of milk',
  'a stick of butter',
];
```

What is the value of `groceryList[2]`?

'a stick of butter' [2] is the third item in an array of 3

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

teamMember['hobby'] = 'exercise'
`teamMember['name'] = 'Jason'
`teamMember['name']['surname']` = 'Weeks'
