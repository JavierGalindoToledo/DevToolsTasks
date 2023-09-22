# Special course "Software development tools"

[![Join the chat at https://t.me/+1A3fdKLjmAthZWZi](https://img.shields.io/badge/chat-Telegram-green?logo=telegram)](https://t.me/+1A3fdKLjmAthZWZi)
[![HTML][html-badge]][html]
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

<!-- Instead of Travis (Linux) and Appveyor (Windows) we will use GitHub Actions -->
<!-- [![Build Status](https://travis-ci.org/UNN-ITMM-Software/devtools-course-practice.svg?branch=master)](https://travis-ci.org/UNN-ITMM-Software/devtools-course-practice) -->
<!-- [![Build status](https://ci.appveyor.com/api/projects/status/dd89jfby02tn85p4?svg=true)](https://ci.appveyor.com/project/kirill-kornyakov/devtools-course-practice) -->
[![Build Status](https://github.com/UNN-ITMM-Software/devtools-course-practice/workflows/CI/badge.svg?branch=main)](https://github.com/UNN-ITMM-Software/devtools-course-practice/actions?query=branch%3Amain)
[![codecov](https://codecov.io/gh/UNN-ITMM-Software/devtools-course-practice/branch/main/graph/badge.svg)](https://codecov.io/gh/UNN-ITMM-Software/devtools-course-practice)

 - ННГУ им. Н.И. Лобачевского
 - Институт ИТММ, каф. МОСТ
 - Nizhny Novgorod State University named after N.I. Lobachevsky

## Lab #1: Setting Up the Environment
### Goals
1. Familiarize yourself with the general procedure for accepting laboratory work.
2. Get acquainted with the GitHub + GitHub Actions infrastructure and the development process adopted there (using the example of [Integration Manager Workflow [imworkflow]).
3. Gain basic skills in using tools such as Git, GoogleTest and CMake.
### Tasks
 1. Prepare the working environment.
    - Install and configure all necessary tools.
    - Get source codes, build a project and run existing tests.
    - Enable testing of your project on GitHub Actions.
 2. Implement several unit tests on an existing component
 3. Integrate your changes into the central repository.
    - Send changes as a pull request.
    - Achieve automatic checks on GitHub Actions.
    - Go through a code review.
## Lab #2: Library development using TDD
### Goals
1. Master the practice of Test-Driven Development.
2. Acquire skills in creating CMake build scripts.
3. Get acquainted with an example of coding style in the C++ language using the Google C++ Style Guide as an example.
4. Deepen the following skills:
     - Writing unit tests using the Google Test tool.
     - Interaction with the continuous integration system GitHub Actions.
     - Passing code review on GitHub.
### Tasks
1. Task topic: [Rule 30][rule30]
2. Create a module that implements this functionality. The module will need to have:
     - High-quality API, formatted as a header file.
     - A set of unit tests providing 100% code coverage.
     - Implementation in C++, with the aim of assembling it as a static library.
3. Integrate your code into the main branch of development, passing testing and code review.
## Lab #3: Application Development
### Goals
1. Continue mastering the technique of writing unit tests using Google Test.
2. Get basic skills in using the CTest tool.
3. Practice team development skills using practices such as Collective Ownership.
### Tasks
1. Add another assembly to the CMake project - a console application that allows you to use the class.
2. Create an application class. It should take the same arguments as the main function and return a string that should be printed to the console.
3. Add CTest tests for the binary.
 

<!-- LINKS -->

[chat]:              https://t.me/+1A3fdKLjmAthZWZi
[hall-of-fame]:      https://docs.google.com/spreadsheets/d/11dxBeegDOpkStVuHZJgpatZV4HqxIkdf6H4gnRpclSM/edit?usp=sharing
[labs]:              https://github.com/UNN-ITMM-Software/devtools-course-practice/tree/main/lab-guide
[control-questions]: https://github.com/UNN-ITMM-Software/devtools-course-theory/blob/master/slides/control-questions.md
[theory]:            https://github.com/UNN-ITMM-Software/devtools-course-theory
[html]:              http://unn-itmm-software.github.io/devtools-course-theory/
[html-badge]:        https://img.shields.io/badge/slides-html-blue.svg
[cdash]:             http://my.cdash.org/index.php?project=devtools-course-practice
[imworkflow]:        https://git-scm.com/book/en/v2/Distributed-Git-Distributed-Workflows#Integration-Manager-Workflow
[rule30]:            https://en.wikipedia.org/wiki/Rule_30
