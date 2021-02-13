## Wabbit Attack (Fork Bomb)
### This script does the following:
1. Start Command Prompt (CMD)
2. Resize and change color of Command Prompt
3. Execute wabbit

## Persistent Wabbit Attack
### This script does the following:
1. Start Command Prompt (CMD)
2. Create foo.bat in Windows Startup Directory
3. Exit

# Additional Information:
- The `for /l %%x in (0, 0, 0) do start` command will run indefinitely.
- If you want to limit number of cmd instances change it like this: ```for /l %%x in (1, 1, 10) do start``` (this will start 10 instances)
- When using Persistent Wabbit it usually take few seconds to get start, this depend on hardware and how many other programs are in Startup directory.
  * If you are unable to remove it using windows, try to boot with linux live usb, then you should be able to remove foo.bat from Startup (This won't work if disk with windows is encrypted).

# Credits
- Wabbit: BlackBoot
- Persistent_Wabbit: https://github.com/Michyus
