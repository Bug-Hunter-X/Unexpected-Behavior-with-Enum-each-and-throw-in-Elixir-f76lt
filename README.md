# Elixir Enum.each and throw Exception

This example demonstrates a potential issue when using `Enum.each` with `throw` in Elixir.  Improper handling of exceptions thrown within `Enum.each` can lead to unexpected behavior. 

The `bug.ex` file shows the problem.  The solution, `bugSolution.ex`, demonstrates a more robust approach.