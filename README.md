# word2pdf
Batch Convert Word Doc/Docx Files to  Files

## Download
Download the latest release [here](releases/latest).

## Bat To Exe Converter
Bat To Exe Converter can convert BAT (.bat) script files to the EXE (.exe) format.

```
::[Bat To Exe Converter]
::
::fBE1pAF6MU+EWHreyHcjLQlHcCW2E0aGIrAP4/z0/9aopEsUV+cLd7///PqLOOVz
::fBE1pAF6MU+EWHreyHcjLQlHcCW2E0aGIrAP4/z0/9aJq18eWeZxfZfeug==
::YAwzoRdxOk+EWAjk
::fBw5plQjdCyDJGyX8VAjFDpgYym+GG6pDaET+NTr6+zJq04SNA==
::YAwzuBVtJxjWCl3EqQJgSA==
::ZR4luwNxJguZRRnk
::Yhs/ulQjdF+5
::cxAkpRVqdFKZSzk=
::cBs/ulQjdF65
::ZR41oxFsdFKZSDk=
::eBoioBt6dFKZSDk=
::cRo6pxp7LAbNWATEpSI=
::egkzugNsPRvcWATEpSI=
::dAsiuh18IRvcCxnZtBNQ
::cRYluBh/LU+EWAjk
::YxY4rhs+aU+JeA==
::cxY6rQJ7JhzQF1fEqQJQ
::ZQ05rAF9IBncCkqN+0xwdVs0
::ZQ05rAF9IAHYFVzEqQJQ
::eg0/rx1wNQPfEVWB+kM9LVsJDGQ=
::fBEirQZwNQPfEVWB+kM9LVsJDGQ=
::cRolqwZ3JBvQF1fEqQJQ
::dhA7uBVwLU+EWDk=
::YQ03rBFzNR3SWATElA==
::dhAmsQZ3MwfNWATElA==
::ZQ0/vhVqMQ3MEVWAtB9wSA==
::Zg8zqx1/OA3MEVWAtB9wSA==
::dhA7pRFwIByZRRnk
::Zh4grVQjdCyDJGyX8VAjFDpgYym+GG6pDaET+NTM4PiD8H05cqw6YIq7
::YB416Ek+ZG8=
::
::
::978f952a14a936cc963da21a135fa983
@echo off

FOR %%f in (*.doc *.docx) DO (
%b2eincfilepath%\nircmd.exe exec hide %b2eincfilepath%\OfficeToPDF.exe /working_dir %b2eincfilepath% "%%f" "%%~nf.pdf"
)
```

## OfficeToPDF
A command line tool to convert Microsoft Office documents to PDFs [[Github](https://github.com/cognidox/OfficeToPDF)]

## NirCmd
NirCmd is a small command-line utility that allows you to do some useful tasks without displaying any user interface. [[Website](http://www.nirsoft.net/utils/nircmd.html)]
