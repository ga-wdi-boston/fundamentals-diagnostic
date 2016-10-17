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

An online service for storing, sharing, and managing git project repositories allowing teams to work together on a single project without stepping all over eachother's work through the application of strong version control.

## Question 3

```js
(false || true) && (false && true);
```

Is the value of this expression `true` or `false`?  Explain your answer.

False, if you think of it like a punnet square false is a dominant trait when the comparator is 'and' while true is dominant when the comparator is 'or'. Since solving the brackets first makes the expression 'true && false' the answer must be false.

## Question 4

```js
var x = 1;
while (x < 5) {
  x = x + x;
}
```

How many times does the loop run?  What's the value of `x` after the while loop?

3 times with the final value of x being equal to 8.

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

The final answer is 5. Since the values of neither a nor b in function "stangeAdd" are greater than 0 the returned value wll be 0 - -5 = 5.

## Question 6

```js
var groceryList = [
  'a loaf a bread',
  'a container of milk',
  'a stick of butter',
];
```

What is the value of `groceryList[2]`?

The value of `groceryList[2]` is "a stick of butter" as the indexes for an array start at 0 the 3 list item will have and index value of '2'.

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

`teamMember['hobby']` = index of [2]
`teamMember['name']` = index of [1]
`teamMember['name']['surname']` = index of [1][1]
