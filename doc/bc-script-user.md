/*

# NAME %Script-Name%

%Script-Name% – %One-line description of this script’s purpose%

## SYNOPSIS

bc [bc options] <**%Script-Name%**
[**--sp-option-1=value**]
[**--sp-option-2=value**]
[**--input=_input-file_**] | [**-i _input-file_**] [**--output=_output-file_**] | [**-o _output-file_**] [**--help**] [**--log=_logfile_**]
[**--man**]
[**--quiet**]
[**--usage**]
[**--debug**]
[**--version**]
[**--verbose**]
[`--`]
[_input-file_ ...]

## DESCRIPTION

A full program user description and its features.

May include numerous subsections, _i.e._, Heading Level 3, Heading Level 4, _etc._).

### System Identification

#### SYSTEM ID

System Identification

#### COMPONENT ID

Component Identificaiton

#### PROGRAM ID

Program ID

## OPTIONS & ARGUMENTS

### Specific Options

Enter options that are specific to **%Script-Name%** here.

* [**--SP-Option-1=value**]

  Specific option 1.

* [**--SP-Option-2=value**]

  Specific option 2.

### Standard Options

* [**--input=_input-file_**] | [**-i _input-file_**]

    Input file, default is standard in, _STDIN_. Single dash, “`-`”, means read from _STDIN_.

* [**--output=_output-file_**] | [**-o _output-file_**]

    Output file, default is standard out, _STDOUT_. Single dash, “`-`”, means write to _STDOUT_.

* [**--help**]

    Print the help message to standard error, _STDERR_, and exit.

* [**--log=_logfile_**]

    Copy all _STDOUT_ and _STDERR_ output to the _logfile_. If _logfile_ is not specified, use _%Program Name%.log_.

* [**--man**]

    Print the man page to standard error, _STDERR_, and exit.

* [**--quiet**]

    Only print fatal error messages to _STDERR_.

* [**--usage**]

    Print the usage message to standard error, _STDERR_, and exit.

* [**--debug**]

    Turn on the debug switch.

* [**--version**]

    Print the version, copyright, and license message to standard error, _STDERR_, and exit.

* [**--verbose**]

    Turn on the verbose switch.

* [`--`] File list marker

    The the double dash, “`--`”, on the command line signals the end options. The remaining items arguments, even if some look like options.

### Arguments

Only file names are allowed to be arguments.
For all other items use options.

* [_input-file_]

    Input file, default is standard in, _STDIN_. Single dash, “`-`”, also means read from _STDIN_.

## SECURITY

**NOTE:** This script runs in user mode.

**WARNING:** No security data resides in this script and is not required for its operation.

## AVAILABILITY

This script is available at 

## EXAMPLES

Insert instructive examples here.

## NOTES & CAVEATS

What additional information would be useful to a user.

## DIAGNOSTICS

A list of every error and warning message that the program can generate
(even the ones that will “never happen”), with a full explanation
of each problem, one or more likely causes, and any suggested remedies.

## EXIT STATUS

What exit codes exist?

## CONFIGURATION AND ENVIRONMENT

No environmental variables were hurt during the development of this program.

## DEPENDENCIES

A list of all of the other programs and libraries that
this program relies upon,
including any restrictions on versions,
part of this program's distribution,
or must be installed separately.

## FILES

A list of the files that are used by this program.

## LANGUAGE

**%Script-Name%** is written for GNU `bc`, a language that supports arbitrary precision numbers.


## STANDARDS

**%Script-Name%** uses GNU extentions to the POSIX P1003.2/D11 draft. See (Nelson 2001).

## VERSION

**%Script-Name%** Version 0.0 Initial Release

## HISTORY

Version 0.0 — Initial Release

## BUGS AND LIMITATIONS

A list of known problems with the module, together with some indication of
whether they are likely to be fixed in an upcoming release.

Also, a list of restrictions on the features the module does provide:
data types that cannot be handled,
performance issues
and the circumstances in which they may arise,
practical limitations on the size of data sets,
special cases that are not (yet) handled, etc.

The initial release usually just has:

* There are no known bugs in this program.

* Please report problems to Mark Jensen.

* Patches are welcome.

## INCOMPATIBILITIES

A list of any known programs and libraries that this program cannot be used in conjunction with.
This may be due to name conflicts in the interface, or competition for system
or program resources, or due to internal limitations of Bash.

## RESOURCES

* Daniel J. Barrett, Richard E. Silverman, and Robert G. Byrnes. 2005. _SSH, the Secure Shell: The Definitive Guide_, 2nd Edition. (Sebastopol: O’Reilly Media)

* Arnold Robbins and Nelson H. F. Beebe. 2005. _Classic Shell Scripting_. (Sebastopol: O’Reilly Media)

## SEE ALSO

**ols_begin**

## LICENSE AND COPYRIGHT

include(license.txt)

## AUTHOR

Mark Jensen  <mark@jensen.net>

*/