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

_Replace this text with your answer._
Github is a version control system, that allows different users to make contributions
to a single project. It stores a project, that is usually known as the "Master" branch,
then allows members of a project to "fork" it, which means put it on their local computer
to edit and make changes to it. The individual members then "push" their changes to a new branch
and the team leader can look at these branches and choose whether or not to merge these changes
with the original project.

## Question 3

```js
(false || true) && (false && true);
```

Is the value of this expression `true` or `false`?  Explain your answer.

_Replace this text with your answer._
The value is false. In order for a boolean value to be 'true' with the &&, both sides must be
true. This is already not the case for the expression in parethesis to the right of the first &&, so we
know that the entire expression will have a boolean value of false, because there is at least one false value.
## Question 4

```js
var x = 1;
while (x < 5) {
  x = x + x;
}
```

How many times does the loop run?  What's the value of `x` after the while loop?

_Replace this text with your answer._
The loop will run three times. The first time, x ends up have a value of 2, because 1 + 1 is equal to 2.
Now, x is equal to two. Now when the loop runs x = 4, because 2 + 2 = 4, which is still less than 5,
which is the condition of our while loop. The next time we run the loop though, x = 8, because 4 + 4 = 8.
This does not meet the condition of the loop.

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
The value is 5. A is not greater than 0, so we use the expression a-b. 

## Question 6

```js
var groceryList = [
  'a loaf a bread',
  'a container of milk',
  'a stick of butter',
];
```

What is the value of `groceryList[2]`?

_Replace this text with your answer._

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

_Replace this text with your answer._
