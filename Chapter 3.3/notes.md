- naming convention in rust is lowercase with underscores
- function definitions start with `fn`
- doesn't matter whether we defined the function before or after calling it in a function
- parameters are defined as follows: `(x: i32, y: char)` with a name and a type
- there are statements and expressions. statements don't return anything while expressions do evaluate and return a value
- a scope with curly brackets is an expression, calling a function is an expression, calling a macro is an expression
- expressions can be part of statements i.e. `let y = {let x = 3; x + 1}` where the part in curly brackets is an expression which evaluates to 4 and gets bound to y
- expressions don't have semicolons at the end. see in the previous example `x + 1`. adding a semicolon at the end of an expression turns it into a statement and won't return a value
- when a function returns something we must declare the type or the return value `fn five() -> i32 { 5 }`
- the important takeaway here is that expressions don't end on semicolons 