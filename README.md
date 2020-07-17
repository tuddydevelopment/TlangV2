# TlangV2
New, turing complete version of Tlang (not TlanG, they are entirely different), which is quite similar to assembly.

Every variable and function is, once defined, globally accessible, this is a static language, there are no objects. I made this language quite similar to assembly, but a little easier and better to understand (functions and variables). This is also why a lot of functions dont require arguments and read from the global buffers. (main, a and b)


`java -jar TlangC.jar <file> <[enableDebugCompilation]>`
  to compile, outputs binary to <file>.bin

`java -jar Tlang.jar <file>`
  to run, only reads binary

`java -jar TlangD.jar <file>`
  to debug-run, only reads binary


(look at [tudbut/TlangV2-Utils](https://github.com/tudbut/TlangV2-Utils) for some pre-made functions)

To run the demos, download the compiler and the runner, then compile the program, it is not pre-compiled.
