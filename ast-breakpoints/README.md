# AST Breakpoints



## Demo

The [demo video](demo.mp4) showcases how AST Breakpoints work.

On the left you can see an editor and on the right the debugger.
The debugger has a breakpoint set on `myCoolFunction` function body.

In the editor, we then swap the functions so `myCoolFunction` is not as the same place
in the file anymore. The page then refreshes, and you can observe that the breakpoint
intelligently stays on `myCoolFunction`, as opposed to traditional breakpoints that
would have sticked to the same line.
