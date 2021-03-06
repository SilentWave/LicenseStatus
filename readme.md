## Description

License Status reads the current status of FlexLM / FlexNet licenses (using lmutil's lmstat command) and presents it in a more usable table format.

License Status is an alternative to the LMTools Server Status tab.

Requires .NET Framework 4.0.

## Features

- Display the license information in an easy to use table
- Sort and group by feature, user, checkout time or other information
- View multiple licenses
- Quickly refresh the status at any time
- Automatic highlighting of users with borrowed features
- View the original text of the lmutil's lmstat command

## Release Notes

August 31, 2014 v3.7

- Released on [GitHub](https://github.com/CharlesWB/LicenseStatus).

October 23, 2012 v3.6

- Add support for spaces within a user's name or display.
- Change About window to display the program version in major.minor format.
- Change background color from a gradient to a solid faint gray color.

September 18, 2012 v3.5

- Added support for situations where the same user/host/display can check out more than one license.
- Added a column 'Checked out' to display the number of licenses a user has checked out. This column is turned off by default.
- Changed the Feature information to show the correct number of used licenses when a user can check out more than one.

July 27, 2012 v3.4

- Corrected issue where the checkout time was missing for most locales other than basic English.

July 26, 2012 v3.3

- Corrected issue where reading the status would cause a crash for most locales other than basic English.

June 14, 2012 v3.2

- Added the ability to turn on and off columns in the detail view.
- Changed the application icon.
- Updated the class library, LicenseManager.dll, to use .NET 4.0.
- Updated various class library methods to use LINQ.

April 1, 2012 v3.1

- Corrected issue where the window position would be restored to a second monitor even if that monitor was disabled.

March 6, 2012 v3.0

- Updated to use .NET 4.0.
- Changed text formatting mode from Ideal to Display. This improves the "blurry" font display seen in WPF .NET 3.5.
- Replaced old Visual Studio installer project with a WiX installer.
- Corrected issue where the settings were not remembered when upgrading from a previous version.

May 20, 2010 v2.4

- Changed the Help-> About url to the Sourceforge project web site.
- Changed the copyright to 2010.

October 17, 2009 v2.3

- Released on [SourceForge](http://sourceforge.net/projects/licensestatus/).

October 9, 2009 v2.3

- Fixed issue with feature and vendor daemon name containing a period.

August 30, 2009 v2.2

- Public release.

August 17, 2009 v2.1

- Private beta release.