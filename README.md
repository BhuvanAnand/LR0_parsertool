LR0_parsertool
==============

a project that implements the stages in a typical LR(0) parser take a input grammar and parse the input for the grammar

a parser typically parse a input string and check whether the input belongs to the grammer.

LR(0) parser - left to right scanning of the input and rightmost derivation of grammar symbols.

LR(0) parser composed of five stages.
      1) finding the FIRST set of grammar symbols.
      2) finding the FOLLOW set of grammar symbols.
      3) from initial state apply the closure rule to find all the possible input states.
      4) construct a parsing table from states obtained by applying closure.
      5) parse the input string by using the parsing table.
      
all the above stages are implemented and the GUI is provided making it as a tool for learning the LR(0) parsing.
each of the above stage outputs can be seen at a click of corresponding button.
