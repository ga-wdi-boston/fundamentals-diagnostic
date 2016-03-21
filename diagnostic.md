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

Graces-MacBook-Pro

## Question 2

Describe GitHub, **briefly** in your own words.

GitHub is a disributed version control system.

## Question 3

```js
(false || true) && (false && true);
```

Is the value of this expression `true` or `false`?  Explain your answer.

False or true evalutes to be true. False and true evaluates to be false. Therefore true and false evaluates to be false.

## Question 4

```js
var x = 1;
while (x < 5) {
  x = x + x;
}
```

How many times does the loop run?  What's the value of `x` after the while loop?

The loop runs 5 times. x = 4

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

result = 0, -5 The value of the result is false because it returned the second value.

## Question 6

```js
var groceryList = [
  'a loaf a bread',
  'a container of milk',
  'a stick of butter',
];
```

What is the value of `groceryList[2]`?

a loaf of bread a countainer of milk a stick of butter

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

The value of 'teamMember['hobby']' is 'exercise'
The value of teamMember[name] is Jason Weeks
The value of teamMember[name][surname] is Weeks
