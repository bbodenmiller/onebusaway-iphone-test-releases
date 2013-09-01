# onebusaway-iphone test releases #

Fake signed compiled code from onebusaway-iphone CI for users with jailbroken devices to test.

## Install ##
1. Install `MobileTerminal` from Cydia
2. In `MobileTerminal` run `curl -LOk https://raw.github.com/bbodenmiller/onebusaway-iphone-test-releases/master/oba && chmod +x ./oba`
3. Then run `su root -c './oba <branch>'` and type your root password. `<branch>` should be replaced with the branch from [onebusaway-iphone](https://github.com/OneBusAway/onebusaway-iphone) you want to install. Leaving off the branch will default to the `dev` branch.
