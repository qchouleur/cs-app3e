```console
❯ file hello.c
hello.c: c program text, ASCII text
```

To get the preprocessed source code.
`gcc -E hello.c -o hello.i`

```console
❯ file hello.i
hello.i: c program text, ASCII text
```

To get the assembler code.
`gcc -S hello.i -o hello.s`

```console
❯ file hello.s
hello.s: assembler source text, ASCII text
```

To get the object file.
`gcc -c hello.s -o hello.o`

```console
❯ file hello.o
hello.o: Mach-O 64-bit object x86_64
```

To get the executable file.
`gcc -o hello hello.o`

```console
❯ file hello
hello: Mach-O 64-bit executable x86_64
```
