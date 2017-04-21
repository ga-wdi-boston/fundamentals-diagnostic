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

~/wdi/diagnostics/fundamentals-diagnostic

## Question 2

Describe GitHub, **briefly** in your own words.

It is an online server where you can save/store your work in stages. It also allows you to collaborate on a project with others.

## Question 3

```js
(false || true) && (false && true);
```

Is the value of this expression `true` or `false`?  Explain your answer.

false || true = true
false && true = false
true && false = FALSE

Answer = False

## Question 4

```js
var x = 1;
while (x < 5) {
  x = x + x;
}
```

How many times does the loop run?  What's the value of `x` after the while loop?

1 < 5 (true)
x = 2
2 < 5 (true)
x = 4
4 < 5 (true)
x = 8
8 < 5 (false)

Answer: x = 8

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

if (0 > 0 || -5 > 0) {
  return 0 + -5;
}
  return 0 - (-5);
};

(0 > 0) false
(-5 > 0) false
(false || false)
If statment only runs if true so return a - b with run.
0 - (-5) = 5

Answer: results = 5

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

'exercise'
[given: 'Jason', surname: 'Weeks']
'Weeks'
