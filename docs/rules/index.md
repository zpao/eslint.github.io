---
title: ESLint
layout: doc
---
<!-- Note: No pull requests accepted for this file. See README.md in the root directory for details. -->
# Rules

Rules in ESLint are divided into several categories to help you better understand their value. Additionally, not all rules are enabled by default. Those that are not enabled by default are marked as being off.

## Possible Errors

The following rules point out areas where you might have made mistakes.

* [no-comma-dangle](no-comma-dangle.html) - disallow trailing commas in object literals
* [no-cond-assign](no-cond-assign.html) - disallow assignment in conditional expressions
* [no-console](no-console.html) - disallow use of `console` (off by default in the node environment)
* [no-constant-condition](no-constant-condition.html) - disallow use of constant expressions in conditions
* [no-control-regex](no-control-regex.html) - disallow control characters in regular expressions
* [no-debugger](no-debugger.html) - disallow use of `debugger`
* [no-dupe-keys](no-dupe-keys.html) - disallow duplicate keys when creating object literals
* [no-empty](no-empty.html) - disallow empty statements
* [no-empty-class](no-empty-class.html) - disallow the use of empty character classes in regular expressions
* [no-ex-assign](no-ex-assign.html) - disallow assigning to the exception in a `catch` block
* [no-extra-boolean-cast](no-extra-boolean-cast.html) - disallow double-negation boolean casts in a boolean context
* [no-extra-parens](no-extra-parens.html) - disallow unnecessary parentheses (off by default)
* [no-extra-semi](no-extra-semi.html) - disallow unnecessary semicolons
* [no-func-assign](no-func-assign.html) - disallow overwriting functions written as function declarations
* [no-inner-declarations](no-inner-declarations.html) - disallow function or variable declarations in nested blocks
* [no-invalid-regexp](no-invalid-regexp.html) - disallow invalid regular expression strings in the `RegExp` constructor
* [no-irregular-whitespace](no-irregular-whitespace.html) - disallow irregular whitespace outside of strings and comments
* [no-negated-in-lhs](no-negated-in-lhs.html) - disallow negation of the left operand of an `in` expression
* [no-obj-calls](no-obj-calls.html) - disallow the use of object properties of the global object (`Math` and `JSON`) as functions
* [no-regex-spaces](no-regex-spaces.html) - disallow multiple spaces in a regular expression literal
* [no-reserved-keys](no-reserved-keys.html) - disallow reserved words being used as object literal keys (off by default)
* [no-sparse-arrays](no-sparse-arrays.html) - disallow sparse arrays
* [no-unreachable](no-unreachable.html) - disallow unreachable statements after a return, throw, continue, or break statement
* [use-isnan](use-isnan.html) - disallow comparisons with the value `NaN`
* [valid-jsdoc](valid-jsdoc.html) - Ensure JSDoc comments are valid (off by default)
* [valid-typeof](valid-typeof.html) - Ensure that the results of typeof are compared against a valid string

## Best Practices

These are rules designed to prevent you from making mistakes. They either prescribe a better way of doing something or help you avoid footguns.

* [block-scoped-var](block-scoped-var.html) - treat `var` statements as if they were block scoped (off by default)
* [complexity](complexity.html) - specify the maximum cyclomatic complexity allowed in a program (off by default)
* [consistent-return](consistent-return.html) - require `return` statements to either always or never specify values
* [curly](curly.html) - specify curly brace conventions for all control statements
* [default-case](default-case.html) - require `default` case in `switch` statements (off by default)
* [dot-notation](dot-notation.html) - encourages use of dot notation whenever possible
* [eqeqeq](eqeqeq.html) - require the use of `===` and `!==`
* [guard-for-in](guard-for-in.html) - make sure `for-in` loops have an `if` statement (off by default)
* [no-alert](no-alert.html) - disallow the use of `alert`, `confirm`, and `prompt`
* [no-caller](no-caller.html) - disallow use of `arguments.caller` or `arguments.callee`
* [no-div-regex](no-div-regex.html) - disallow division operators explicitly at beginning of regular expression (off by default)
* [no-else-return](no-else-return.html) - disallow `else` after a `return` in an `if` (off by default)
* [no-empty-label](no-empty-label.html) - disallow use of labels for anything other then loops and switches
* [no-eq-null](no-eq-null.html) - disallow comparisons to null without a type-checking operator (off by default)
* [no-eval](no-eval.html) - disallow use of `eval()`
* [no-extend-native](no-extend-native.html) - disallow adding to native types
* [no-extra-bind](no-extra-bind.html) - disallow unnecessary function binding
* [no-fallthrough](no-fallthrough.html) - disallow fallthrough of `case` statements
* [no-floating-decimal](no-floating-decimal.html) - disallow the use of leading or trailing decimal points in numeric literals (off by default)
* [no-implied-eval](no-implied-eval.html) - disallow use of `eval()`-like methods
* [no-iterator](no-iterator.html) - disallow usage of `__iterator__` property
* [no-labels](no-labels.html) - disallow use of labeled statements
* [no-lone-blocks](no-lone-blocks.html) - disallow unnecessary nested blocks
* [no-loop-func](no-loop-func.html) - disallow creation of functions within loops
* [no-multi-spaces](no-multi-spaces.html) - disallow use of multiple spaces
* [no-multi-str](no-multi-str.html) - disallow use of multiline strings
* [no-native-reassign](no-native-reassign.html) - disallow reassignments of native objects
* [no-new](no-new.html) - disallow use of new operator when not part of the assignment or comparison
* [no-new-func](no-new-func.html) - disallow use of new operator for `Function` object
* [no-new-wrappers](no-new-wrappers.html) - disallows creating new instances of `String`,`Number`, and `Boolean`
* [no-octal](no-octal.html) - disallow use of octal literals
* [no-octal-escape](no-octal-escape.html) - disallow use of octal escape sequences in string literals, such as `var foo = "Copyright \251";`
* [no-process-env](no-process-env.html) - disallow use of `process.env` (off by default)
* [no-proto](no-proto.html) - disallow usage of `__proto__` property
* [no-redeclare](no-redeclare.html) - disallow declaring the same variable more then once
* [no-return-assign](no-return-assign.html) - disallow use of assignment in `return` statement
* [no-script-url](no-script-url.html) - disallow use of javascript: urls.
* [no-self-compare](no-self-compare.html) - disallow comparisons where both sides are exactly the same (off by default)
* [no-sequences](no-sequences.html) - disallow use of comma operator
* [no-throw-literal](no-throw-literal.html) - restrict what can be thrown as an exception (off by default)
* [no-unused-expressions](no-unused-expressions.html) - disallow usage of expressions in statement position
* [no-void](no-void.html) - disallow use of `void` operator (off by default)
* [no-warning-comments](no-warning-comments.html) - disallow usage of configurable warning terms in comments - e.g. `TODO` or `FIXME` (off by default)
* [no-with](no-with.html) - disallow use of the `with` statement
* [radix](radix.html) - require use of the second argument for `parseInt()` (off by default)
* [vars-on-top](vars-on-top.html) - requires to declare all vars on top of their containing scope (off by default)
* [wrap-iife](wrap-iife.html) - require immediate function invocation to be wrapped in parentheses (off by default)
* [yoda](yoda.html) - require or disallow Yoda conditions

## Strict Mode

These rules relate to using strict mode.

* [global-strict](global-strict.html) - **(deprecated)** require or disallow the `"use strict"` pragma in the global scope (off by default in the node environment)
* [no-extra-strict](no-extra-strict.html) - **(deprecated)** disallow unnecessary use of `"use strict";` when already in strict mode
* [strict](strict.html) - controls location of Use Strict Directives

## Variables

These rules have to do with variable declarations.

* [no-catch-shadow](no-catch-shadow.html) - disallow the catch clause parameter name being the same as a variable in the outer scope (off by default in the node environment)
* [no-delete-var](no-delete-var.html) - disallow deletion of variables
* [no-label-var](no-label-var.html) - disallow labels that share a name with a variable
* [no-shadow](no-shadow.html) - disallow declaration of variables already declared in the outer scope
* [no-shadow-restricted-names](no-shadow-restricted-names.html) - disallow shadowing of names such as `arguments`
* [no-undef](no-undef.html) - disallow use of undeclared variables unless mentioned in a `/*global */` block
* [no-undef-init](no-undef-init.html) - disallow use of undefined when initializing variables
* [no-undefined](no-undefined.html) - disallow use of `undefined` variable (off by default)
* [no-unused-vars](no-unused-vars.html) - disallow declaration of variables that are not used in the code
* [no-use-before-define](no-use-before-define.html) - disallow use of variables before they are defined

## Node.js

These rules are specific to JavaScript running on Node.js.

* [handle-callback-err](handle-callback-err.html) - enforces error handling in callbacks (off by default) (on by default in the node environment)
* [no-mixed-requires](no-mixed-requires.html) - disallow mixing regular variable and require declarations (off by default) (on by default in the node environment)
* [no-new-require](no-new-require.html) - disallow use of new operator with the `require` function (off by default) (on by default in the node environment)
* [no-path-concat](no-path-concat.html) - disallow string concatenation with `__dirname` and `__filename` (off by default) (on by default in the node environment)
* [no-process-exit](no-process-exit.html) - disallow `process.exit()` (on by default in the node environment)
* [no-restricted-modules](no-restricted-modules.html) - restrict usage of specified node modules (off by default)
* [no-sync](no-sync.html) - disallow use of synchronous methods (off by default)

## Stylistic Issues

These rules are purely matters of style and are quite subjective.

* [indent](indent.html) - this option sets a specific tab width for your code (off by default)
* [brace-style](brace-style.html) - enforce one true brace style (off by default)
* [camelcase](camelcase.html) - require camel case names
* [comma-spacing](comma-spacing.html) - enforce spacing before and after comma
* [comma-style](comma-style.html) - enforce one true comma style (off by default)
* [consistent-this](consistent-this.html) - enforces consistent naming when capturing the current execution context (off by default)
* [eol-last](eol-last.html) - enforce newline at the end of file, with no multiple empty lines
* [func-names](func-names.html) - require function expressions to have a name (off by default)
* [func-style](func-style.html) - enforces use of function declarations or expressions (off by default)
* [key-spacing](key-spacing.html) - enforces spacing between keys and values in object literal properties
* [max-nested-callbacks](max-nested-callbacks.html) - specify the maximum depth callbacks can be nested (off by default)
* [new-cap](new-cap.html) - require a capital letter for constructors
* [new-parens](new-parens.html) - disallow the omission of parentheses when invoking a constructor with no arguments
* [no-array-constructor](no-array-constructor.html) - disallow use of the `Array` constructor
* [no-inline-comments](no-inline-comments.html) - disallow comments inline after code (off by default)
* [no-lonely-if](no-lonely-if.html) - disallow if as the only statement in an else block (off by default)
* [no-mixed-spaces-and-tabs](no-mixed-spaces-and-tabs.html) - disallow mixed spaces and tabs for indentation
* [no-multiple-empty-lines](no-multiple-empty-lines.html) - disallow multiple empty lines (off by default)
* [no-nested-ternary](no-nested-ternary.html) - disallow nested ternary expressions (off by default)
* [no-new-object](no-new-object.html) - disallow use of the `Object` constructor
* [no-space-before-semi](no-space-before-semi.html) - disallow space before semicolon
* [no-spaced-func](no-spaced-func.html) - disallow space between function identifier and application
* [no-ternary](no-ternary.html) - disallow the use of ternary operators (off by default)
* [no-trailing-spaces](no-trailing-spaces.html) - disallow trailing whitespace at the end of lines
* [no-underscore-dangle](no-underscore-dangle.html) - disallow dangling underscores in identifiers
* [no-wrap-func](no-wrap-func.html) - disallow wrapping of non-IIFE statements in parens
* [one-var](one-var.html) - allow just one var statement per function (off by default)
* [operator-assignment](operator-assignment.html) - require assignment operator shorthand where possible or prohibit it entirely (off by default)
* [padded-blocks](padded-blocks.html) - enforce padding within blocks (off by default)
* [quote-props](quote-props.html) - require quotes around object literal property names (off by default)
* [quotes](quotes.html) - specify whether double or single quotes should be used
* [semi](semi.html) - require or disallow use of semicolons instead of ASI
* [sort-vars](sort-vars.html) - sort variables within the same declaration block (off by default)
* [space-after-function-name](space-after-function-name.html) - **(deprecated)** require a space after function names (off by default)
* [space-after-keywords](space-after-keywords.html) - require a space after certain keywords (off by default)
* [space-before-blocks](space-before-blocks.html) - require or disallow space before blocks (off by default)
* [space-before-function-parentheses](space-before-function-parentheses.html) - require or disallow space before function parentheses (off by default)
* [space-in-brackets](space-in-brackets.html) - require or disallow spaces inside brackets (off by default)
* [space-in-parens](space-in-parens.html) - require or disallow spaces inside parentheses (off by default)
* [space-infix-ops](space-infix-ops.html) - require spaces around operators
* [space-return-throw-case](space-return-throw-case.html) - require a space after `return`, `throw`, and `case`
* [space-unary-ops](space-unary-ops.html) - Require or disallow spaces before/after unary operators (words on by default, nonwords off by default)
* [spaced-line-comment](spaced-line-comment.html) - require or disallow a space immediately following the `//` in a line comment (off by default)
* [wrap-regex](wrap-regex.html) - require regex literals to be wrapped in parentheses (off by default)

## ECMAScript 6

These rules are only relevant to ES6 environments and are off by default.

* [no-var](no-var.html) - require `let` or `const` instead of `var` (off by default)
* [generator-star](generator-star.html) - enforce the position of the `*` in generator functions (off by default)

## Legacy

The following rules are included for compatibility with [JSHint](http://jshint.com/) and [JSLint](http://jslint.com/). While the names of the rules may not match up with the JSHint/JSLint counterpart, the functionality is the same.

* [max-depth](max-depth.html) - specify the maximum depth that blocks can be nested (off by default)
* [max-len](max-len.html) - specify the maximum length of a line in your program (off by default)
* [max-params](max-params.html) - limits the number of parameters that can be used in the function declaration. (off by default)
* [max-statements](max-statements.html) - specify the maximum number of statement allowed in a function (off by default)
* [no-bitwise](no-bitwise.html) - disallow use of bitwise operators (off by default)
* [no-plusplus](no-plusplus.html) - disallow use of unary operators, `++` and `--` (off by default)
