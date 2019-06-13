# AppleWatch DeviceSupport for Xcode [![Tweet](https://img.shields.io/twitter/url/http/shields.io.svg?style=social)](https://twitter.com/intent/tweet?text=Check%20out%20Xcode-watchOS-DeviceSupport%20on%20GitHub&url=https://github.com/isatria/Xcode-watchOS-DeviceSupport)

![last commit](https://img.shields.io/github/last-commit/isatria/Xcode-watchOS-DeviceSupport.svg)


Will update regularly.

## Usage: ##
Below command is trying to extract all files zip of device support to **/Applications/Xcode.app**.

```pyton
sudo pyton extract.py
```

You can use `--target` if your Xcode is not in **/Applications/**

```pyton
sudo python extract.py --target /Document/Xcode.app
```

```
python extract.py -h
usage: extract.py [-h] [--target XCODEPATH]

Extract DeviceSupport files to Xcode.app

optional arguments:
  -h, --help          show this help message and exit
  --target XCODEPATH  custom Xcode.app path location
```
### Manual ###
1. Close **Xcode**.
2. Open **Finder**.
3. Press **Shift**+**⌘ (Command)**+**G** to open *Go to Folder*
4. Enter: `/Applications/Xcode/Contents/Developer/Platforms/WatchOS.platform/DeviceSupport/`.
5. Then extract (unzip) and copy the latest Device Support file do you want to this directory.

**Note :**  
If your **Xcode.app** is not in `/Applications/`, change `/Applications/Xcode` to match the path of the existence of **Xcode.app**.

## Supported Versions ##
#### watchOS 6: ####
> * [6.0 (17R5491t)](https://github.com/isatria/Xcode-watchOS-DeviceSupport/raw/master/src/6.0.zip) `31 May 2019`

#### watchOS 4: ####
> * [4.3 (15T212)](https://github.com/isatria/Xcode-watchOS-DeviceSupport/raw/master/src/4.3.zip) `14 March 2018`
> * [4.2 (15S102)](https://github.com/isatria/Xcode-watchOS-DeviceSupport/raw/master/src/4.2.zip) `15 November 2017`
> * [4.1 (15R846)](https://github.com/isatria/Xcode-watchOS-DeviceSupport/raw/master/src/4.1.zip) `19 October 2017`
> * [4.0 (15R372)](https://github.com/isatria/Xcode-watchOS-DeviceSupport/raw/master/src/4.0.zip) `29 August 2017`

#### watchOS 3: ####
> * [3.2 (14V249)](https://github.com/isatria/Xcode-watchOS-DeviceSupport/raw/master/src/3.2.zip) `17 March 2017`
> * [3.1 (14S471)](https://github.com/isatria/Xcode-watchOS-DeviceSupport/raw/master/src/3.1.zip) `24 October 2016`
> * [3.0 (14S326)](https://github.com/isatria/Xcode-watchOS-DeviceSupport/raw/master/src/3.0.zip) `13 October 2016`

#### watchOS 2: ####
> * [2.2 (13V144)](https://github.com/isatria/Xcode-watchOS-DeviceSupport/raw/master/src/2.2.zip) `9 March 2016`
> * [2.1 (13S661)](https://github.com/isatria/Xcode-watchOS-DeviceSupport/raw/master/src/2.1.zip) `14 December 2015`
> * [2.0 (13S344)](https://github.com/isatria/Xcode-watchOS-DeviceSupport/raw/master/src/2.0.zip) `16 September 2015`

## External links ##
* [Official Latest Xcode 11 Beta Build (11M336W)](https://developer.apple.com/services-account/download?path=/WWDC_2019/Xcode_11_Beta/Xcode_11_Beta.xip)

