# AnsiColor

Support for ANSI colored strings in Julia. Supported in REPL/Shell
environment for both Unix and Mac.

##Using AnsiColor

AnsiColor wraps a string in the ANSI escape sequences used for colorized
text. The style, foreground and backround colors of a string can be set. 

**A simple example:**

```julia
using AnsiColor

println(colorize("Hello World!", "red", background="light_yellow", mode="underline"))
```

**Supported colors available in most environments:**

  - "black"
  - "red"
  - "green"
  - "yellow"
  - "blue"
  - "magenta"
  - "cyan"
  - "white"
  - "default"

  - "light_black"
  - "light_red"
  - "light_green"
  - "light_yellow"
  - "light_blue"
  - "light_magenta"
  - "light_cyan"
  - "light_white"

**Supported text modes:**

  - "default"
  - "bold"
  - "underline"
  - "blink"
  - "swap"
  - "hide"

