# onebusaway-iphone test releases #

Fake signed compiled code from [onebusaway-iphone CI](https://travis-ci.org/OneBusAway/onebusaway-iphone) for users with jailbroken devices to test.

## One Time Setup ##
1. Install `cURL`, `WhiteTerminal` (or any other terminal application), `AppSync Unified`, and `IPA Installer Console` from Cydia
2. Restart your iPhone
3. In `WhiteTerminal` run `curl -LOko ./oba http://bit.ly/jboba && chmod +x ./oba`

## Install ##
Run `./oba <username>/<branch>`. `<branch>` should be replaced with the branch you want to install while `<username>` should be replaced with the developers fork from which you want to install from. Leaving off the branch will default to the `OneBusAway/develop` branch.
