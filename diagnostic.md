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

/Users/Graces-MacBook-Pro/wdi/try/

## Question 2

Describe GitHub, **briefly** in your own words.

You can upload and share projects and log changes to the GitHub repository.

## Question 3

```js
(false || true) && (false && true);
```

Is the value of this expression `true` or `false`?  Explain your answer.

False. Because the first parentheses result is true and the second parentheses
result is false. For "&&" operator result, you need both conditions to be true.

## Question 4

```js
var x = 1;
while (x < 5) {
  x = x + x;
}
```

How many times does the loop run?  What's the value of `x` after the while loop?
4 times. The value after while loop is 8.

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

-5 is the result value because (0,-5) is false for both conditons in the ||
operator in the if statement, so javascript will run the next statement return,
which is a-b.

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
exercise
