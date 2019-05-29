phil-mayer/google-analytics-plugin
=======================

This repository is a fork of [danwilson/google-analytics-plugin](https://github.com/danwilson/google-analytics-plugin). This fork was created to resolve an issue where Apple rejects the App Store submission because the plugin unexpectedly includes IDFA-related code. See [this related issue](https://github.com/danwilson/google-analytics-plugin/issues/218) for more details.

# Installation
The `no-idfa` branch of this repository removes IDFA-related code. When installing this plugin with the Cordova CLI, make sure to specify the correct branch.
```sh
cordova plugin add https://github.com/phil-mayer/google-analytics-plugin.git#no-idfa
```
