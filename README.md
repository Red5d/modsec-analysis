modsec-analysis
===============

ModSecurity error log analysis in bash.

I realize there are more sophisticated log analysis applications,
but this is meant to be a simple analysis script for if you don't
have a log analysis application or you just want to do a quick check
on something.

I'm working on getting it to return more detailed results and have
more specific filtering and maybe statistical options.

Create a file called "internalips" in the same directory as the script
to enable filtering logs based on whether the client that generated
the event was inside your network or not.

You may also need to adjust the ERROR_LOG and MODSEC_AUDIT_LOG
variables in the script based on where your system puts those files.
