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

GitHub is a website that connects many different people to files, and versions
of these files, submitted through git, that they want to share with eachother.

## Question 3

```js
(false || true) && (false && true);
```

Is the value of this expression `true` or `false`?  Explain your answer.

FALSE. First parentheses asks if either false or true are true. The answer is
true. Second parentheses asks if both false and true are true. This is false.
These two statements are then asked if they are both true, which is false.

## Question 4

```js
var x = 1;
while (x < 5) {
  x = x + x;
}
```

How many times does the loop run?  What's the value of `x` after the while loop?

It runs three times. The values of x is then 8.

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

-5 is the result. The if statement says if either a is greater than zero or if
b is greater than zero, then it will return the sum of the two numbers,
otherwise it will return the difference. In this case its returning the
difference. But the result would be the same regardless in this situation....

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

What is the value of `teamMember['hobby']`?  Of `teamMember['name']`?  Of
`teamMember['name']['surname']`?

'exercise'
''{ given: 'Jason', surname: 'Weeks' }'
'Weeks'
