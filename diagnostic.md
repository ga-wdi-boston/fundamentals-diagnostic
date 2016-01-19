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

_What is the full path to the current directory?_

~/wdi/try

## Question 2

Describe GitHub, **briefly** in your own words.

GitHub is a remote repository system used for version control. The main purposes
of GitHub are (1) to enable developers in different locations to share their code,
(2) allow them to maintain control over different versions of a program so that they
aren't destroying each other's work, and (3) to keep their work safely stored in the cloud instead of on a local hard-drive

## Question 3

```js
(false || true) && (false && true);
```

Is the value of this expression `true` or `false`?  Explain your answer.

_This evaluates to false; the statement in the first set of parentheses evaluates to true since only one side of the || must be true for the whole statement to be true, however the second set of parentheses evaluates to false because both sides of && must be true for the statement to evaluate to true. Since between the sets of parenthses is && but only one of them evaluates to true, the entire statement evaluates to false._

## Question 4

```js
var x = 1;
while (x < 5) {
  x = x + x;
}
```

How many times does the loop run?  What's the value of `x` after the while loop?

_The loop runs three times, and the value of x afterwards is 4_

## Question 5

```js
var strangeAdd = function strangeAdd(a, b) {
  if (a > 0 || b > 0) {
    return a + b;
  }
  return a - b;
};

var result = strangeAdd(0, -5);
```

What is the value of result?  Explain your answer.

_This returns -5, because since neither parameter is >0, the if statement does not run, and instead the function gives the default return of a-b_

## Question 6

```js
var groceryList = [
  'a loaf a bread',
  'a container of milk',
  'a stick of butter',
];
```

What is the value of `groceryList[2]`?

_groceryList[2] == "a stick of butter"_

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

What is the value of `teamMember['hobby']`?  Of `teamMember['name']`?  Of `teamMember['name']['surname']`?

teamMember['hobby'] == 'exercise'
teamMember['name'] == ['Jason','Weeks']
teamMember['name']['surname'] == 'Weeks'
