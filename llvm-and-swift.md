# LLVM and Swift

Swift is built on the [LLVM Compiler Infrastructure](http://llvm.org/).
Swift uses the LLVM Core for code generation and optimization (among other things), [Clang](http://clang.llvm.org/) for interoperability with C-based languages, and [LLDB](http://lldb.llvm.org/) for debugging and the REPL.

Swift maintains a fork of the [LLVM Core](https://github.com/llvm/llvm-project) source repository on GitHub at [llvm-project](https://github.com/swiftlang/llvm-project).
This repository track upstreams LLVM development and contains additional changes for Swift.
The upstream LLVM repository are merged into the Swift-specific repository frequently.
Every attempt is made to minimize the differences between upstream LLVM and the Swift fork to only those changes specifically required for Swift.

### Where Do LLVM Changes Go?

Swift follows a policy of making a change in the most upstream repository that is feasible.
Contributions to Swift's version of LLVM Project should go directly into the upstream LLVM repository unless they are specific to Swift.
For example, an improvement to LLDB’s data formatters for a Swift type belongs in the Swift fork of the LLVM project, whereas a bug fix to an LLVM optimizer—even if it’s only been observed when operating on Swift-generated LLVM IR—belongs in upstream LLVM.

Commits to an upstream LLVM repository are automatically merged into the appropriate upstream branches in the corresponding Swift repository (`next`) in the [llvm-project](https://github.com/swiftlang/llvm-project).

### Swift and LLVM Developer Policies

Contributions to [llvm-project clone](https://github.com/swiftlang/llvm-project) are governed by the [LLVM Developer Policy](http://llvm.org/docs/DeveloperPolicy.html) and should follow the appropriate [licensing](http://llvm.org/docs/DeveloperPolicy.html#copyright-license-and-patents) and [coding standards](http://llvm.org/docs/CodingStandards.html).
Issues with LLVM code are tracked using the [LLVM bug database](https://github.com/llvm/llvm-project/issues).
For LLDB, changes to files with llvm.org comment headers must go to the [upstream LLDB at llvm.org](https://github.com/llvm/llvm-project/tree/main/lldb) and abide by the [LLVM Developer Policy](http://llvm.org/docs/DeveloperPolicy.html) and [LLDB coding conventions](https://llvm.org/docs/CodingStandards.html).
Contributions to the Swift-specific parts of LLDB (that is, those with a Swift.org comment header) use the [Swift license](https://www.swift.org/community/#license) but still follow the LLDB coding conventions.
