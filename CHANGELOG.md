# Change Log

## [1.2.12](https://github.com/CloudRail/cloudrail-si-xamarin-android-sdk/tree/1.2.12) (2018-09-11)
[Full Changelog](https://github.com/CloudRail/cloudrail-si-xamarin-android-sdk/compare/1.2.11...1.2.12)

* GoogleDrive: Fix Authentication issue

## [1.2.11](https://github.com/CloudRail/cloudrail-si-xamarin-android-sdk/tree/1.2.11) (2018-08-30)
[Full Changelog](https://github.com/CloudRail/cloudrail-si-xamarin-android-sdk/compare/1.2.10...1.2.11)

* Fixed OneDrive For business auth process
* Fixed Google Drive (fileExists)
* Fixed Backblaze Advance Request

## [1.2.10](https://github.com/CloudRail/cloudrail-si-xamarin-android-sdk/tree/1.2.10) (2018-05-22)
[Full Changelog](https://github.com/CloudRail/cloudrail-si-xamarin-android-sdk/compare/1.2.9...1.2.10)

* OneDriveBusiness: Fix missing url encoding of the client secret on refreshing tokens
* GoogleCloudPlatform: Add a missing internal function
* MicrosoftAzure: Fix an issue in the advanced request function

## [1.2.9](https://github.com/CloudRail/cloudrail-si-xamarin-android-sdk/tree/1.2.9) (2018-04-23)
[Full Changelog](https://github.com/CloudRail/cloudrail-si-xamarin-android-sdk/compare/1.2.8...1.2.9)

* OneDrive: Attach missing state parameter to authentication url
* Facebook: Removed user_about_me scope which shows description.
* Google Cloud: Added object name encoding to google cloud.

## [1.2.8](https://github.com/CloudRail/cloudrail-si-xamarin-android-sdk/tree/1.2.8) (2018-04-10)
[Full Changelog](https://github.com/CloudRail/cloudrail-si-xamarin-android-sdk/compare/1.2.7...1.2.8)

* Fixed bug in Exists: method in GoogleDrive.
* Added AdvancedRequest feature in Yelp.
* Added new method ListFilesInBucketWithPrefix to BusinessCloudStorage interface.

## [1.2.7](https://github.com/CloudRail/cloudrail-si-xamarin-android-sdk/tree/1.2.7) (2018-03-28)
[Full Changelog](https://github.com/CloudRail/cloudrail-si-xamarin-android-sdk/compare/1.2.6...1.2.7)

* Minor fix in AmazonS3, GoogleCloudPlatform, FacebookMessenger
* Fix in uploadFileWithContentModified for all CloudStorage Interfaces.
* Updated Yelp to use API v3.

## [1.2.6](https://github.com/CloudRail/cloudrail-si-xamarin-android-sdk/tree/1.2.6) (2018-02-12)
[Full Changelog](https://github.com/CloudRail/cloudrail-si-xamarin-android-sdk/compare/1.2.5...1.2.6)

* Add a new method to the CloudStorage interface that allows uploading files with a custom modified date
* Fix a missing Authorization header in getChildren and getChildrenPage of OneDrive
* Fix error handling in Dropbox
* Fix an issue with upload in PCloud

## [1.2.5](https://github.com/CloudRail/cloudrail-si-xamarin-android-sdk/tree/1.2.5) (2018-01-23)
[Full Changelog](https://github.com/CloudRail/cloudrail-si-xamarin-android-sdk/compare/1.2.4...1.2.5)

* pCloud added as a new integration in the Cloud Storage interface
* Fixed Google Drive path issue (when it contains backslashes)

## [1.2.4](https://github.com/CloudRail/cloudrail-si-xamarin-android-sdk/tree/1.2.4) (2017-11-15)
[Full Changelog](https://github.com/CloudRail/cloudrail-si-xamarin-android-sdk/compare/1.2.3...1.2.4)

* Bug fixes for GMail and Telegram
* Add SlackBot as a new service for the messaging interface

## [1.2.3](https://github.com/CloudRail/cloudrail-si-xamarin-android-sdk/tree/1.2.3) (2017-10-29)
[Full Changelog](https://github.com/CloudRail/cloudrail-si-xamarin-android-sdk/compare/1.2.2...1.2.3)

* Amazon S3 fix

## [1.2.2](https://github.com/CloudRail/cloudrail-si-xamarin-android-sdk/tree/1.2.2) (2017-10-17)
[Full Changelog](https://github.com/CloudRail/cloudrail-si-xamarin-android-sdk/compare/1.2.1...1.2.2)

* Added Advance Request to Messaging Services
* Added Send Caurosel Method to Messaging Interface

## [1.2.1](https://github.com/CloudRail/cloudrail-si-xamarin-android-sdk/tree/1.2.1) (2017-10-17)
[Full Changelog](https://github.com/CloudRail/cloudrail-si-xamarin-android-sdk/compare/1.2.0...1.2.1)

* Added New Messaging Interfaces (Facebook, Viber)
* Fixed Amazon S3 pagination issue
* Fixed for CloudStorage (OneDrive, Google Drive, Box and Dropbox)
* Fixed OneDrive Business

## [1.2.0](https://github.com/CloudRail/cloudrail-si-xamarin-android-sdk/tree/1.2.0) (2017-10-09)
[Full Changelog](https://github.com/CloudRail/cloudrail-si-android-sdk/compare/1.2.0...1.0.0)

* Added Messaging Interface (Telegram, Line)

## [1.0.0](https://github.com/CloudRail/cloudrail-si-xamarin-android-sdk/tree/1.0.0) (2017-08-07)
- Initial release
