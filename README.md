
# Code Review Tool

#### Code-Review-as-an-Educational-Service: An Education-oriented Software-as-a-Service Tool for Java Code Review

Accessing the tool : [https://static-code-analyser.azurewebsites.net/](https://static-code-analyser.azurewebsites.net/)


## Introduction

This tool is a solution for detecting and highlighting code quality issues during code review within GitHub repositories  by employing Abstract Syntax Tree (AST) Analysis. The tool aims
to provide a safety net for beginners by guiding them towards implementing industry-standard coding conventions and away from poor-quality code pitfalls, ensuring that learners are
shielded from the effects of working with poor-quality code by highlighting issues and educating developers on appropriate software principles to create standard adhering software. By leveraging AST Analysis, the system will break the source code into pieces allowing, for a detailed examination of
syntax and structure. This tool is designed in a cloud-native fashion and devel- oped as a software-as-a-service solution. As such, there is little configuration work left for using this tool to perform code review tasks.
## Functionalities

#### Calculating cyclomatic complexity of codebase.

#### Identifying coding style issues.
* Checking class and interface naming conventions. 
* Checking variable naming convention.
* Checking usage of Magic numbers.
* Checking indentation consistency.
* Checking brace style.
* Checking the import organisation.
#### Identifying code smells.
* Checking existence of excessive parameters.
* Checking existence of methods with excessive length.
* Checking existence of God class.
* Checking existence of large classes.
* Checking correctness of using try block.
* Checking existence of data clumps.
* Checking existence of methods with primitive obsession.
* Checking correctness of using comments.
* Checking existence of dead methods.
* Checking existence of method chaining.
* Checking exception handling.
#### Identifying security risks.
* Checking existence of deprecated APIs.
* Checking existence of SQL injection.
* Checking existence of cross-site scripting.
* Checking existence of insecure deserialization. 
* Checking existence of hard-coded credentials. 
* Checking existence of race condition.
## Further Information and basic Help

[User Guide](https://github.com/MBeattie02/code_review_tool/blob/main/code_review_tool_documentation/UserManual.pdf)

[Serverside Code](https://github.com/MBeattie02/code_review_tool/tree/main/code_review_server)

[Clientside Code](https://github.com/MBeattie02/code_review_tool/tree/main/code_review_client)
## Version

Version of Software: ![version](https://img.shields.io/badge/version-1.0.0-blue)


## License

[![License](https://img.shields.io/badge/License-BSD_3--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause)

