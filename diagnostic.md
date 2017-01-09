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

/users/grace/wdi/try

## Question 2

Describe GitHub, **briefly** in your own words.

GitHub is tool that allows developers to store versions of their code on the cloud as they are creating it. It is similar to Dropbox where developers can store iterations of a project on the cloud for others to look at and contribute code on various projects.

## Question 3

```js
(false || true) && (false && true);
```

Is the value of this expression `true` or `false`?  Explain your answer.

The value  of this expression is 'false'. The expression on the left resolves to 'true', while the expression on the left resolves to false. The resulting expression is (true && false) which resolves to false. This is because in order to be true both must be true since the expression is using an && operator.

## Question 4

```js
var x = 1;
while (x < 5) {
  x = x + x;
}
```

How many times does the loop run?  What's the value of `x` after the while loop?

This loop runs 3 times. The value of x after the loop resolves is 8.

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

the value of the result is 5. The two values inputed into the strangeAdd function do not trigger the 'if' conditional because the conditional resolves to false when the value of a and b is 0 or less. This then triggers the final return which calculates the difference between the two variables.

## Question 6

```js
var groceryList = [
  'a loaf a bread',
  'a container of milk',
  'a stick of butter',
];
```

What is the value of `groceryList[2]`?

'a stick of butter

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

teamMember['hobby'] = 'exercise', teammember['name'] = {given: 'Jason', surname: 'Weeks'}, the last one = 'exercise'
