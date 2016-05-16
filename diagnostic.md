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

GitHub manages repositories. One can fork -- orprepare to download a directory -- or clone actually download the directory off the internet/GitHub, directories from GitHub using terminal on the computer.  One can also commit changes to a Github repository so that the commits can be accessed via a log to see what changes have been commited to a GitHub repository.

## Question 3

```js
(false || true) && (false && true);
```

Is the value of this expression `true` or `false`?  Explain your answer.

Evaluates to false.
First parentheses evaluates to true.  Second parentheses evaluates to false.  Now for the final evaluation, true && false evaluates to false.

## Question 4

```js
var x = 1;
while (x < 5) {
  x = x + x;
}
```

How many times does the loop run?  What's the value of `x` after the while loop?

This loop will run 3 times and final value of x is 8
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

because NEITHER 0 nor 5 is greater than 0, the first 'if' statement will not be executed
therefore, a - b will be executed which results to 0 - -5 = 5

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

teamMember['hobby'] === "exercise"
teamMember['name'] === "{ given: 'Jason', surname: 'Weeks' }"
teamMember['name']['surname'] === 'Weeks'
