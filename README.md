# onebusaway-iphone test releases #

Fake signed compiled code from [onebusaway-iphone CI](https://travis-ci.org/OneBusAway/onebusaway-iphone) for users with jailbroken devices to test.

## Install ##
1. Install `curl`, `MobileTerminal` (or any other terminal application), and `IPA Installer Console` from Cydia
2. In `MobileTerminal` run `curl -LOk https://raw.github.com/bbodenmiller/onebusaway-iphone-test-releases/master/oba && chmod +x ./oba`
3. Then run `./oba <username>/<branch>`. `<branch>` should be replaced with the branch you want to install while `<user>` should be replaced with the developers fork from which you want to install from. Leaving off the branch will default to the `OneBusAway/develop` branch.
