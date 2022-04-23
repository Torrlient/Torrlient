# Torrlient
This repo is a mirror, containing a collection of stuff from Torrlient.com

# Torrlient.com
Is a small scale private datacenter, that provide access to computing resources through Virtual Machine Applications.
We support individual development and growth with ***free*** access to greater computing resources.

## TorrlientVM
This folder contains the source code for "TorrlientVM", a Virtual Machine intended to make it easier to develop Autonomous Virtual Machine Applications.

The purpose of this script is to execute programs only once at reboot, which crontab to my knowledge cannot do. 

We execute this script by name only. To replicate this behaviour use this command: 
```
cp TorrlientVM.py /bin/torrlientvm
```
CLI Options
```
torrlientvm -search
```
```
torrlientvm -init scriptname
```
```
torrlientvm -remove scriptname
```
```
torrlientvm -queue
```
```
torrlientvm -listen
```
```
torrlientvm -run
```

***Note*** This code contain a section with Telemetry that are completely unused. 
