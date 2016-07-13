# What is an Expression?

## Overview

We've used expressions before in our labs without even noticing it! Expressions are what we put inside the curly braces (`{{}}`) inside the DOM - but they can be a lot more powerful than what we have done already.

## Objectives

- Describe expressions
- Using an expression
- Conditionally assign data using the ternary operator
- Create an expression to display length of data

## Express yourself

Anything in between the `{{}}` braces we've been using in our templates is an "expression". We've only been doing *simple* expressions up to this point, just referencing a variable.

However, expressions can be a lot more powerful. We can add, look up indexes/properties in arrays/objects or even use ternary operators (or do most of what we can do in JavaScript, such as `{{ 1 + 1 }}` outputting 2).

### How long?

One common expression that we may use on a day-to-day basis is the length of an array. For instance, we might want to display how many notifications a user has or how many emails they've got. We can do this purely with the `.length` property - much like how we do it in JavaScript!

```html
{{ someArray.length }}
```

It's as simple as that!

### If this.. or that

We can also use a ternary expression. This takes a boolean value and switches what it displays depending if the boolean is true or false.

```html
{{ someArray.length === 0 ? 'No emails!' : 'Lots of emails' }}
```

`No emails!` will be displayed if `someArray.length === 0`. If it isn't equal to zero, `Lots of emails` will be displayed!

<p class='util--hide'>View <a href='https://learn.co/lessons/angular-what-is-an-expression-readme'>Angular What Is An Expression</a> on Learn.co and start learning to code for free.</p>
