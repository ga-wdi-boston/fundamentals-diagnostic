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

users/grace/wdi/try/try_graces

## Question 2

Describe GitHub, **briefly** in your own words.

GitHub is a site that holds repositories.It helps you track your changes, so it makes collaboration easier, too.

## Question 3

```js
(false || true) && (false && true);
```(true) && (false)
    false
Is the value of this expression `true` or `false`?  Explain your answer.

With (OR) it evaluates to "true" because at least one is true. Then (AND) evaluates to "false" because it will only evaluate as true if both of the arguments are true; but in this case it is false. Between true && false, the same rule applies and therefore the last evaluation is to "false"

## Question 4

```js
var x = 1;
while (x < 5) {
  x = x + x;
}
```

How many times does the loop run?  What's the value of `x` after the while loop?

It runs five times because the rule is x<5 for the loop to finish. The final value of 'x' is 32.

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

Value is undefined because the condition is not satisfied by the numbers provided

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

'exercise' of 'jason' of 'jason' 'weeks'
