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

GitHub is a cloud repository used for storing code. This platform allows developers to share, review, and comment on code.

## Question 3

```js
(false || true) && (false && true);
```

Is the value of this expression `true` or `false`?  Explain your answer.

false || true --> true
false && true --> false
true && false --> false
Value of this expression is false because evaluating the individual expressions results in true and false therefore it is false.


## Question 4

```js
var x = 1;
while (x < 5) {
  x = x + x;
}
```

How many times does the loop run?  What's the value of `x` after the while loop?

The loop will run 3 times.
First loop x = 2
Second loop x = 4
Third loop x = 8
Will not run a 4th time because x greater than 5.


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

result = 5
(0 > 0) false
(-5 > 0) false
0 - (-5) = 5

## Question 6

```js
var groceryList = [
  'a loaf a bread',
  'a container of milk',
  'a stick of butter',
];
```

What is the value of `groceryList[2]`?

groceryList[2] = "a stick of butter"
Arrays are indexed starting with 0 so the first item in an array has an index of 0, the second item is 1, and the third item is 2.

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
teamMember['name'] = [object Object] {
  given: "Jason",
  surname: "Weeks"
}
teamMember['name']['surname]= 'Weeks'
