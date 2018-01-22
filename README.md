
# Java 9 vs Java 8

## Optional class

 * ifPresent(Consumer action)
 
 * ifPresentOrElse(Consumer action, Runnable emptyAction)
    * eg., ifPresentOrElse(T -> {}, () -> {})

