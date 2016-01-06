# Grav Pages JSON Plugin

The **pages json plugin** for [Grav](http://github.com/getgrav/grav) provides a very basic json api for accessing pages from Grav.

# Installation

Download and unpack a zip (or clone this repository) into the user/plugins directory of your project

# Configuration

Simply copy the `user/plugins/grav-plugin-pages-json/grav-plugin-pages-json.yaml` into `user/config/grav-plugin-pages-json/grav-plugin-pages-json.yaml` and make your modifications.

```
enabled: true
```

# Usage

Send a request to any page on your site with the Accept header set to `application/json` and the plugin will return the response in a json structure.