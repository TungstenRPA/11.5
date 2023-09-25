# Kofax RPA 11.5
Due for release early October 2023.
## New Features
* Robots
  * Robots can now run stand-alone without a host Basic Engine Robot.
  * Robot Side Panels with Editors.
  * Chromium Embedded Framework (CEF) now has standalone executable for more frequent upgrading.
  * **Open Email** Step from BER has been added to Robots to allow easily handling of headers, subject, body and all attachments.
* Basic Engine Robot
  * The very old Classic Browser has been removed. it was deprecated in version 11.x?
  * The webkit(?) engine is still available for BER.
* Management Console
  * New login for users using tokens.
  * "Message of the Day" feature added. This will also help with communicating to RPA Cloud users.
* Robot File System
  * RFS can now be access from embedded Excel.
  * Files can be uploaded from RFS to embedded Browser (CEF).
* Cloud
  * Remote Roboservers.
  * Cloud Readiness Guide.
  * Token-based authentication to Management Console from Design Studio, Roboserver, Robot File System and Document Transformation Service.
* Kofax Total Agility Integration
  * Unifield Licensing with Kofax Total Agility.
  * Robots can be called directly from KTA, and KTA Quick Robots without requiring an intermediate BER.
    * There is a new **Return** Step in Robots to return multiple results.
  * Application Analytics
* 
## Docker
