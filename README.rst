========================================
Awesome-JIT
========================================

.. contents:: Table of Contents



Libraries
========================================

Help you implement JIT
------------------------------

* `AsmJit <https://github.com/kobalicek/asmjit>`_ -  Complete x86/x64 JIT and Remote Assembler for C++
* `DynASM <http://luajit.org/dynasm.html>`_
* `LibJIT <https://www.gnu.org/software/libjit/>`_
* `LLVM - MCJIT <http://llvm.org/docs/MCJITDesignAndImplementation.html>`_
* `GCC - libgccjit <https://gcc.gnu.org/onlinedocs/jit/>`_
* `GNU lightning <https://www.gnu.org/software/lightning/>`_ - a library that generates assembly language code at run-time
* `Xbyak <https://github.com/herumi/xbyak>`_ - JIT assembler for x86(IA32), x64(AMD64, x86-64) by C++
* `sljit <http://sljit.sourceforge.net/>`_ - a stack-less platform independent JIT compiler
* `QBE <https://c9x.me/compile/>`_ - written in C, similar to LLVM but much smaller
* `MIR <https://github.com/vnmakarov/mir>`_ - a new JIT backend in C being developed by a Redhat GCC maintainer
* `NanoJIT <https://github.com/dibyendumajumdar/nanojit>`_ - a small JIT engine originally written by Adobe for Flash
* `nj <https://github.com/dibyendumajumdar/nj>`_ - a JIT engine written in C++ based on `Eclipse OMR <https://github.com/eclipse/omr>`_. Eclipse OMR is used in IBM's Java implementation, but the JIT engine is generic


Comes with JIT support
------------------------------

* Python
    - `Numba <http://numba.pydata.org/>`_ - NumPy aware dynamic Python compiler using LLVM


Programming Languages Implementation
========================================

* `Julia <https://github.com/JuliaLang/julia>`_
* Python
    - `PyPy <https://bitbucket.org/pypy/pypy>`_
    - `Pyston <https://github.com/dropbox/pyston>`_ - performance-oriented Python implementation built using LLVM and modern JIT techniques
    - `Pyjion <https://github.com/Microsoft/Pyjion>`_ - JIT for Python based upon CoreCLR
* Lua
    - `LuaJIT <https://github.com/LuaJIT/LuaJIT>`_
    - `Ravi <https://github.com/dibyendumajumdar/ravi>`_ - a derivative/dialect of Lua 5.3 with limited optional static typing and an LLVM powered JIT compiler
    - `RaptorJIT <https://github.com/raptorjit/raptorjit>`_ - a fork of LuaJIT focused on predictably high performance.
* JavaScript
    - `V8 <https://github.com/v8/v8>`_
    - `SpiderMonkey <https://developer.mozilla.org/en-US/docs/Mozilla/Projects/SpiderMonkey/Getting_SpiderMonkey_source_code>`_
* PHP
    - `HHVM <http://hhvm.com/>`_
    - `HippyVM <https://github.com/hippyvm/hippyvm>`_
* Ruby
    - `Topaz <https://github.com/topazproject/topaz>`_
* Lisp
    - `CLISP <http://www.clisp.org/>`_
    - `Pixie <https://github.com/pixie-lang/pixie>`_
* Smalltalk
    - `GNU Smalltalk <http://smalltalk.gnu.org/>`_
    - `RSqueak <https://github.com/HPI-SWA-Lab/RSqueak/>`_
* Prolog
    - `Pyrolog <https://bitbucket.org/cfbolz/pyrolog>`_
* `Racket <http://racket-lang.org/>`_
* Java
    - `HotSpot <http://openjdk.java.net/groups/hotspot/>`_
    - `Dalvik <https://source.android.com/devices/tech/dalvik/index.html>`_
    - `Avian <https://readytalk.github.io/avian/>`_ - A lightweight alternative to Java
    - `Jikes RVM <http://www.jikesrvm.org/>`_ - Research Virtual Machine
* Erlang
    - BEAMJIT
* WebAssembly
    - `wasm-jit <https://github.com/indutny/wasm-jit>`_
* LLVM IR
    - `Sulong <https://github.com/graalvm/sulong>`_ - an interpreter for LLVM IR written in Java using the Truffle language implementation framework and Graal as a just-in-time (JIT) compiler
* SOM (Simple Object Machine)
    - `RPySOM <https://github.com/SOM-st/RPySOM>`_ - The Simple Object Machine Smalltalk implemented in RPython
    - `RTruffleSOM <https://github.com/SOM-st/RTruffleSOM>`_ - combining ideas from Truffle and TruffleSOM with RPython's metatracing
* `.NET <https://github.com/dotnet/coreclr>`_
* `ZetaVM <https://github.com/zetavm/zetavm>`_
* Ethereum
    - `EVM JIT <https://github.com/ethereum/evmjit>`_



Bindings
========================================

* `llvmlite <https://github.com/numba/llvmlite>`_ - A lightweight LLVM python binding for writing JIT compilers
* `pygccjit <https://github.com/davidmalcolm/pygccjit>`_ - Python bindings for libgccjit



Tools
========================================

* `jitpy <https://github.com/fijal/jitpy>`_ - Library to embed PyPy into CPython
* `RPython Toolchain <https://rpython.readthedocs.io/en/latest/index.html>`_ - framework for producing implementations of dynamic languages
* `Truffle <https://github.com/graalvm/truffle>`_ - Language Implementation Framework
* `JITWatch <https://github.com/AdoptOpenJDK/jitwatch>`_ - Log analyser and visualiser for the HotSpot JIT compiler



Papers
========================================

* [2003] `A Brief History of Just-In-Time <http://dl.acm.org/citation.cfm?id=857077>`_
* [2010] `OCamlJIT 2.0 - Faster Objective Caml <https://arxiv.org/abs/1011.1783>`_
* [2015] `Pycket: A Tracing JIT For a Functional Language <http://dl.acm.org/citation.cfm?id=2784740>`_
* [2015] `Making an Embedded DBMS JIT-friendly <http://arxiv.org/abs/1512.03207>`_



JIT in Database
========================================

* `PostgreSQL <https://github.com/postgres/postgres>`_
    - ``src/backend/jit``
* SQlite
    - `SQPyte <https://bitbucket.org/softdevteam/sqpyte>`_



Resources
========================================

Twitter
------------------------------

* `@LuaJIT <https://twitter.com/luajit>`_
* `@pypyproject <https://twitter.com/pypyproject>`_
