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

_/Users/grace/wdi/try_

## Question 2

Describe GitHub, **briefly** in your own words.

_A website that holds repositories for users to download._

## Question 3

```js
(false || true) && (false && true);
```

Is the value of this expression `true` or `false`?  Explain your answer.

_The value of the expression is 'false' because the first expression because 'true' while the second becomes 'false', so because the whole expression is an expanded view of the second sub-expression: (false && true) = false._

## Question 4

```js
var x = 1;
while (x < 5) {
  x = x + x;
}
```

How many times does the loop run?  What's the value of `x` after the while loop?

_The loop runs twice and 'x' becomes '8' after the while loop._

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

_The value of result is 5 because 'a' holds the same value as 0 and 'b' is -5, so we use the return 'a-b' 0 - (-5)= 0 + 5 = 5._

## Question 6

```js
var groceryList = [
  'a loaf a bread',
  'a container of milk',
  'a stick of butter',
];
```

What is the value of `groceryList[2]`?

_The value of 'groceryList[2] is 'a stick of butter'._

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

_'teamMember['hobby'] = "exercise"', 'teamMember['name'] = [object Object] {  given: "Jason", surname: "Weeks"}', and 'teamMember['name']['surname'] = "Weeks"'._
