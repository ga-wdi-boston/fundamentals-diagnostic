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

wdi/try

## Question 2

Describe GitHub, **briefly** in your own words.

GitHub is a virtual hub for repositories used to share code, track changes, and let other view projects you've worked on. I'd equivalate it to Google-docs + Dropbox for code.

## Question 3

```js
(false || true) && (false && true);
```

Is the value of this expression `true` or `false`?  Explain your answer.

false.
Breaking it down:
1 and 2
(A or B) and (C and D).
1: (false or true) is true because at least one statement is true.
2: (false and true) is false because not all statements are true
overall: true && false evaluates to false for the same reason as part 2.

## Question 4

```js
var x = 1;
while (x < 5) {
  x = x + x;
}
```

How many times does the loop run?  What's the value of `x` after the while loop?

Loop runs 3 times.
Loop ends when x = 8;

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

result == 5;
The if statement does not run because neither 0>0 nor -5>0. So the default case of 0-(-5) runs producing a result of 5.

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

{
  given: 'Jason',
  surname: 'Weeks'
}

'Weeks'
