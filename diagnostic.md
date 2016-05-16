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

/Users/mishaherscu/wdi/try

## Question 2

Describe GitHub, **briefly** in your own words.

GitHub is a website for coordinating usage of Git. Git is a version control
software that tracks diffs between versions of files. GitHub allows people to
post their files (mostly code) in repositories. It then lets other users,
who are often their teammates, but could be anyone (unless it's private repo),
fork their repository, clone it to their local computer, make changes, push
those changes, and ultimately submit pull requests to get their changes
merged back into the original source code. Git handles finding any conflicts
while merging branches or just new changes from pull requests.

## Question 3

```js
(false || true) && (false && true);
```

Is the value of this expression `true` or `false`?  Explain your answer.

This expression is false. The first section is an OR so it evaluates to true
because it has a true. The second part is an AND so it evaluates to false
because it has a false. The two sections are connected by an AND so the entire
expressions is false because the second part is false.

## Question 4

```js
var x = 1;
while (x < 5) {
  x = x + x;
}
```

How many times does the loop run?  What's the value of `x` after the while loop?

The loop will run 3 times and x will have the value of 8 when the loop is
finished running. The reason is that it doubles whenever the loop runs. The
first run checks and 1 < 5 so x becomes 2. The next cycle checks 2 < 5 then
x goes from 2 to 4. Then since 4 < 5, x becomes 8. Then since 8 > 5 the loop
is done.

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

The result is 5 because neither argument is greater than zero so we subtract
b from a instead of adding them. 0 - (-5) = 5.

## Question 6

```js
var groceryList = [
  'a loaf a bread',
  'a container of milk',
  'a stick of butter',
];
```

What is the value of `groceryList[2]`?

'a stick of butter'. The only thing to remember here is that javascript
indexes from zero.

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

`teamMember['hobby']` has the value of `'exercise'`, which is a string.
`teamMember['name']` has the value of `{given: 'Jason', surname: 'Weeks'}`,
which is an associative array.
`teamMember['name']['surname']` has the value of `'Weeks'`, which is a string.

Hmm I hope this is right, but I feel like I may be missing something.
However, rather than obsessively trying to get this right, I think it is
better to just try something so I can fail fast and work from there.
That is what Jeff would do (I think).
