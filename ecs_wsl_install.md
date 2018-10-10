

## Installing and Setting Up the Windows Subsystem for Linux (_WSL_)

### Installing WSL for the 1st Time:

| Step | Steps                                       |  Notes                        |
|:----:|---------------------------------------------|-------------------------------|
| 1    | Go to [START] and type _Store_              |                               |
| 2    | Click on Microsoft Store                    |                               |
| 3    | Click on Search in the top right.           |                               |
| 4    | Search for _Bash_                           |                               |
| 5    | Click on [Get the apps]                     |                               |
| 6    | Click on [Ubuntu]                           |                               |
| 7    | Click on [Get]                              | Wait for Install              |
| 8    | Click on [Launch]                           | Wait for Install              |
| 9    | Type _student_ for username and hit [Enter] |                               |
| 10   | Type _ict_ for password and hit [Enter]     | Nothing will show as you type |
| 11   | Retype _ict_ for password and hit [Enter]   | Nothing will show as you type |


### Installing some compilers on WSL:

_Note: You can copy and past all of these commands._

| Step | Commands                             |  Notes                               |
|:----:|--------------------------------------|--------------------------------------|
| 1    | sudo apt-get update                  | Type this in and hit [Enter]<br />Type your password _ict_ and hit [Enter]  |
| 2    | sudo apt-get upgrade                 | Type this in and hit [Enter]<br />Hit [Enter] when it asks: _Do you want to continue? [Y/n]_  |
| 3    | sudo apt-get install build-essential | Type this in and hit [Enter]<br />Hit [Enter] when it asks: _Do you want to continue? [Y/n]_  |


### Reinstalling _WSL_ because it does not work:

_Note: You can copy and past commands on steps 2 and 3._

| Step | Stemps/Commands                               | Notes                         |
|:----:|-----------------------------------------------|-------------------------------|
| 1    | Left Click on [Start]                         |                               |
| 2    | Click on [Windows PowerShell]                 |                               |
| 3    | lxrun /uninstall /full                        | Type this in and hit [Enter]<br /> Enter _y_ when it asks you to |
| 4    | lxrun /install                                | Type this in and hit [Enter]<br /> Enter _y_ when it asks you to |
| 5    | Type _student_ for username and hit [Enter]   |                               |
| 6    | Type _ict_ for password and hit [Enter]       | Nothing will show as you type |
| 7    | Retype _ict_ for password and hit [Enter]     | Nothing will show as you type |
| 8    | Close Windows PowerShell Down                 |                               |
| 9    | Go to [Start] type in _bash_ and hit [Enter]  |                               |
