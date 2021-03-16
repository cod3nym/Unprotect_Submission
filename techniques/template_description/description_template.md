# Template Unprotect Techniques

## Authorship information
* Name or nickname: <myname>
* Twitter: https://twitter.com/<yourhandle>
# Website: yourwebsite[.]com
# Linkedin: <yourlinkedinprofile>
# Email: <youremail@yes.com>
  

## Technique Information
* Technique title (required): (e.g: SuspendThread)
* Technique category (required): (e.g: Anti-debugging)
* Technique description (required): The kernel32 SuspendThread function or the NTDLL NtSuspendThread function can be another very effective way to disable user-mode debuggers. This can be achieved by enumerating the threads of a given process, or searching for a named window and opening its owner thread, and then suspending that thread.
* Code snippet: please add the code in a separate file.

## Detection rules
* Please add your rules in separate files.