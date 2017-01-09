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

Github is an online database that allows programmers to update changes they've made to a file, locally, on the web. It allows developers to keep track of each and every individual change they make to a file, as a means of record.

## Question 3

```js
(false || true) && (false && true);

```

Is the value of this expression `true` or `false`?  Explain your answer.

True. First half equates to True because  || defaults to true if either side is True.  Not 100% confident on how && works, so I will stick with True.

## Question 4

```js
var x = 1;
while (x < 5) {
  x = x + x;
}
```

How many times does the loop run?  What's the value of `x` after the while loop?

This loop will run up to 5 times. The value of X will be 8.

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

The value of the result is 5. Since the if is false in both arguments, it defaults the the second return value that is outside the if statement. 0 - (-5) = 5


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

'Exercise'. 'jason', 'weeks'. [1,2].

Definitely not feeling confident on this one^
