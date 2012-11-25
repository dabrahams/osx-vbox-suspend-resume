Place this directory in /Library/StartupItems and `chown -R
root:wheel` it.  I also renamed the directory VBoxHeadless on my
system, but I'm not convinced that's necessary.

This approach uses a "[deprecated
interface](https://developer.apple.com/library/mac/#documentation/MacOSX/Conceptual/BPSystemStartup/Chapters/StartupItems.html),"
but MacOS doesn't seem to give us another reasonable way to run
something at system shutdown.
