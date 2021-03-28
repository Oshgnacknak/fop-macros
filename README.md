# FOP Macros

Collection of macros to to help during the FOP exam.
If any macro breaks your typing,
press and release `ctrl + shift + alt` to fix those keys.

## Getting started

1. Install [sxhkd](https://wiki.archlinux.org/index.php/Sxhkd)
and [xdotool](https://wiki.archlinux.org/index.php/Xdotool#Automation).

1. Run `sxhkd -c macros.sxhkd` in the background.

## Macros

### aspekts of oop
`ctrl + shift + alt + a`:
[Four buzz words](https://www.indeed.com/career-advice/career-development/what-is-object-oriented-programming)
professors love to hear.

### filter map
`ctrl + shift + alt + f + m`:
Racket implementation of
[filter map](https://docs.racket-lang.org/reference/pairs.html?q=map#%28def._%28%28lib._racket%2Flist..rkt%29._filter-map%29%29).
You might need to inline `f` (the mapper) and `p` (the predicate).
Remove `f` to get `filter` or `p` to get `map`.

### interface
`ctrl + shift + alt + i`:
Standard [java interface](https://www.w3schools.com/java/java_interface.asp)
with five [methods](https://www.w3schools.com/java/java_methods.asp).

### class
`ctrl + shift + alt + c`:
Standard [java class](https://www.w3schools.com/java/java_classes.asp)
with a lot of boilerplate.

### exception
`ctrl + shift + alt + e`:
Standard [java exception](https://www.tutorialspoint.com/java/java_exceptions.htm)
with a costume [constructor](https://www.w3schools.com/java/java_constructors.asp).

### listitemmethod
`ctrl + shift + alt + l`:
A Method to work with two `ListItem<T>` "pointers" without recursion.
