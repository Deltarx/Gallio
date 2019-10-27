# Unix
> Current version:
0.0.1v

System and subsystem to run and operate project `DELTAR`. Python scripts run the bulk of computing and error handling while the Electron framework with interface design.
____
:exclamation:
## Warning!
During test please restrict Coms and outbound Connection!

___

## File structure
 * Unix
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
