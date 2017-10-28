---
title: "Code style"
---
When working with the source code of OpenBlox and related projects, please follow this style. The goal of this is consistency.

## C/C++

### File layout

* Comment with license and possible short explanation of file, script, or tool
* Headers
* Macros
* Classes and types
	* Constructors, deconstructors
	* Properties
	* Methods
		* Static first
		* Lua-specific last
	* “Events” (technically properties, but of an event type)
* Function declarations
	* Include variable names
	* Group and order logically
* Global variables
* Function definitions in same order as declarations
* Entry (main)

### Language features

* Do not use OS-specific code in common files.
* Do not mix declarations and code.
* Use `//` for single line comments, not `/* */`.
* Variadic macros are fine, but you must accept at least one argument first, even if it’s just the number of arguments.

### Blocks

* Variable declarations come before the block.
* `{` on same line, with no space preceding.
* `}` on own line, unless continuing statement (`else`, `do while`, etc.).

### Indentation

Indentation is always to use tabulations, never spaces.

### Functions and methods

* Entire declaration on one line.
* Name should be camelCase.
* No space after opening (or closing).
* Functions to be used by Lua should have the prefix `lua_` and start with a lowercase letter (`lua_toString`).
* Internal functions and methods should be prefixed with an underscore (`_addChild`).

### Variables and properties

* Name should be camelCase.
* In declaration of pointers, the `*` is adjacent to type, not variable name (`char*`).
* Internal variables should be prefixed with an underscore, unless defined as private (`_userdata`).

### Keywords

* No space after `if`, `for`, `while`, `switch`.
* Always use `()` with `sizeof`.

### Switch

* Cases blocks (`case theCase: {`).
* Cases should be indented one level past the `switch`.
* Explain any cases that fall through.

### Headers

* Standard headers in alphabetical order.
	* If headers must be included in a specific order (e.g. Windows headers) explain why.
* Local headers after an empty line.
* Place one empty line between headers being used and headers you’re providing definitions for.

### Logical tests

Never test against NULL explicitly. If you’re writing a boolean test, do not write `== true` or `== false`, use `if(val)` or `if(!val)` respectively.
