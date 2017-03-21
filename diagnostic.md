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

GitHub is an online repository hosting service that stores Git repositories, which are distributed version control software.

## Question 3

```js
(false || true) && (false && true);
```

Is the value of this expression `true` or `false`?  Explain your answer.

false.
The 'or' statement (false || true) evaluates to true.
The 'and' statement evaluates to false.
As a result, the overall 'and' statement is equivalent to (true && false).  This makes it evaluate to false.





## Question 4

```js
var x = 1;
while (x < 5) {
  x = x + x;
}
```

How many times does the loop run?  What's the value of `x` after the while loop?

1 - initial value
2 - run 1
4 - run 2
8 - run 3

The loop runs 3 times before exiting the loop because x = 8 which is greater than 5.

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

Neither a nor b are greater than 0.  As a result, the function returns a-b or 0 - (-5).  This equals 0 + 5 or 5.  Thus the function evaluates to 5.

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

`teamMember['hobby']` = 'exercise'
`teamMember['name']` = {
    given: 'Jason',
    surname: 'Weeks'
  }

  `teamMember['name']['surname']` = "Weeks"
