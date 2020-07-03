# Initial page

This repository contains all your certificates and provisioning profiles needed to build and sign your applications. They are encrypted using OpenSSL via a passphrase.

**Important:** Make sure this repository is set to private and only your team members have access to this repo.

Do not modify this file, as it gets overwritten every time you run _match_.

## Installation

Make sure you have the latest version of the Xcode command line tools installed:

```text
xcode-select --install
```

Install _fastlane_ using

```text
[sudo] gem install fastlane -NV
```

or alternatively using `brew cask install fastlane`

## Usage

Navigate to your project folder and run

```text
fastlane match appstore
```

```text
fastlane match adhoc
```

```text
fastlane match development
```

```text
fastlane match enterprise
```

For more information open [fastlane match git repo](https://docs.fastlane.tools/actions/match/)

## Content

### certs

This directory contains all your certificates with their private keys

### profiles

This directory contains all provisioning profiles

For more information open [fastlane match git repo](https://docs.fastlane.tools/actions/match/)

