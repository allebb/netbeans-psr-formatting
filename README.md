# PSR auto-formatting for NetBeans

This repository provides source code auto-formatting settings for PHP [PSR1](http://www.php-fig.org/psr/psr-1/) and [PSR2](http://www.php-fig.org/psr/psr-2/) standards.

Although [NetBeans](https://netbeans.org/) does not provide automatic formatting support for all of the PSR1 and PSR2 'rules' (eg. refactoring class and method name case) I have done my best to implement as much as possible.

The result of using this configuration is, once imported you can then use the ```Source > Format``` function (``ALT``+``SHIFT``+``F`` on Windows and Linux) or (``ALT``+``F`` on Mac) in NetBeans the PHP code will automatically be formatted to match PSR1/PSR2 syntax format.

## Requirements

* [NetBeans](https://netbeans.org/) (Tested and developed on v8.0.2 but should work fine on other versions too!)

## License

All things have a license I guess, so keeping it plain and simple, these files are released under the [MIT license](LICENSE).

## Support

I am happy to provide support via. my personal email address, so if you need a hand or want to give me some feedback feel free to drop me an email at: [ballen@bobbyallen.me](mailto:ballen@bobbyallen.me).

## Installation

* Download the [latest release](http://lk2.in/cQ) to your machine.
* Open up the NetBeans IDE on your computer
* From the top menu, click on ```Tools``` and then from the menu that appears click ```Options```
* When the **Options** window appears click on the ```Import``` button at the bottom left.
* When the **Import** window appears click on the ```Browse``` button and select the downloaded zip archive that you downloaded in the first step.
* Under the ```Select options to import:```, check the ```All``` check box and then click ```Ok``` and then ```Apply```.
* You should then be prompted to restart the IDE, restart and enjoy your new auto-formatting skills ;)

## Preparing the source code for 'import'

In order to import the settings into NetBeans, compress the root directory of the ```src``` directory into a **zip file** of which can then be used to import into NetBeans as shown below in the installation guide.
