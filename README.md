# JDWP exploitation script


## What is it ?
This exploitation script is meant to be used by pentesters against active JDWP service, in order to gain Remote Code Execution.

## How does it work ?
Base on https://github.com/IOActive/jdwp-shellifier .
Thanks for @_hugsy_

usage: poc.py [-h] -t IP [-p PORT] [-c COMMAND]
poc.py: error: argument -t/--target is required

## What is new ?
Added a new way to execute commands, study from [MSF exploit](https://github.com/rapid7/metasploit-framework/blob/master/modules/exploits/multi/misc/java_jdwp_debugger.rb). In this way you can execute the command immediately instead of waiting for a breakpoint event.  
![demo](https://github.com/Lz1y/jdwp-shellifier/blob/master/POC.gif?raw=true)
## Useful link
https://docs.oracle.com/en/java/javase/11/docs/specs/jpda/architecture.html
https://docs.oracle.com/en/java/javase/11/docs/specs/jpda/jpda.html
https://docs.oracle.com/en/java/javase/11/docs/specs/jdwp/jdwp-spec.html
https://docs.oracle.com/en/java/javase/11/docs/specs/jdwp/jdwp-protocol.html
https://github.com/IOActive/jdwp-shellifier
https://github.com/rapid7/metasploit-framework/blob/master/modules/exploits/multi/misc/java_jdwp_debugger.rb
