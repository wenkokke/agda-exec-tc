# Examples of execTC!
A repository with examples of using the system call primitive execTC.

To run these examples, you need to use the [exec-tc][^exec-tc] branch of Agda, and create a `~/.agda/executables` file, which lists the paths to all executables you want Agda to have access to. For instance, to run the first example, [echo.agda](src/echo.agda), you need to add the following to `~/.agda/executables`:

```bash
/bin/echo
```

We currently have these exciting examples:

  - [echo.agda](src/echo.agda): Hello, World! An example which calls `echo` during type checking!

[^exec-tc]: https://github.com/agda/agda/tree/exec-tc
