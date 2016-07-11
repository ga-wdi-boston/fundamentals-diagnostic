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

GitHub is an application that tracks your progress, saves your changes without
interferring your previous work, and lets others use and improve your code.
It is a colaboration platform.

## Question 3

```js
(false || true) && (false && true);
```

Is the value of this expression `true` or `false`?  Explain your answer.

Logic operator && is only true if both expressions are true.

Left side of the expression: logic operator || can give us false or true value;
Right side of the expression: logic operator && gives us false value;

false && false -> false;
true && false -> false;

The value of this expression is false.


## Question 4

```js
var x = 1;
while (x < 5) {
  x = x + x;
}
```

How many times does the loop run?  What's the value of `x` after the while loop?

While loop runs four times.

x= 1+1; x=2;
x= 2+1; x=3;
x= 3+1; x=4;
x= 4+1; x=5;

The value of x is 5.

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

a > 0 || b > 0
a isn't larger than 0. b isn't larger than 0. Return a-b.

Result is 5.

## Question 6

```js
var groceryList = [
  'a loaf a bread',
  'a container of milk',
  'a stick of butter',
];
```

What is the value of `groceryList[2]`?

The value of groceryList[2] is "a stick of butter";

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


The value of teamMember['hobby'] is "excercise";

The value of teamMember['name'] is

name: {
  given: 'Jason',
  surname: 'Weeks'
},

The value of teamMember['name']['surname'] is "Weeks";
