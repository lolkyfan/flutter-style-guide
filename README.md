# Flutter Style Guide

## Table of Contents
* [File Names](#file-names)
* [App Code Strucuter](#app-code-structure)
  * [Presentation Layer](#presentation-layer)

### File Names
Source file names should be lowercase, with words separated by underscores as necessary to improve readability. Source files end with a `.dart` extension.

Examples:
- A file containing a single class `MyClass` is named `my_class.dart`
- A barrel file containing source file exports is named after a prulalized common ancestor name (if possible) like `models.dart`

## App Code Structure

### Presentation Layer
Top level widgets should have suffix `Page`. Examples are `HomePage`, `LoginPage`. These page widgets usually contain scaffold with an app bar or navigation bar and body.
