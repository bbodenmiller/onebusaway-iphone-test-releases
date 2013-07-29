# onebusaway-iphone test releases #

Fake signed compiled code from onebusaway-iphone CI for users with jailbroken devices to test.

## Install ##
1. Install `git` and `MobileTerminal` from Cydia
2. In `MobileTerminal` run 
   * `login root` then enter root password (`alpine` if you never changed it)
   * `curl -LOk https://raw.github.com/bbodenmiller/onebusaway-iphone-test-releases/master/oba && chmod +x ./oba`
3. Then run `./oba <branch>` as root anytime you want to get the latest code (reboot will occur). `<branch>` should be replaced with the branch from [onebusaway-iphone](https://github.com/OneBusAway/onebusaway-iphone) you want to install. Leaving off the branch will default to the `dev` branch.
