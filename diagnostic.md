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

Graces-MacBook-Pro/Users/grace/wdi/try

## Question 2

Describe GitHub, **briefly** in your own words.

GitHub is an online host for Git, a version control system used to track changes

## Question 3

```js
(false || true) && (false && true);
```

Is the value of this expression `true` or `false`?  Explain your answer.

False. && will return true only if both sides are true

## Question 4

```js
var x = 1;
while (x < 5) {
  x = x + x;
}
```

How many times does the loop run?  What's the value of `x` after the while loop?

3 times, x = 4 on the last loop, next would x = 8 which doesn't meet the while
condition

## Question 5

```js
var strangeAdd = function strangeAdd(a, b) {
  if (a > 0 || b > 0) {
    return a + b;
  }
  return a - b;
};

var result = add(0, -5);
```

What is the value of result?  Explain your answer.

-5, parameters given for strangeAdd match the if statement so it returns a + b

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

'exercise', given: 'Jason' surname: 'Weeks', 'Weeks'
