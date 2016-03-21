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

_A company that mananges Git respositories in the cloud. GitHub is used for developers to track, share, and manages changes to their code. The changes are tracked and stored in respositories._

## Question 3

```js
(false || true) && (false && true);
```

Is the value of this expression `true` or `false`?  Explain your answer.

_False. The parenthesis on the left side is false, as '&&' requires BOTH sides are true. On the first parentheis on the right side, the '||' signifies only one side needs to be true. Therefore, after solving the parenthesis, you have the equation'true && false', which is false._

## Question 4

```js
var x = 1;
while (x < 5) {
  x = x + x;
}
```

How many times does the loop run?  What's the value of `x` after the while loop?

_1+1 = 2; 2+2 = 4; 4+4 = 8. The loop will run 3 times, and the value of x after will be 8._

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

_If a is greater than 0 OR b is greater than 0, return a + b ; otherwise, return a - b. Condition 1 is not met, therefore return (0 - (-5)) = 5._

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

_teamMember['hobby'] = exercise; teamMember['name'] = {given: 'Jason', surname: 'Weeks'}; teamMember['name']['surname'] = Weeks_
