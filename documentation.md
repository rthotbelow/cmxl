Welcome to documentation
=========================
1. Getting Started
2. Actual Documentation
3. Not actually added yet but more like a work in progress

## Getting Started
We'll start with a simple hello world application.
```
log "hello world"
```
Seems simple right?

## Actual Documentation
* `log <arg>` = `log "hello world"` This prints a string.
* `##<arg>` = `##testcomment` These are comments, they are useful for pointing things out.

## Not actually added yet but more like a work in progress
* `import <arg>` = `import "testmodule"` This imports a module.
*
```
                                                         ##|
                                                         ##V
                                               ##The string is optional
func <arg><arg1> {                  func "testfunction"(string1) {
                           =        
}                                   }
``` 
This creates a new function.
* `call <arg><arg1>` = `call testfunction "123"` This executes the given function. **The string is optional**
