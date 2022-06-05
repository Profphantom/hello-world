# Bandit Wargames
## Lvl 0 - 1
### CODE(Bold)
**ssh bandit0@bandit.labs.overthewire.org -p 2220**

**cat readme**

*cleared with given passcode and generates passcode for lvl 1* 
 
**boJ9jbbUNNfktd78OOpsqOltutMc3MY1**

## Lvl 1 - 2
### CODE(Bold)
**ssh bandit1@bandit.labs.overthewire.org -p 2220**

*Accessed with passcode from above*


**cat < -**


*Generates passcode for lvl 2* **CV1DtqXWVFXTvM2F0k09SHz0YwRINYA9**

## Lvl 2 - 3
### CODE(Bold)
**ssh bandit2@bandit.labs.overthewire.org -p 2220**


*Accessed with passcode from above*


**cat  spaces\ in\ this\ filename**


*Generates passcode for lvl 3*

**UmHadQclWmgdLOKQ3YNgjWxGoRMb5luK**

## Lvl 3 - 4
### CODE(Bold)
**ssh bandit3@bandit.labs.overthewire.org -p 2220**


*Accessed with passcode from above*


**cd inhere**


**ls -a** *this gives the name of hidden file '.hidden'*


**cat .hidden**


*Generates passcode for lvl 4* **pIwrPrtPN36QITSp3EQaw936yaFoFgAB**



## Lvl 4 - 5
### CODE(Bold)
**ssh bandit4@bandit.labs.overthewire.org -p 2220**


*Accessed with passcode from above*


**cd inhere**


**ls** *this gives the list of directories {'-maybehere00','-maybehere01'---} one of these directories contains the required file*


**file ./-file*** *This will give the details about the files the one corresponding to ASCII is the required file*


**cat < -file07**


*Generates passcode for lvl 5*


**koReBOKuIDDepwhWk7jZC0RTdopnAYKh**

## Lvl 5 - 6
### CODE(Bold)
**ssh bandit5@bandit.labs.overthewire.org -p 2220**


*Accessed with passcode from above*


**cd inhere**


**find . -size 1033c \! -executable** *this gives a file which has 1033 bytes and is not executable*


**cat ./maybehere07/.file2**


*Generates passcode for lvl 6* **DXjZPULLxYr17uwoI01bNLQbtFemEgo7**

## Lvl 6 - 7
### CODE(Bold)
**ssh bandit6@bandit.labs.overthewire.org -p 2220**


*Accessed with passcode from above*


**find / -user bandit7 -group bandit6 -size 33c** *This gives a number of file but majority have denied access*


**cat /var/lib/dpkg/info/bandit7.password**


*Generates passcode for lvl 7* **HKBPTKQnIay4Fw76bEy8PVxKEDQRKTzs**



## Lvl 7 - 8
### CODE(Bold)
**ssh bandit7@bandit.labs.overthewire.org -p 2220**


*Accessed with passcode from above*


**grep millionth data.txt** *text after millionth*


*Generates passcode for lvl 8* 


**cvX2JJa4CFALtqS87jk27qwqGhBM9plV**

## Lvl 8 - 9
### CODE(Bold)
**ssh bandit8@bandit.labs.overthewire.org -p 2220**


*Accessed with passcode from above*


**sort data.txt | uniq -u** *it separates unique data line from the whole mess*


*Generates passcode for lvl 9*


**UsvVyFSfZZWbi6wgC7dAFyFuR6jQQUhR**

## Lvl 9 - 10
### CODE(Bold)
**ssh bandit9@bandit.labs.overthewire.org -p 2220**


*Accessed with passcode from above*


**strings data.txt | grep ==** *stings seperates redable stuff from the data and grep ensures that the data that is returned is precededby ==*


*Generates passcode for lvl 10* **truKLdjsbJ5g7yyJ2X2R0o3a5HQJFuLk**


## Lvl 10 - 11
### CODE(Bold)
**ssh bandit10@bandit.labs.overthewire.org -p 2220**


*Accessed with passcode from above*


**base64 -d data.txt** *it decodes the data giving the passcode*


*Generates passcode for lvl 11* **IFukwKGsFW8MOq3IRFqrxE1hxTNEbUPR**









