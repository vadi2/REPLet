# REPLet - the Mudlet Lua REPL

This package replicates the functionality of the `lua` alias inside its own UserWindow
It comes with a single alias, `replet`, which opens the REPLet console. From there, you can execute arbitrary lua code and see the results in the console.

Once you have the console open, you can type `usage` within the console for the extra commands which REPLet comes with, in addition to executing code.

By default, adds `recho(msg)`, `rcecho(msg)` etc to allow for easy c/d/h/echoing directly to the console. If this covers over functions you already have and want to use in the console, use `addEchos false` in the REPLet console's command line.