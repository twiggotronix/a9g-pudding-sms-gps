# Sending sms and GPS with A9G pudding dev board

## Installation & setup

Download and install SDK and toolchain (cf. [A9G pudding dev board on twiggotronix.com](https://www.twiggotronix.com/fr/a9g-pudding-module-de-developpement/))

Copy the app_main.c file into your or clone this repo into the app folder : 
```bash 
git clone git@github.com:davidtwigger/a9g-pudding-sms-gps.git ./
```

Copy and rename include/app_main_example.h to include/app_main.h and replace the constant vales with yours:

Then run the build.bat script:
```bash
./build.bat app
```
