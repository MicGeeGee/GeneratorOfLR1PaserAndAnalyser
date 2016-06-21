# GeneratorOfLR1PaserAndAnalyser

It is just a introduction page.
This project is about a generator of LR1 parser and analyser, which, in other words, work for generating LR1-based compiler.

The repositories could be refer to the link:https://github.com/CMinusCompiler .

To comprise a compiler, there are a lexer, a parser and an analyser needed. In this project, lexer generating is not automatic,
that is, the lexer here is fixed. But the generating work for parsers and analysers is automatic.

For LR1-Parser generator, the inputs are grammar descriptions and the output is a LR1 table.
For LR1-Analyser generator, the inputs are LR1 table, source code and LR1-inductive rules, and the output is a list of quads
(target of compiled source code).
