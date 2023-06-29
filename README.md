# os-download-packages

## Introduction

This Java-based command-line tool provides a simple method to download packages from a OneSpan account.

## Set-Up Instructions

+ Download the latest release of the `os-download-packages-<version>.jar` from the [Releases](https://git.corp.adobe.com/sign-acs/os-download-packages/releases) page
+ [Download Java 1.8](https://www.oracle.com/java/technologies/javase/javase8-archive-downloads.html), if you don't already have it installed on your machine

## Usage

+ Open a command prompt in the directory where you have the JAR file downloaded
+ Execute the following command, replacing:
  + `<version>` with the appropriate value for the release, such as `1.0.0`
  + `<api-url>` with the URL for your account
  + `<api-key>` with the API Key for your account

```sh
java -jar os-download-packages-<version>.jar <api-url> <api-key>
```

Assuming you have specified the required parameters correctly, then you should see output similar to that below:

![Sample Output](/images/example-usage.png)
