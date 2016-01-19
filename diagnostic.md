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

GitHub is a tool which (along with git) allows software develpers to save
their work, save different versions and branches of their work, and allow
others to contribute to their work without giving up control of the master
set of documents. It is efficient because it tracks changes to documents
rather than tracking entirely different documents.

## Question 3

```js
(false || true) && (false && true);
```

Is the value of this expression `true` or `false`?  Explain your answer.

false. The expression will only evaluate to true if both (false || true) AND
(false && true) would evaluate to true. (false || true) evaluates to true, but
(false && true) evaluates to false, so the whole expression evaluates to false

## Question 4

```js
var x = 1;
while (x < 5) {
  x = x + x;
}
```

How many times does the loop run?  What's the value of `x` after the while loop?

The loop will run three times, and afterwards x = 8

## Question 5

```js
var strangeAdd = function strangeAdd(a, b) {
  if (a > 0 || b > 0) {
    return a + b;
  }
  return a - b;
};

var result = add(0, -5);
```
What is the value of result?  Explain your answer.

//assuming the function "add" is actually "strangAdd"
//5. The conditional statement will not run, because neither
//a or b is greater than 0. 0 - (-5) = 0 + 5 = 5

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

What is the value of `teamMember['hobby']`?  Of `teamMember['name']`?  Of `teamMember['name']['surname']`?

teamMember['hobby'] = 'exercise'
teamMember['name'] = { given: 'Jason', surname: 'Weeks' }
teamMember['name']['surname'] = 'Weeks'
