# C#: Phone Number

Write a program that cleans up user-entered phone numbers so that they can be sent SMS messages.

The rules are as follows:

- If the phone number is less than 10 digits assume that it is bad
  number
- If the phone number is 10 digits assume that it is good
- If the phone number is 11 digits and the first number is 1, trim the 1
  and use the last 10 digits
- If the phone number is 11 digits and the first number is not 1, then
  it is a bad number
- If the phone number is more than 11 digits assume that it is a bad
  number

We've provided tests, now make them pass.

Hint: Only make one test pass at a time. Disable the others, then flip
each on in turn after you get the current failing one to pass.

Follow these instructions on how to [get your C# development environment set up][csharp-installation].

The exercises use NUnit. Follow [this guide][nunit-guide] to get started.

[csharp-installation]: https://github.com/exercism/xcsharp/blob/master/docs/INSTALLATION.md
[nunit-guide]: https://github.com/exercism/xcsharp/blob/master/docs/TESTS.md

## Source

Event Manager by JumpstartLab [http://tutorials.jumpstartlab.com/projects/eventmanager.html](http://tutorials.jumpstartlab.com/projects/eventmanager.html)

This exercise is from the [C#][csharp] track on [Exercism][exercism]

[exercism]: http://exercism.io
[csharp]: http://exercism.io/languages/csharp



