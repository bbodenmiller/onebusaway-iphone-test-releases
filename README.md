# onebusaway-iphone test releases #

Fake signed compiled code from onebusaway-iphone CI for users with jailbroken devices to test.

## Install ##
1. Install `git` and `MobileTerminal` from Cydia
2. In `MobileTerminal` run 
   * `rm oba` if script already exists
   * `curl -LOk https://raw.github.com/bbodenmiller/onebusaway-iphone-test-releases/master/oba && chmod +x ./oba`
3. Then run `./oba <branch>` anytime you want to get the latest code. `<branch>` should be replaced with the branch from [onebusaway-iphone](https://github.com/OneBusAway/onebusaway-iphone) you want to install. Leaving off the branch will default to the `dev` branch.
