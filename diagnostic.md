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

_/Users/grace/wdi/try_

## Question 2

Describe GitHub, **briefly** in your own words.

_online repository to help collect and share of git file, which is used for version control.  Version control is like keeping different verison of the same file with with edits._

## Question 3

```js
(false || true) && (false && true);
```

Is the value of this expression `true` or `false`?  Explain your answer.

_false. (false||true) return first true value, in this case, it's true. (false&&true) return true only if both items are true, in this case it's false. this make the simply the statment into true && false, which would return false._

## Question 4

```js
var x = 1;
while (x < 5) {
  x = x + x;
}
```

How many times does the loop run?  What's the value of `x` after the while loop?

_3 times, 8._

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

_5.  1st if condition only happen if a>0 or b>0.  this is case neither 0 or -5 is >0.  which which to return a-b.  which give 0 - -5 = 0 +5 = 5._

## Question 6

```js
var groceryList = [
  'a loaf a bread',
  'a container of milk',
  'a stick of butter',
];
```

What is the value of `groceryList[2]`?

_'a stick of butter'_

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

_teamMember['hobby'] would give us 'exercise'_
_teamMember['name'] would give us_
_given:'Jason'_
_surname: 'Weeks'_
_teamMember['name']['surname'] would give us 'Weeks'_
