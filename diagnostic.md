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

GitHub is a place where you can push your code into a repository. This makes it so you can track edits you have made to code over time as well as share code with others.

## Question 3

```js
(false || true) && (false && true);
```

Is the value of this expression `true` or `false`?  Explain your answer.

The left side of the statement evaluates to (true) and the right side evaluates to (false) so then we are analyzing true && false which evaluates to false. It is asking is this statement is true and false which evaluates to false because it is two separate things.

## Question 4

```js
var x = 1;
while (x < 5) {
  x = x + x;
}
```

4 times, x=5



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

The answer is 5. You substitute 0 and -5 in place of a and b, respectively. The if statement is only executed if a is greater than 0 or if bis greater than 0, neither of which is true. Thus, you get put at the return point which is 0 - (-5)=

## Question 6

```js
var groceryList = [
  'a loaf a bread',
  'a container of milk',
  'a stick of butter',
];
```

What is the value of `groceryList[2]`?

'a container of milk'

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

'excercise'
'Jason' 'Weeks'
'Weeks'
