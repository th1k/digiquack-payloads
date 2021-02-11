## Create Windows User Account

### This script does the following:
1. Starts Command prompt as Administrator
2. Runs sequence of powershell commands
    * Stores password in a variable
    * Creates new local user account
    * Gives newly created account administrator priviliages
3. Exits Command prompt

> Note: Running time is around 15 seconds(depending on how and length of user name, password or description, etc.)

### Additional options:
- Optionally you can add `-FullName` and `-Description` parameters to give account more believable look: 
`New-LocalUser \"accName\" -Password $pass -FullName \"User name\" -Description \"Description of new account\"`

### Credit
- https://github.com/Michyus
