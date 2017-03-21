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

GitHub is a platform where you can manage git repositories, create push and pull code, and share feedback with other developers.

## Question 3

```js
(false || true) && (false && true);
```

Is the value of this expression `true` or `false`?  Explain your answer.

Answer: FALSE;
First parenthesis is TRUE because it takes the first truthy value.
Second parenthesis is FALSE because it takes the first falsey value.
When you compare the two parenthesis with AND, it takes the first falsey value again, so the answer is FALSE.

## Question 4

```js
var x = 1;
while (x < 5) {
  x = x + x;
}
```

How many times does the loop run?  What's the value of `x` after the while loop?

The loop only runs twice. The final value of x is 4.
Loop 1 has x = 1 + 1; which equals 2.
Loop 2 has x = 2 + 2; which equals 4.
It does not run a third time because x is not less than 5.

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

Both variables a and b are not greater than 0, so we must return a - b. 0 - (-5) is 5.
Answer: 5.

## Question 6

```js
var groceryList = [
  'a loaf a bread',
  'a container of milk',
  'a stick of butter',
];
```

What is the value of `groceryList[2]`?

Easy. groceryList[2] is 'a stick of butter' because the first item on the list is groceryList[0].

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

teamMember['hobby'] is exercise.
teamMember['name'] will return objects:
        given: "Jason",
        surname: "Weeks"
teamMember['name']['surname'] is Weeks.
