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

Answer:
/Users/grace/wdi/try

## Question 2

Describe GitHub, **briefly** in your own words.

Answer:
GitHub is a remote repository where I can store projects, track versions, and collaborate with others.

## Question 3

```js
(false || true) && (false && true);
```

Is the value of this expression `true` or `false`?  Explain your answer.

Answer:
False

## Question 4

```js
var x = 1;
while (x < 5) {
  x = x + x;
}
```

How many times does the loop run?  What's the value of `x` after the while loop?

Answer:
The loop will run 3 times. After the loop, the value of x will be 8.

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

Answer:
The arguments in this function indicate that a = 0 and b = -5. Since both of these values are less than zero, we will skip the if statement. The function will return a - b = 0 - (-5) = 5.

## Question 6

```js
var groceryList = [
  'a loaf a bread',
  'a container of milk',
  'a stick of butter',
];
```

What is the value of `groceryList[2]`?

Answer:
The value of `groceryList[2]` is 'a stick of butter'.

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

Answer:
teamMember['hobby'] = 'exercise'
teamMember['name'] = [object Object]
                    {
                      given: "Jason",
                      surname: "Weeks"
                    }
teamMember['name']['surname'] = "Weeks"
