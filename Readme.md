# smcFanControl

smcFanControl lets the user set a minimum speed for built-in fans. It allows you to increase your minimum fan speed to make your Intel Mac run cooler. In order to not damage your machine, smcFanControl does not let you set a minimum speed to a value below Apple's defaults.

![My image](https://dl.dropboxusercontent.com/u/10430797/smcFanControl_screenshot.png)
** Add "disable setKey_external option" to avoid the SMC min fan speed bug on some OSX86 PC **

## Installing it using Homebrew & Cask

Make sure you have both [Homebrew](http://brew.sh/) and [Cask](http://caskroom.io/) installed. You'll find intructions to install both tools on their respective websites.

After installing Homebrew and Cask, run:

```
$ brew cask install smcfancontrol
```

After that you'll be able to use Spotilight to launch smcFanControl normally. :-)


Requirements: Intel Mac / OS X 10.6 or higher 


Compiled version: http://www.eidac.de/smcfancontrol/smcfancontrol_2_5_2.zip

FAQ / More info: Found in project under "Ressources/*.lproj/F.A.Q.rtf" or included in above .zip

License: GPL 2
