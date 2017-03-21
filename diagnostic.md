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

It is an online version control repository for files and code. Developers can use it to store projects, upload, update, and download code repositories.

## Question 3

```js
(false || true) && (false && true);
```

Is the value of this expression `true` or `false`?  Explain your answer.

False - You would first evaluate (false || true). In this case, with the OR operator, you return the first truthy value. In this case, it would be the second value "true". Then you evaluate the second portion (false && true). With the AND operator, you return the first falsey value which is the first value of "false". Next, you compare the (true) from the first parenthesis with the AND operator and the (false) from the second parenthesis. In this case, you would return the first falsey value which gives you a final value of 'false'.

## Question 4

```js
var x = 1;
while (x < 5) {
  x = x + x;
}
```

How many times does the loop run?  What's the value of `x` after the while loop?

It runs 3 times. The value of x after the while loop is 8.

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

var result = 5

When running the function, you will first look at the first "if" statement with the OR operator. In this case, a=0. As a result, a is not greater than 0. You will then look at the second part. b = -5. As a result, b is not greater than 0. Given the condition in the if statement doesn't apply, you go to the second part of the function. You would return a-b. Which is: 0- -5 = 5.

## Question 6

```js
var groceryList = [
  'a loaf a bread',
  'a container of milk',
  'a stick of butter',
];
```

What is the value of `groceryList[2]`?

groceryList[2] = 'a stick of butter'

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
teamMember['name'] = {
          given: 'Jason',
          surname: 'Weeks'}
teamMember['name']['surname'] = 'Weeks'
