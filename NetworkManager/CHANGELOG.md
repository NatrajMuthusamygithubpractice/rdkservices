# Changelog

All notable changes to this RDK Service will be documented in this file.

* Each RDK Service has a CHANGELOG file that contains all changes done so far. When version is updated, add a entry in the CHANGELOG.md at the top with user friendly information on what was changed with the new version. Please don't mention JIRA tickets in CHANGELOG. 

* Please Add entry in the CHANGELOG for each version change and indicate the type of change with these labels:
    * **Added** for new features.
    * **Changed** for changes in existing functionality.
    * **Deprecated** for soon-to-be removed features.
    * **Removed** for now removed features.
    * **Fixed** for any bug fixes.
    * **Security** in case of vulnerabilities.

* Changes in CHANGELOG should be updated when commits are added to the main or release branches. There should be one CHANGELOG entry per JIRA Ticket. This is not enforced on sprint branches since there could be multiple changes for the same JIRA ticket during development. 

* For more details, refer to [versioning](https://github.com/rdkcentral/rdkservices#versioning) section under Main README.

## [0.2.11] - 2024-08-28
### Fixed
- onError event is posted for WiFi scan even when scan is successful

## [0.2.10] - 2024-08-23
### Fixed
- Wi-Fi Connection in Network page is showing 2.4Ghz when connected to 5Ghz network
### Added
- Async retry logic to check netsrvmgr is active

## [0.2.9] - 2024-07-04
### Fixed 
- Fixed all the regressions that are unearthed during migration to this plugin
- Fixed the core NetworkManager Plugin issues

## [0.2.0] - 2024-05-27
### Added
- Restructured the NetworkManager folder organization
- Refactored Legacy Network & WiFiManager Plugin as JSONRPC
- Built COMRPC Proxy Implementation as part of NetworkManager Plugin itself
- Built out-of-process class as part of main library itself.

## [0.1.0] - 2024-03-28
### Added
- Added NetworkManager plugin. A Unified `NetworkManager` plugin that allows you to manage Ethernet and Wifi interfaces on the device.
