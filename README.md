# angr_tutorial
The goal is to demonstrate [angr](https://github.com/angr/angr)'s usage through a series of examples

1. Symbolizing cmd-line arguments (See `args`)
2. Symbolizing a single integer (See `magic_number`'s `symbolize_int()` )
2. Symbolizing a single string (See `bomb32/phase1`)
3. Symbolizing function arguments
    1. via modifying the stack contents directly (See `bomb32/phase2`)
    2. via `stack_push(symbol)` (See `magic_number`'s `symbolize_stack_param()`)
4. Symbolizing user input
  1. read() (?? https://github.com/angr/angr-doc/blob/master/examples/fauxware/fauxware.c ??)
  2. sscanf()
  3. gets()
5. Using alternate success conditions
  1. Based on a specific register or memory values
  2. Based on user output (??? state.posix.dumps(1) ?? )
6. Symbolizing files (?? https://docs.angr.io/docs/toplevel.html ??)
