# latex-log-parser improved#
This is an improved version of the jpallen latex-log-parser, a javascript library intended to parse a log file produced by a LaTeX compilation.



## This version ##
This fork mainly aims to correctly parse the warning and error messages emitted by the dedicated LaTeX commands: 

* \@latex@error{msg}{help}
* \@latex@warning
* \@latex@warning@no@line
* \PackageError{package}{msg}{help}
* \PackageWarning{package}{msg}
* \PackageWarningNoLine{package}{msg}
* \ClassError{class}{msg}{help}
* \ClassWarning{class}{msg}
* \ClassWarningNoLine{class}{msg}
