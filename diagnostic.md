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

It's a website that stores open-source code amongst users, where a user can
send their projects to this web-based repository and other users can take the
original author's code to revise.

## Question 3

```js
(false || true) && (false && true);
```

Is the value of this expression `true` or `false`?  Explain your answer.

`false` because,within the second paranthesis, both boolean statements needtobe
true, when you are using an && logical operator. Since it reverts to false,
you are left with true (from the first paranthesis) and false (from the second)
which is within an && statment. Since, only one is True and the other is False,
the statment returns false.


## Question 4

```js
var x = 1;
while (x < 5) {
  x = x + x;
}
```

How many times does the loop run?  What's the value of `x` after the while loop?

The loop should run 3 times. The value of `x` should be 4.

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

0 - (-5) = 5; the value should be 5. Since both parameters are not greater than
0, it moves to the next statment which is return a - b.

## Question 6

```js
var groceryList = [
  'a loaf a bread',
  'a container of milk',
  'a stick of butter',
];
```

What is the value of `groceryList[2]`?

the value is 'a stick of butter'

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

'teamMember['hobby']' = 'exercise'; 'teamMember'['name'] = given: 'Jason',
surname: 'Weeks'; 'teamMember['name']['surname']' = 'Weeks';
