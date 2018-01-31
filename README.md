
# Java 9

## Java Modules
Java modules are builing blocks of [*microservices*](TODO)

## JPMS (Java Platform Module System)

allowing the user to create their modules to develop their applications.

_TODO_

## JLINK

allowing the user to create executable to their applications.

```
jlink [options] --module-path modulepath --add-modules module [,module...]
```

_TODO_

## JDEPS

_TODO_

## JShell
  
  Using Jshell, a program element like statement, declaration or expression can be immediately verified.
  Typically till Java 8, a developer needs atleast IDE help to validate any arbitary logic. 
  Hence JShell gives hand to minimize the above effort.
  
  *_How to Use_*
  
  _Type_ in command prompt, JShell window opens for you.
  
  
## Optional class

 * ifPresent(Consumer action)
 
 * ifPresentOrElse(Consumer action, Runnable emptyAction)
    * eg., ifPresentOrElse(T -> {}, () -> {})

