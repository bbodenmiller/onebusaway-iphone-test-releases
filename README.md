# onebusaway-iphone test releases #

Fake signed compiled code from [onebusaway-iphone CI](https://travis-ci.org/OneBusAway/onebusaway-iphone) for users with jailbroken devices to test.

## One Time Setup ##
1. Install `curl`, `MobileTerminal` (or any other terminal application), `AppSync for iOS 7.0+`, and `IPA Installer Console` from Cydia
2. Restart your iPhone
3. In `MobileTerminal` run `curl -LOk https://raw.github.com/bbodenmiller/onebusaway-iphone-test-releases/master/oba && chmod +x ./oba`

## Install ##
Run `./oba <username>/<branch>`. `<branch>` should be replaced with the branch you want to install while `<user>` should be replaced with the developers fork from which you want to install from. Leaving off the branch will default to the `OneBusAway/develop` branch.
