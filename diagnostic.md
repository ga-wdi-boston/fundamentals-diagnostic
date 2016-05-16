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

Users/Grace/wdi/try

## Question 2

Describe GitHub, **briefly** in your own words.

GitHub is website that allows users to share and download code, track changes made to it, and make updates to existing code. It allows for multiple versions of the same project to exist in a concise, comprehensible manner that makes it clear who made which changes and when. Code can be downloaded and opened locally and then once changes are made, it can easily be shared and organized for any and all relevant parties to access on GitHub.

## Question 3

```js
(false || true) && (false && true);
```

Is the value of this expression `true` or `false`?  Explain your answer.

The value of this expression is `false`. The first expression evaluates as `true` as one is true. The second evaluates as `false` as it can only evaluate as `true` if both are `true`. This boils down to (true && false), which again, only evaluates as `true` if both values are `true` and thus evaluates to `false`.

## Question 4

```js
var x = 1;
while (x < 5) {
  x = x + x;
}
```

How many times does the loop run?  What's the value of `x` after the while loop?

The loop runs three times. The value of `x` after the while loop is x + x. So after the first loop, x = 1 + 1 so 2, after the second, 2 + 2 so 4, after the third, 4 + 4 so 8 and then it stops because x > 5.

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

The value of the result is `-5`. The first if expression says if a > 0 OR b > 0, then to return a + b. Since a = 0, only b > 0 satisfies and thus a + b is returned, meaning 0 + -5 is returned, which = -5. Since a return basically tells an expression to end immediately, the second return is not hit and not needed so the expression evaluates to -5.

## Question 6

```js
var groceryList = [
  'a loaf a bread',
  'a container of milk',
  'a stick of butter',
];
```

What is the value of `groceryList[2]`?

The value of `groceryList[2]` is `a container of milk`

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

The value of 'teamMember['hobby']' is 'exercise'. the value of 'teamMember['name']' is '{given: 'Jason', surname: 'Weeks'}'. The value of 'teamMember['name']['surname']' is 'Weeks'.
