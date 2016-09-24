#Part 01 - JavaScript Quick Start

##1. Basic JavaScript

###Background

• JavaScript means the programming language.

• ECMAScript is the name used by the language specification. Therefore, whenever
referring to versions of the language, people say ECMAScript. The current version
of JavaScript is ECMAScript 5; ECMAScript 6 is currently being developed.

JavaScript enables a programming style that is a mixture of functional programming (higher-order functions; built-in map, reduce, etc.) and object-oriented programming (objects, inheritance).

###Syntax

• ***Statements*** “do things”. A program is a sequence of statements. Here is an example
of a statement, which declares (creates) a variable foo:

```var foo;```

• ***Expressions*** produce values. They are function arguments, the right side of an assignment, etc. Here’s an example of an expression:

```3 * 7```

###Variables and Assignment

Identifiers are names that play various syntactic roles in JavaScript. For example, the
name of a variable is an identifier. Identifiers are case sensitive.

The following identifiers are ***reserved words*** — they are part of the syntax and can’t be used as variable names (including function names and parameter names):

- arguments 

- break 

- case 

- catch

- class 

- const 

- continue 

- debugger

- default 

- delete 

- do 

- else

- enum 

- export 

- extends 

- false

- finally 

- for 

- function 

- if

- implements 

- import 

- in 

- instanceof

- interface 

- let 

- new 

- null

- package 

- private 

- protected 

- public

- return 

- static 

- super 

- switch

- this 

- throw 

- true 

- try

- typeof 

- var 

- void 

- while

The following three identifiers are not reserved words, but you should treat them as if
they were:

- Infinity

- NaN

- undefined

###Values

All values in JavaScript have properties. Each property has a key (or name) and a value. You can think of properties like fields of a record. You use the dot (.) operator to read a property:

```javascript
value.propKey
```

For example, the string 'abc' has the property length:

```javascript
> var str = 'abc';
> str.length
3
```

And you can use it to invoke methods:

```javascript
> 'hello'.toUpperCase()
'HELLO'
```

The two “non-values” ```undefined``` and ```null``` do not have properties.

###Booleans

###Numbers

###Operators

###Strings

###Statements

###Functions

###Exception Handling

###Strict Mode

###Variable Scoping and Closures

###Objects and Constructors

###Arrays

###Regular Expressions

###Math

###Other Functionality of the Standard Library