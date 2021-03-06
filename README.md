## TagSpaces for YunoHost

[![Integration level](https://dash.yunohost.org/integration/tagspaces.svg)](https://dash.yunohost.org/appci/app/tagspaces) ![](https://ci-apps.yunohost.org/ci/badges/tagspaces.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/tagspaces.maintain.svg)

This YunoHost app is the self-hosted version of TagSpaces (information below). It is a self-hosted alternative to Evernote.
TagSpaces do not store data by itself. Instead, you could either use it to manage your local data, or to manage WebDAV data (such as a folder in your OwnCloud app).
Note: The data sources are stored in your web browser, meaning that other users won't have access to them and that you will have to redo your setup on other computers.

**The current version of the YNH TagSpaces app is v1.12.0**. I will not update at the moment because the newer version has a different UI that conflicts with SSOwat (the file creation icone is placed under the YunoHost icon...)

Configuration with the OwnCloud app as data source
--------------------------------------------------
- Browse to your app
- Create a new location with the path to your OwnCloud app folder **without the domain name** (only local owncloud installs work): /owncloud/remote.php/webdav/tagspaces (given you have a "tagspaces" folder at the root of your OwnCloud files)
- Give a name to your location and save.
- A dialog for credentials entering will appear. Enter here your ownCloud username and password.
- That's all, you can now browse your ownCloud files in TagSpaces.
More information: http://www.tagspaces.org/webdav-edition/


![tagspaces logo](https://raw.github.com/uggrock/tagspaces/master/data/assets/icon96.png) 
## Introduction

`TagSpaces` is a open source application for managing of your local files. You can find more information about it on its website [tagspaces.org](http://tagspaces.org/). For a quick TagSpaces introduction please see this [video](https://www.youtube.com/embed/CJ2hYU6U-C8) on youtube.

- [TagSpaces blog](http://tagspaces.org/blog/) for any news about tagspaces
- [the issues tracker](https://github.com/uggrock/tagspaces/issues) for developer support requests
- [the TagSpaces wiki](https://github.com/uggrock/tagspaces/wiki) for end-users and implementors (currently not really used)

## Features

* **File managing & tagging:** TagSpaces provides a convient interface for browsing, viewing and tagging of your local files
* **No-Cloud:** TagSpaces is running completely serverless on your laptop, desktop or tablet and does not request internet connection or any kind of online registration or service provider.
* **Note Taking:** You can create and edit notes in plain text, markdown and html file formats
* **Cross-platform:** TagSpaces runs perfectly on Windows, Linux, Mac, Android and as extension in Firefox and Chrome.

## Screenshots

![Lead TagSpaces Screenshot](http://www.tagspaces.org/content/v1.7/tagspaces-lead-screenshot.png)

### How to setup the TagSpaces WebDAV edition?
You can find information on this topic on the [TagSpaces blog](http://www.tagspaces.org/webdav-edition/).

## License

`TagSpaces`'s code uses the AGPL (GNU Affero General Public License) Version 3, see our `LICENSE` file.
