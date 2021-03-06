# Click, a Command-line Parsing Package for Python
A talk to be given at the [Python WA](https://www.meetup.com/pythonwa) meetup on
[2021-11-04](https://www.meetup.com/pythonwa/events/281673788/)

## Blurb

Do you prefer to spend your time writing a program, or writing the
interface layer (which handles the command-line options and subcommands,
tests them for validity, opens files, etc.)?

Wouldn't it be great if you could just indicate how your command-line
interface should work and let something else take care of the details?
Good news: Click can do this!  It uses decorators, so as to keep your
interface functions concerned only with business logic, i.e. dealing
with the problem domain.  Click has a large set of classes that make it
easy to specify the type of your command-line options and arguments, and
create custom types if you want.  And it generates online help messages,
which can be enhanced by optional descriptions that you add to your
option specifications.

This talk will give an overview of how to create a Python command-line
tool using setup.py packaging, with entry points.

https://click.palletsprojects.com

## Outline

  1. Introduction
  1. Click rationale
  1. The basics
  1. Options
      1. Boolean options
      1. Options with parameters
      1. Integer options
      1. Counting options
      1. Mandatory options
      1. Choice options
      1. File path options
      1. File handle options
      1. Multi-string options
      1. Password option
      1. Prompting when an option is missing
  1. Positional parameters
      1. Lists of parameters
      1. Variable numbers of parameters
  1. Click types
  1. Subcommands
  1. Contexts
  1. Defaults and the environment
  1. Colours, logging, prompting, exceptions, oh my!
  1. Conclusion
  1. Questions

## Presenter bio

Alastair is a Software Engineer and system administrator by trade.  He has a BSc in Computer Science from Curtin University.

His computer-related interests lie in various areas within his trade; suffice to say that he is a "geek of many colours". :)  Alastair is a die-hard FOSS user and Linux fan.

He is also a freelancer with his own business.  [Warpspace IT](http://www.warpspace.net/) is a consultancy with a fairly broad focus on the technical side of IT.

### Contact

guru@warpspace.net

1300 881744

## Slides

[Python-Click-talk slides.odp](Python-Click-talk slides.odp)
