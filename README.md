### README for Lab 6

## Authors

Group Members: Garrett Barber, Anna Heltz, and Bailey Smith

## Installation

To install this project, first go to JupyterLab. Then you will need to open a terminal. Then type in "git clone " and paste the url
from github so that you can edit this project.

## Usage

This is a simple program. It takes in 2 inputs. The user's name and their favorite number. Then it will output their
name and favorite number in one line. 

# code

name = input("What is your name?")                                   - this takes the users name as an input
try:                                                                 - this will make sure that the user enters a number
    number = int(input("What is your favorite number?"))             - this takes the users favorite number as an input
except:                                                              - this will make the user enter an integer if they did not at first
    number = int(input("Enter a number"))                            - this will taks users favorite number as an input if they did not at first
print(number, "is their favorite number and", name, "is their name") - this will print the users favorite number and name on one line

## Contributing

To contribute to this repository, first you will need to obtain the link to this project. Then you will need to fork the project. If you want
to alter the code, you will need to submit a pull request. On JupyterLab, once you are in the terminal type "git add ." then "git commit" and then "git push". This will save your work to the original code if the pull request is accepted. 

## License

This is free and unencumbered software released into the public domain.

Anyone is free to copy, modify, publish, use, compile, sell, or
distribute this software, either in source code form or as a compiled
binary, for any purpose, commercial or non-commercial, and by any
means.

In jurisdictions that recognize copyright laws, the author or authors
of this software dedicate any and all copyright interest in the
software to the public domain. We make this dedication for the benefit
of the public at large and to the detriment of our heirs and
successors. We intend this dedication to be an overt act of
relinquishment in perpetuity of all present and future rights to this
software under copyright law.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS BE LIABLE FOR ANY CLAIM, DAMAGES OR
OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT


## Code of Conduct

Our Pledge: In the interest of fostering an open and welcoming environment, we as contributors and maintainers pledge to making participation in our project and our community a harassment-free experience for everyone, regardless of age, body size, disability, ethnicity, gender identity and expression, level of experience, nationality, personal appearance, race, religion, or sexual identity and orientation.


