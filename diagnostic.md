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

GitHub is a Git respository hosting service and user interface for Git. GitHub allows users to collobrate by sharing source code. Users can contribute to existing projects by adding comments, suggesting edits, and 'forking' them to their own respository to
make additonal edits.

## Question 3

```js
(false || true) && (false && true);
```

Is the value of this expression `true` or `false`?  Explain your answer.

'false'. The (false || true) statement evaluates to true. || returns true if
either operand is true. The (false && true) statement evaluates to false.  &&
returns true if both operands are true; otherwise, returns false.

The resulting true && false statement evaluaes to false.

## Question 4

```js
var x = 1;
while (x < 5) {
  x = x + x;
}
```

How many times does the loop run?  What's the value of `x` after the while loop?

The loop runs three times. The value of x after the while loop is 8.
Before loop: x = 1
After first loop: x = 2
After second loop: x = 4
After third loop: x = 8

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

the if(a > 0 || b > 0) statement evaluates to fale, therefore the function
evaluates to a - b. Thus result = 0 - (-5) = 5.

## Question 6

```js
var groceryList = [
  'a loaf a bread',
  'a container of milk',
  'a stick of butter',
];
```

What is the value of `groceryList[2]`?

groceryList[2] = 'a container of milk'

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

'teamMember['hobby']' = 'exercise'
'teamMember['name']' = {given: 'Jason', surname: 'Weeks'}
'teamMember['name']['surname']' = 'Weeks'
