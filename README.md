<p align="center">
   <img src='icon.png' alt="icon" /></p>
</p>   
<h3 align="center">Open Contributions to</h3>
<h1 align="center">Download All Images</h1>

> ### [Download All Images](https://download-all-images.mobilefirst.me/) is a popular Chrome extension for downloading a large number of images from a web page with a single click. 

<br/>

[![img](https://img.shields.io/chrome-web-store/v/ifipmflagepipjokmbdecpmjbibjnakm)](https://chrome.google.com/webstore/detail/ifipmflagepipjokmbdecpmjbibjnakm)
[![img](https://img.shields.io/chrome-web-store/users/ifipmflagepipjokmbdecpmjbibjnakm)](https://chrome.google.com/webstore/detail/ifipmflagepipjokmbdecpmjbibjnakm)
[![img](https://img.shields.io/chrome-web-store/stars/ifipmflagepipjokmbdecpmjbibjnakm)](https://chrome.google.com/webstore/detail/ifipmflagepipjokmbdecpmjbibjnakm)
[![img](https://img.shields.io/chrome-web-store/rating-count/ifipmflagepipjokmbdecpmjbibjnakm)](https://chrome.google.com/webstore/detail/ifipmflagepipjokmbdecpmjbibjnakm)
[![img](https://img.shields.io/static/v1?label=first%20release&message=2017&color=AB47BC)](https://chrome.google.com/webstore/detail/ifipmflagepipjokmbdecpmjbibjnakm)

### Purpose

This repository is meant for public issue tracking and community contributions to Download All Images.
More specifically it serves these purposes:

1. Open tracking for pending issues and creating new issues
2. Enabling user contributions to source, such as language translations
3. Going forward: maintaining release notes and history of releases

* * *

### Download All Images is free to use, does not have ads, does not spy on you, or sell your data.

Consider supporting the project by contributing to its development in the ways described below or by sponsoring the effort.

* * *

## Issue Tracking

- First see open [issues](https://github.com/MobileFirstLLC/dai-contrib/issues)

- If the issue you are having is not addressed in the open issues, [open a new issue](https://github.com/MobileFirstLLC/dai-contrib/issues/new/choose).


## Translations

If you are a user of Download All Images and speak multiple languages, consider providing a 
translation to make the experience more user-friendly.

### Current Language Support

| Code | Description | Edit | Target Release |
| --- | --- | --- | --- |
| `en` | English (US, UK) default | [source](/locales/en/messages.json) | available |
| `fi` | Finnish | [source](/locales/fi/messages.json) | v2.5.0 |

#### Instructions for adding new languages

1. Fork this repo
2. Under `locales` directory create a new directory for the language of your choice. 
   Refer to [this list  of locale codes](https://developer.chrome.com/webstore/i18n#localeTable). 
   Use the locale code as directory name.
3. Make a copy of `/locales/en/messages.json` and paste it under your newly created directory.
4. For each entry in the `.json` file, replace value of `message` with an appropriate translation.
5. Submit a pull request.
6. If approved your translation will be added to the next release.   

#### Instructions for improving translations

1. Fork this repo
2. Navigate to `locales` and then choose the language you want to edit
3. Open the `messages.json` to make corrections
4. Submit a pull request
5. If approved, the correction will be included in the next release.   

* * *

Download All Images is made by [Mobile First](https://mobilefirst.me) in Augusta, Georgia 🍑
