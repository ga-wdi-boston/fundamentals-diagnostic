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

Much like Dropbox, GitHub is a platform used to manage Git repositories. It is
basically a shared repository for developers to share and manage code.

## Question 3

```js
(false || true) && (false && true);
```

Is the value of this expression `true` or `false`?  Explain your answer.

(false || true) = true, and (false && true)= false
false && true = false
Since the first expression equates to true and the second to false; the final
outcome would be false.

## Question 4

```js
var x = 1;
while (x < 5) {
  x = x + x;
}
```

How many times does the loop run?  What's the value of `x` after the while loop?

Loop instances:
1st= x=1+1; x = 2
2nd= x=2+2; x=4
3rd= x=4+4; x=8
Answer= 3 times, x=8

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

var strangeAdd = function(0, -5) {
  if (a > 0 || b > 0) {
    return a + b;
  }
  return a - b;
};
return a-b; 0- (-5); 0+5;
return 5;

## Question 6

```js
var groceryList = [
  'a loaf a bread',
  'a container of milk',
  'a stick of butter',
];
```

What is the value of `groceryList[2]`?

groceryList[2]= 'a stick of butter';

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

`teamMember['hobby']`= 'exercise'
`teamMember['name']`='Jason'
`teamMember['name']['surname']`='Jason''Weeks'
