# angr_tutorial
The goal is to demonstrate [angr](https://github.com/angr/angr)'s use through a series of examples

1. Symbolizing cmd-line arguments (See `args`)
2. Symbolizing a single integer (See `magic_number`'s `symbolize_int()` )
2. Symbolizing a single string (See `bomb32/phase1`)
3. Symbolizing function arguments
    1. via modifying the stack contents directly (See `bomb32/phase2`)
    2. via `stack_push(symbol)` (See `magic_number`'s `symbolize_stack_param()`)
4. Symbolizing user input (???)
  1. sscanf()
  2. gets()
5. Examining user output (??? state.posix.dumps(1) ?? )
6. Symbolizing files (?? https://docs.angr.io/docs/toplevel.html ??)
