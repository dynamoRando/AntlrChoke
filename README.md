# AntlrChoke
VS 2022 Preview 3.1 Crashes on Antlr Generated File

Demonstrates VS 2022 Preview 3.1 crashing when viewing the file TSqlParser.cs. Also causes failures on VS 2019 Community. 

Does not appear to crash if the project is changed to target .NET 5 instead of .NET 6.

## Code Generation
Code was previously generated from the example [here](http://franckgaspoz.fr/en/first-steps-with-antlr4-in-csharp/). Antlr grammar was taken from [here](https://github.com/antlr/grammars-v4/tree/master/sql/tsql).
