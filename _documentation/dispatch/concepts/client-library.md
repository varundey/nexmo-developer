---
title: Client library
navigation_weight: 1
description: Client libraries are used to help you rapidly develop your messaging applications.
---

# Nexmo client library support

In addition to being able to use Messages and Dispatch via the REST APIs, Nexmo also provides client library support. Currently client library support is only available for Node.

During Beta the Node client library containing support for the Messages and Dispatch API can be installed using:

```
$ npm install nexmo@beta
```

If you decide to use the client library you will need the following information:

Key | Description
-- | --
`NEXMO_API_KEY` | The Nexmo API key which you can obtain from your [Nexmo Dashboard](https://dashboard.nexmo.com).
`NEXMO_API_SECRET` | The Nexmo API secret which you can obtain from your [Nexmo Dashboard](https://dashboard.nexmo.com).
`NEXMO_APPLICATION_ID` | The Nexmo Application ID for your Nexmo Application which can be obtained from your [Nexmo Dashboard](https://dashboard.nexmo.com).
`NEXMO_APPLICATION_PRIVATE_KEY_PATH` | The path to the `private.key` file that was generated when you created your Nexmo Application.

These variables can then be replaced with actual values in the client library example code.

Further examples on using the client library can be found here:

```building_block_list
product: dispatch
```
