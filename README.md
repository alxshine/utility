# Miscellaneous command line utilities
This repository contains various utilities I wrote for jobs I need to do often.
They don't have man entries, but I try to give them meaningful help texts.

## silent
Silent is useful if you have long running code that you don't want to monitor.
It can log output to a file as well as stdout, notify you via pushover (using the python-pushover package in the pip repository) and optionally shutdown the computer after it is finished.
Before the shutdown (-s option) you have 5 seconds to cancel it.
Try the helptext *silent -h* for more info.
