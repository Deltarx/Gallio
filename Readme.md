# ATI
> Current version:
0.0.1v

System and subsystem to run and operate project `DELTAR`. Python scripts run the bulk of computing and error handling while the Electron framework with interface design.
____
:exclamation:
## Warning!
During test please restrict Coms and outbound Connection!

___

## File structure
 * ATI
  * Bin
    - css (css files)
    - html (html files)
    - js  (javascript files)
    * main
        - scripts (Python and other scripts)
        - subsystem (important framework files)
        - system
        - src (other files)
    * src (other files and images)
  * node_modules
  * package-lock.json
  * package.json
  * `readme.md`

### Startup Command
``` python
npm start electron .
```
### test Command

Change `init.html` to `test.html` in `init.js`. then run the Startup Command.

### Error Codes (python Core)
 - Error 100: System error/ Runtime Error
 - Error 101: Python Version Is not upto date (A newer python version is needed to ensure stablity)
 - Error 102: Module Warning (Module Stablity is unstable)
 - Error 103: Module Cannot be found! (Module path may need to be verifed or try rebooting)
 - Error 104: Module Error! (unkown erro has accured)

### Core
#### subsystems 
Main.py is the main program file. It uses ATI.py as a module manager and error handler.
 * Main.py
   * ATI.py
     - datetime module
     - os module 
     - Ui module
     - secert module
     - math module
     - numpy module
     - sklearn module 
     - error handler 
     - Main screen (terminal / cmd)

#### management sys
Since python cannot not have multi threaded processing there 
* Opinion A: Run mathematics systems in c#.
* Opinion B: Built a cluster computing unit.

Opinion A may take long to code but can have multi thread processing, allow upto 6 scripts running at the same time.
Opinion B is more technical challenging to make and maintain but will give a better system performance.

    
