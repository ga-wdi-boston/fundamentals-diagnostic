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

GitHub is a version control application that allows developers make changes to dev projects in a systematic way, especially as it concerns collaboration with multiple developers attempting to make changes to the same project.

## Question 3

```js
(false || true) && (false && true);
```

Is the value of this expression `true` or `false`?  Explain your answer.

answer:  false
explanation:  'false || true' resolves to true.  'false && true' resolves to false.  Which leaves true && false, which resolves to false

## Question 4

```js
var x = 1;
while (x < 5) {
  x = x + x;
}
```
How many times does the loop run? What's the value of x after the while loop?

Loop runs 3 times.  x = 8.


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
What is the value of result? Explain your answer.

result = 5.  Neither a nor b are greater than 0, so return a - b, or 0 - -5 = 5.


## Question 6

```js
var groceryList = [
  'a loaf a bread',
  'a container of milk',
  'a stick of butter',
];
```

What is the value of `groceryList[2]`?

a stick of butter

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

teamMember['hobby'] = exercise
teamMember['name'] = Object {given: "Jason", surname: "Weeks"}
teamMember['name']['surname'] = Weeks
