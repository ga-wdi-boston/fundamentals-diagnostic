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

Git is a program used for version control (eg - keeping track of changes you've made to code you've written).
Github is a website where one can upload/review/share those gits and work on them with other people.

## Question 3

```js
(false || true) && (false && true);
```

Is the value of this expression `true` or `false`?  Explain your answer.

'false'

The statement on the left (false||true) evaluates to 'true', but the && means that
both sides have to evaluate to the same thing in order for the full expression to evaluate
to true. Since the statement on the right (false && true) evaluates to false, the entire expression
therefore evaluates to false.

## Question 4

```js
var x = 1;
while (x < 5) {
  x = x + x;
}
```

How many times does the loop run?  What's the value of `x` after the while loop?

The loop will run 3 times. The final value of 'x' is 8.

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

The result will end up being 5.

Since neither a or b is greater than 0, the first if statement will not be executed.
This brings us to the statement 'return a - b', or 'return 0 - -5'
Since the rules of arithmetic state that subtracting a negative equates to adding
(or something to that extent - i'm a little rusty on my exact terminology here),
the statement evaluates to return 0 + 5, thus giving us postitive 5 as the final value.


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

The value of teamMember['hobby'] is 'exercise'
The value of teamMember['name'] is {'given': 'Jason', 'surname': 'Weeks'}
The value of teamMember['name']['surname'] is 'Weeks'


hiiiiii chris~
