
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


## Optional class

 * ifPresent(Consumer action)
 
 * ifPresentOrElse(Consumer action, Runnable emptyAction)
    * eg., ifPresentOrElse(T -> {}, () -> {})

