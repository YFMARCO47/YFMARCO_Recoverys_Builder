# YFMARCO Recovery Builder |TWRP / PBRP / OFRP / SHRP|
Compile your first custom recovery via Github Actions - with ldcheck setup.

## How to Use
1. Fork this repository.

## How to build in case of private repository
1. Create a token.
2. Enter the repository settings.
3. Go to the Secrets and variables option then to Actions.
4. Create a new repository secret.
5. The first thing you will name "RECOVERY_TOKEN" is where you will put the Token.
6. The second secret is called "RECOVERY_USERNAME" This is where you will enter the email address associated with your GitHub account.

2. Go to `Action` tab > `All workflows` > Pick which Build you need (`TWRP or PBRP or OFRP or SHRP`) > `Run workflow`, then pick required information from each drop-down list:
 - Manifest Branch (*14.1,*12.1, *11.0, *10.0, *9.0, *8.1, *7.1, *6.0, etc.)
 - Device Tree (Your device tree repository link)
 - Device Tree Branch (Your device tree repository branch)
 - Build Target (boot, reecovery, vendorboot)
 - LDCHECK (path to your target binary file, ie. `system/bin/qseecomd`)
   - If you are building manually/locally and you want to use ldcheck for checking dependencies, visit [THIS](https://github.com/TeamWin/android_device_qcom_twrp-common/tree/android-11#using-ldcheck-to-find-dependencies) this for guide.

## Thanks/Credits
 - [YFMARCO-Dev](https://github.com/YFMARCO-Dev)
 - [CaptainThrowback](https://github.com/CaptainThrowback)
 - [azwhikaru](https://github.com/azwhikaru)
 - [cd-Crypton](https://github.com/cd-Crypton)
 - [that1](https://github.com/that1)
 - [carlodandan](https://github.com/carlodandan)
 - [lazycodebuilder](https://github.com/lazycodebuilder)
 - And to all Contributors in every repositories and scripts I used.