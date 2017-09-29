This contains 3 test modules. 

Loading the master module correctly sets environment variable `TESTVAR`
```
$ module load testmaster
$ echo $TESTVAR
```
But loading it again gives a cryptic error:
```
$module load testmaster
Lmod Warning:  /qhome/ns5bc/code/modulefiles/test/test: (test/test): can't read "env(APP_DIR)": no such variable 
While processing the following module(s):
    Module fullname        Module Filename
    ---------------        ---------------
    test/test              /qhome/ns5bc/code/modulefiles/test/test
    testmaster/testmaster  /qhome/ns5bc/code/modulefiles/testmaster/testmaster
```