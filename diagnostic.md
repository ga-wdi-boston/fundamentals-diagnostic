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

/Users/grace/wdi

## Question 2

Describe GitHub, **briefly** in your own words.

Github is a website that allows developers to:
1) Keep track of changes they are making to their code in a given project
2) Share that code with other developers
3) Get code from other developers, copy it, and work on it themselves
4) Work collaboratively with other developers on a single project, by creating multiple versions of the the same "master" and tracking changes made along the way on individual "branches"

## Question 3

```js
(false || true) && (false && true);
```

Is the value of this expression `true` or `false`?  Explain your answer.

The expression is false because the first statement evaluates to true, but the last statement evaluates to false, because it uses the AND boolean, meaning both inputs (can't remember correct word) must be true for the entire statement to evaluate to true.

## Question 4

```js
var x = 1;
while (x < 5) {
  x = x + x;
}
```

How many times does the loop run?  What's the value of `x` after the while loop?

The loop runs 3 times and the final value of x is 8.

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

I don't know the answer to this question.

## Question 6

```js
var groceryList = [
  'a loaf a bread',
  'a container of milk',
  'a stick of butter',
];
```

What is the value of `groceryList[2]`?

It is 'a stick of butter' because in JS array indexes are zero-based, meaning the first element is 0, the next is 1, and the next is 2, which is the 'butter' element listed in this example.

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

I am not very confident about these answers but, in order:
exercise; Jason Weeks; Jason Weeks Weeks
