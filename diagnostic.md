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

GitHub is a website for storing git repositories online.
Git is a version control program used for tracking edits and modifications to
files.

## Question 3

```js
(false || true) && (false && true);
```

Is the value of this expression `true` or `false`?  Explain your answer.

The value is: false
Reason: (false || true) && (false && true);
        (true) && (false);
        false;

## Question 4

```js
var x = 1;
while (x < 5) {
  x = x + x;
}
```

How many times does the loop run?  What's the value of `x` after the while loop?

The loop runs 3 times. The value of x after the while loop is: 8

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

The value of result is 5.
Reason: strangeAdd is called with parameters 0 and -5
        So the if statement is if (0 > 0) || -5 > 0) which becomes (false || false)
        which is false, so the if statement code doesn't run.
        The next line is return a - b; which becomes return 0 - (-5) so it
        becomes just 5. Thus result stores: 5

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

Value of teamMember['hobby'] is: 'exercise'
Value of teamMember['name'] is: {given: 'Jason', surname: 'Weeks'}
Value of teamMember['name']['surname'] is: 'Weeks'
