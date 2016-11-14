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

current direcory is try

## Question 2

Describe GitHub, **briefly** in your own words.

_git hub is a repository for projects that can be pulled and pushed by other coders

## Question 3

```js
(false || true) && (false && true);
```

false statement, (false or true )and (false and true)

_Replace this text with your answer._

## Question 4

```js
var x = 1;
while (x < 5) {
  x = x + x;
}
```
it will run twice x=2 then x=4


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
if a is less than zero or b greater than zero the answer will be a + b if not the answer will be a - b

## Question 6

```js
var groceryList = [
  'a loaf a bread',
  'a container of milk',
  'a stick of butter',
];
```

What is the value of `groceryList[2]`?

_stick of butter
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

teamMember.name.given.surname = jason weeks  teamMemeber.hobby = exercize
