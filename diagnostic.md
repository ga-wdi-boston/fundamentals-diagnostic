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

GitHub is an online hosting service for code repositories that facilitates
collaboration between developers using Git.

## Question 3

```js
(false || true) && (false && true);
// first one evaluates to true
// second one evaluates to false
// larger expression is "true && false", which evals to false
```

Is the value of this expression `true` or `false`?  Explain your answer.

False. The first half of the expression evaluates to 'true' and the second half
evaluates to 'false', reducing the larger expression to 'true && false', which
evaluates to 'false'.

## Question 4

```js
var x = 1;
while (x < 5) {
  x = x + x;
}
```

<!-- // iteration   x < 5?  x
//      1           true    2
//      2           true    4
//      3           true    8
//      4           false -> loop does not run a 4th time -->

How many times does the loop run?  What's the value of `x` after the while loop?

The loop runs 3 times, and when it completes, the value of x is 8.

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

The value of result is 5. The function strangeAdd first checks to see if either
value passed in is greater than zero. Since neither 0 nor -5 is greater than
zero, the if block does not run. strangeAdd then executes 'return a - b', which
returns a value of (0 - (-5)), or 5. This value is then assigned to the
variable 'result'.

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

The value of `teamMember['hobby']` is 'exercise'

The value of `teamMember['name']` is {
  given: 'Jason',
  surname: 'Weeks'
}

The value of `teamMember['name']['surname']` is 'Weeks'
