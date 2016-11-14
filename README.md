# PSR auto-formatting for NetBeans

This repository provides source code auto-formatting settings for PHP [PSR1](http://www.php-fig.org/psr/psr-1/) and [PSR2](http://www.php-fig.org/psr/psr-2/) standards.

Although [NetBeans](https://netbeans.org/) does not provide automatic formatting support for all of the PSR1 and PSR2 'rules' (eg. refactoring class and method name case) I have done my best to implement as much as possible.

The result of using this configuration is, once imported you can then use the ```Source > Format``` function (``ALT``+``SHIFT``+``F`` on Windows and Linux) or (``CTRL``+``SHIFT``+``F`` on Mac) in NetBeans the PHP code will automatically be formatted to match PSR1/PSR2 syntax format.

## Requirements

* [NetBeans](https://netbeans.org/) (Tested and developed on v8.2 and v8.1 but should work fine on other versions too!)

## License

All things have a license I guess, so keeping it plain and simple, these files are released under the [MIT license](LICENSE).

## Support

I am happy to provide support via. my personal email address, so if you need a hand or want to give me some feedback please drop me an email at: [ballen@bobbyallen.me](mailto:ballen@bobbyallen.me).

## Installation

* Download the [latest release](https://github.com/bobsta63/netbeans-psr-formatting/releases) (specifically the __ZIP__ version) to your machine (If you're using Netbeans 8.1 or below see the notes below about a bug and a provided workaround version).
* Open up the NetBeans IDE on your computer
* From the top menu, click on ```Tools``` and then from the menu that appears click ```Options```
* When the **Options** window appears click on the ```Import``` button at the bottom left.
* When the **Import** window appears click on the ```Browse``` button and select the downloaded zip archive that you downloaded in the first step.
* Under the ```Select options to import:```, check the ```All``` check box and then click ```Ok``` and then ```Apply```.
* You should then be prompted to restart the IDE, restart and enjoy your new auto-formatting skills ;)

## Using NetBeans 8.1 (and lower)?

There is an issue in Netbeans versions 8.1 (and lower) in which the ``namespace`` new-line configuration does not work (a bug) of which has since been 
fixed in Netbeans 8.2. As a workaround however, [release v1.0.1](https://github.com/bobsta63/netbeans-psr-formatting/releases/tag/v1.0.1) uses a single blank line to split the ``namespace`` from the first line of which is recommended to use.

## Preparing the source code for 'import'

In order to import the settings into NetBeans, compress the root directory of the ```src``` directory into a **zip file** of which can then be used to import into NetBeans as shown below in the installation guide.
