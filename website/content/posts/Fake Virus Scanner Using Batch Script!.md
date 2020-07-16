---
author: "Ben Spears"
date: 2018-09-11
title: Fake Virus Scanner Using Batch Script!
featuredImg: ""

---

```
@ echo off
title Ben's Virus Scanner
echo loading virus scanner
ping localhost -n 2 >nul
cls
echo loading virus scanner.
ping localhost -n 2 >nul
cls
echo loading virus scanner..
ping localhost -n 2 >nul
cls
echo loading virus scanner...
ping localhost -n 2 >nul
cls
echo loading virus scanner....
ping localhost -n 2 >nul
cls
echo loading virus scanner.....
ping localhost -n 2 >nul
cls
color 0a
echo Virus Scanner Loaded!
ping localhost -n 2 >nul
cls
echo (-----------------------------------------------------------------------------)
echo (-----------------------------------------------------------------------------)
echo (---------------------------Ben's Virus Scanner-------------------------------)
echo (-----------------------------------------------------------------------------)
echo (-----------------------------------------------------------------------------)


set input=
set /p input= Do you want to scan your computer for viruses? Yes or No-
if %input%==yes goto y
if %input%==no goto n

:n
color 04
echo Your computer will not be scanned
pause
echo Virus Scanner will now exit
pause
cls
exit

:y
color 0a
dirc:/s
dir/s
tree c:\
tree 
dir/s
dir/c
pause
cls
echo Two virus' has been found!-

echo delete\quarantine\ignore

set input=
set /p input= What do you want to do with this virus?
if %input%==delete goto d
if %input%==quarantine goto q
if %input%==ignore goto i

:d
cls
echo Ben is now deleting the virus
ping localhost -n 2 >nul
cls
echo Ben is now deleting the virus.
ping localhost -n 2 >nul
cls
echo Ben is now deleting the virus..
ping localhost -n 2 >nul
cls
echo Ben is now deleting the virus...
ping localhost -n 2 >nul
cls
echo Ben is now deleting the virus....
ping localhost -n 2 >nul
cls
echo Ben is now deleting the virus.....
ping localhost -n 2 >nul
cls
echo The Virus has been deleted!
pause
echo Virus Scanner will now exit
pause
cls
exit

:q
cls
echo Scanner is now quarantining the virus
ping localhost -n 2 >nul
cls
echo Scanner is now quarantining the virus.
ping localhost -n 2 >nul
cls
echo Scanner is now quarantining the virus..
ping localhost -n 2 >nul
cls
echo Scanner is now quarantining the virus...
ping localhost -n 2 >nul
cls
echo Scanner is now quarantining the virus....
ping localhost -n 2 >nul
cls
echo Scanner is now quarantining the virus.....
ping localhost -n 2 >nul
cls

echo virus quarantined
pause
echo virus scanner will now exit
pause
cls
exit

:i
cls
echo this virus will no longer appear in virus scans if ignored

echo yes
echo no

set input=
set /p input= do you want to ignore virus?
if %input%==yes goto z
if %input%==no goto x

:z
cls
echo ignoring virus
ping localhost -n 2 >nul
cls
echo ignoring virus.
ping localhost -n 2 >nul
cls
echo ignoring virus..
ping localhost -n 2 >nul
cls
echo ignoring virus...
ping localhost -n 2 >nul
cls
echo ignoring virus....
ping localhost -n 2 >nul
cls
echo ignoring virus.....
ping localhost -n 2 >nul
cls

Echo virus ignored
pause
echo virus scanner will now exit
pause
cls
exit
:x
cls
echo virus scanner will now exit
pause
cls
exit
REM Ben's Virus Scanner
REM This is a fake virus scanner
```