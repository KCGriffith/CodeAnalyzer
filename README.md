# CodeAnalyzer
Code analyzer for CSC 415 presentation assignment

Requirements:
- Visual Studio 2015 or 2017
- .NET Compiler Platform SDK
- Tools > NuGet Package Manager > Package Manager Controls
	- In console: Install-Package Microsoft.CodeAnalysis -Pre
	  NOTE: This will provide the Microsoft.CodeAnalysis libraries

How to test:
- Run TestProject and Visual Studio should load the regex code analyzer from the companion project
  giving a message about "malformed regex" in Visual Studio.