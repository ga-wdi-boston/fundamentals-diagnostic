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

/Users/grace/wdi/try/

## Question 2

Describe GitHub, **briefly** in your own words.

GitHub is a respository (a folder in the cloud), that saves and keep trakes of your files. It's considerd a source code management system which works on top of Git.

## Question 3

```js
(false || true) && (false && true);
```

Is the value of this expression `true` or `false`?  Explain your answer.

In order to be true both expressions need to be true (&&). First expression evalustes to true since one of the exppression needs to be true ( || = or). The second one evaluates to false, so the whole thing is false.

## Question 4

```js
var x = 1;
while (x < 5) {
  x = x + x;
}
```

How many times does the loop run?  What's the value of `x` after the while loop?

Three times, x= 8

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

no result is passed, since both expressions value to false. a is with 0 not
bigger than 0 and b is with -5 not bigger than 0, so the if statement won't run,
so no return will be passed.

## Question 6

```js
var groceryList = [
  'a loaf a bread',
  'a container of milk',
  'a stick of butter',
];
```

What is the value of `groceryList[2]`?

'a stick of butter';

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

```js
teamMember['hobby']= 'exercise';
teamMember['name']= { given: 'Jason', surname: 'Weeks' };
teamMember['name']['surname']= {'Weeks'};
```
