## `hello_make`

Provide your solution to `hello_bash` as a file in this folder called
`solution.sh`

Write a `Makefile` that tests the solution to `hello_bash` for correctness.

`make build` should copy your solution from your other directory into this one.

`make test` should fail (return a non-zero value) if the program's output has
any difference compared to what is expected, and succeed otherwise.  To do
this, store your program's output in a file, and then use `diff`.

`make clean` should remove any files your directory did not start with
