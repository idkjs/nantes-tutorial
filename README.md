# [Nantes Tutorial](https://www.linux-nantes.org/~fmonnier/OCaml/ocaml-wrapping-c.html)

Run `ocamlopt -o hello.opt hello.ml hello_stubs.c` for .ml file.

For reason: compile with `ocamlc -o hello -pp "refmt -p ml" -impl hello.re`
For reason: compile with `ocamlopt -o hello.opt hello.ml hello_stubs.c`
