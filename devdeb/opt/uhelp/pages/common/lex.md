# lex

> Lexical analyzer generator.
> Given the specification for a lexical analyzer, generates C code implementing it.
> Note: on most major OSes, this command is an alias for `flex`.
> More information: <https://manned.org/lex.1>.

- Generate an analyzer from a Lex file, storing it to the file `lex.yy.c`:

`lex {{analyzer.l}}`

- Specify the output file:

`lex -t {{analyzer.l}} > {{analyzer.c}}`

- Compile a C file generated by Lex:

`c99 {{path/to/lex.yy.c}} -o {{executable}}`