# What is an Expression?

## Overview

Let's take a look at expressions. We've used expressions in our labs without even noticing it!

## Objectives

- Describe expressions
- Using an expression
- Conditionally assign data using the ternary operator
- Create an expression to display length of data

## Express yourself

Anything in between the `{{}}` braces we've been using in our templates is an "expression". We've only been doing *simple* expressions up to this point, just referencing a variable.

However, expressions can be a lot more powerful. We can add, look up indexes/properties in arrays/objects or even use ternary operators.

### How long?

One common expression that we may use on a day-to-day basis is the length of an array. For instance, we might want to display how many notifications a user has or how many emails they've got. We can do this purely with the `.length` property - much like how we do it in JavaScript!

```html
{{ someArray.length }}
```

It's as simple as that!

### If this.. or that

We can also use a ternary expression. This takes a boolean value and switches what it displays depending if the boolean is true or false.

```html
{{ someArray.length === 0 && 'No emails!' || 'Lots of emails' }}
```

`No emails!` will be displayed if `someArray.length === 0`. If it isn't equal to zero, `Lots of emails` will be displayed!
>>>>>>> draft
