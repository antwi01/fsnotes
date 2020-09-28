# Introduction

This is an example of how to package an iOS app for Veracode static scanning, and also shows SCA agent-based scanning.

This is a Veracode-specific readme file.  For the original, see README-original.md.

# How to use this

You have 3 options to run a static scan:

1. Upload the .bca archive from the `veracode-output` directory.
2. Clone this repo and built it yourself (requires a Mac with Xcode and an Apple Developer account).  Then package and upload for scanning.
3. Use the included `bitrise.yml` file to build this app on Bitrise (requires a Bitrise account and an Apple Developer account).

# Notes

There are a few screenshots of this app running on an iPad mini in the `veracode-docs` directory.  There is also a screenshot of the end of a Bitrise build.