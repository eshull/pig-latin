# Pig Latin generator

#### A program that allows users to input a word and outputs its pig latin version. 6/6/18

#### By **Craig Wann and Eric **

## Description

A website created with C# and HTML where a user can submit a word and determine its raw Scrabble score.


### Specs
| Spec | Input | Output |
| :-------------     | :------------- | :------------- |
| **word begins with vowel** | User Input: "under" |  Output: "underWay" |
| **word begins with consonant** | User Input: "dog |  Output: "ogDay" |
| **word begins with multi-consonants **| User Input: "strong" | Output: "pantspants" |
| **word begins with "Y"**| Input: "you" | Output: "ouYay" |
| **word begins with "QU"** | Input: "queen" | Output: "eenQuay" |

## Setup/Installation Requirements

1. To run this program, you must have a C# compiler. I use [Mono](http://www.mono-project.com).
2. Install the [Nancy](http://nancyfx.org/) framework to use the view engine. Follow the link for installation instructions.
3. Clone this repository.
4. Open the command line--I use PowerShell--and navigate into the repository. Use the command "dnx kestrel" to start the server.
5. On your browser, navigate to "localhost:5004" and enjoy!

## Known Bugs
* No known bugs at this time.

## Technologies Used
* C#
  * Nancy framework
  * Razor View Engine
  * ASP.NET Kestrel HTTP server
  * xUnit

* HTML

## Support and contact details

_Email no one with any questions, comments, or concerns._

### License

*{This software is licensed under the MIT license}*

Copyright (c) 2018 **_{Craig & Eric}_**
