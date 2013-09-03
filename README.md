# onebusaway-iphone test releases #

Fake signed compiled code from [onebusaway-iphone CI](https://travis-ci.org/OneBusAway/onebusaway-iphone) for users with jailbroken devices to test.

## Install ##
1. Install `MobileTerminal` and `IPA Installer Console` from Cydia
2. In `MobileTerminal` run `curl -LOk https://raw.github.com/bbodenmiller/onebusaway-iphone-test-releases/master/oba && chmod +x ./oba`
3. Then run `./oba <branch>`. `<branch>` should be replaced with the branch from [onebusaway-iphone](https://github.com/OneBusAway/onebusaway-iphone) you want to install. Leaving off the branch will default to the `develop` branch.
