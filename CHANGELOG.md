# Changelog


## 2.0.12#
* LCD functions fot T2mini
**Thanks to make this AWESOME PR [@ytyng](https://github.com/ytyng)**

## 2.0.11#
* Fixed exceptions with a device that is not sunmi.
* This is good if you have a hybrid app with just a condition to start or not sunmi printer.
**Thanks to open the issue [@aoeminh](https://github.com/aoeminh)**


# 2.0.10
* Print the arabic text in ColumnMaker wasn't working. Now it's fixed and the example will print chinese, russian and arabic.<br>
**Thanks AGAIN!!! to open the issue [@akshaykalola28](https://github.com/akshaykalola28)**

## 2.0.9
* This package still ( and i think will never) woks in IOS, but now you can generate your apps in IOS without exceptions.<br>
**Thanks to open the issue [@akshaykalola28](https://github.com/akshaykalola28)**

## 2.0.8
* Removed Label Printing Support , because the aidl don't give the support anymore (updated the IWoyouService)
* Update the printText method, now you can set the style, bold and size in the method.
* [x] cutPaper - Dedicated method just to cut the line
* [x] getPrinterSerialNo - Get the serial number of the printer
* [x] getPrinterVersion - Get the printer's version
* [x] getPrinterPaper - Get the paper size ( 0: 80mm 1: 58mm)
## 2.0.7
* Code format

## 2.0.6
* Fix enum.dart to format issues

## 2.0.5
* Fix enum.dart to format issues

## 2.0.4
* Fix some code to increase Pub points

## 2.0.3
* Fixed Barcode Example

## 2.0.2
* Fixed pubspec.yaml

## 2.0.1
* Fixed Readme

## 2.0.0

* 2.0.0 release
* Update Readme
* Enable Null Safety Support
* Label Printing Support For Sunmi V2 Pro
* Refine existing features
* Minor bug fixed
* Included Qrcode print
* Included Column print
* Included Barcode print
* Included method to print with escpos
* Included bold mode On/Off
* Included font size change:
    - Extra small
    - Small
    - Medium (default)
    - Large
    - Extra Large
