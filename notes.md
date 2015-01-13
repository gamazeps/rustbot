# 13/01/15

Welle it's 1h40 a.m. so this is a short note.
First I need to know how to have proper controll over my compiliation toolchain.
Thus I start to look at kmcallister article on making a small main program (the one of 151 bytes)

Read the low level part of the Rust Doc, I'll need to dig deeper into this.

Read it, it's quite usefull, saw taht we can have a linker script, this is nice :)
Let's try to do replicate this.

Looked a little at zync : it seems far too bloated (ChibiOS/RT is my ideal) for what I want.
Looked a little at ChibiOS/RT's sources, very clean, good inspiration.

Next steps
Reproduce kmcallister's code.
See how cargo works for my needs (Make may be needed), need to find how to easily pass my linkerscript
