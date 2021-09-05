# AntlrChoke
VS 2022 Preview 3.1 Crashes on Antlr Generated File

Demonstrates VS 2022 Preview 3.1 crashing when viewing the file TSqlParser.cs (Generated from Antlr 4.6.6). Also causes failures on VS 2019 Community. The newer generated file TSqlParser_new.cs does not appear to crash (file was generated from Antlr 4.9.2).

Does not appear to crash if the project is changed to target .NET 5 instead of .NET 6.

## Code Generation
Code was previously generated from the example [here](http://franckgaspoz.fr/en/first-steps-with-antlr4-in-csharp/). Antlr grammar was taken from [here](https://github.com/antlr/grammars-v4/tree/master/sql/tsql).

## Scenario 
Possible situation when someone is upgrading a project from an older version of Antlr and older project to .NET 6, will crash Visual Studio.
