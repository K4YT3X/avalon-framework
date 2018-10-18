# Avalon Framework

## 1.6.0 (October 18, 2018)

1. Restructured the project.
1. Output now follows the Linux output guidelines (stderr, stdout, etc.)
1. Added logging functionality (log to syslog)

## Description

Avalon framework tries to make printing messages and
getting user input easier it includes most UNIX terminal background
and foreground colors.

<b>It includes:</b> 
1. All Linux terminal 16 bit foreground color.
1. All Linux terminal 16 bit background color.
1. Standardized printing for info, warning, debug, error and etc.
1. The ability to log to syslog.

Easiest way to get user True or False input:
~~~~
if Avalon.ask("Question?", True):  # Default is True
    print("True!")
~~~~

#
### Screenshots (To be Updated)
This is how it looks like:
![avlaon_framework](https://user-images.githubusercontent.com/21986859/31029604-56f3a1ec-a520-11e7-94fd-361ff9a43ed3.png)


### Usages Examples (To be Updated)
~~~~
import avalon_framework as avalon

Avalon.info("Output green information here")
Avalon.warning("This outputs yellow bold warnings")
Avalon.error("This prints a red bold error")
Avalon.subLevelTimeInfo("This prints detailed time and grey info")
Avalon.ask("Returns true if user selects y, vice versa")
~~~~