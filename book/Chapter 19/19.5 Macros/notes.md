-  `macros` differ from `functions` in that they are a way of writing code that writes other code
-  `macros` also offer some additional features that `functions` don't
-  for example, a `macro` can take any number of parameters while a `function` has to declare the number of parameters it takes
-  `macros` are also expanded before the compiler interprets the code so it can implement a `trait` on a given `type` while a `function` can't do that because it gets called at runtime and `traits` need to be implemented at compile time
-  another difference is that `macros` need to be defined or brought into scope before they are called while `functions` can be defined anywhere
-  there are different kinds of macros covered in the code samples
