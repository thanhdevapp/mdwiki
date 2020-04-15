---
description: You can send requests in Postman to connect to APIs you are working with
---

# Sending your first request with postman

## How it work?

When you send a request, Postman will display the response received from the API server in a way that lets you examine, visualize, and if necessary troubleshoot it.

![](../.gitbook/assets/image%20%281%29.png)

## CrCSending your first request

You can make requests to APIs in Postman. An API request allows you to retrieve data from a data source, or to send data. APIs run on web servers, and expose enpdoints to support the operations client applications use to provide their functionality.

Each API request uses an HTTP method. The most common methods are `GET`, `POST`, `PATCH`, `PUT`, and `DELETE`.

* `GET` methods retrieve data from an API.
* `POST` sends new data to an API.
* `PATCH` and `PUT` methods update existing data.
* `DELETE` removes existing data.

In Postman you can make API requests and examine the responses without using a terminal or writing any code. When you create a request and click **Send**, the API response appears inside the Postman user interface.

![request and response illustration](https://assets.postman.com/postman-docs/anatomy-of-a-request.png)

### Sending a request <a id="sending-a-request"></a>

To send your first API request, open Postman. Make sure **Build** is selected at the bottom right. Click the **+** plus button to open a new tab.

Enter `postman-echo.com/get` in the URL field.

Click **Send**. You will see the JSON data response from the server in the lower pane.

![request response](https://assets.postman.com/postman-docs/Request-repsonse.png)

