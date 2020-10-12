---
description: Learn how to authenticate yourself with the Minehut API
---

# Authentication

## What we need

To authenticate ourselves, we need to get our **token** and our **session id**. This can be found in every request sent by the browser regarding a panel action.

In order to get our token and session id:
1. Login to Minehut
2. Go into your **Dashboard**
3. Open up Chrome Developer Tools with **CTRL + Shift + I**
4. Double click on one of the requests labeled "all_data", if none are present, just wait a bit. It doesn't matter which one you click.
5. You'll see another 'panel' open up in Developer Tools, scroll down in it until you see **Request Headers**.
6. You'll see many fields and values in the Request Headers section, you'll want to write down the ones labeled **x-session-id** and **authorization**

Now you have your **session id** (**x-session-id**) and **token** (**authorization**)
Note that your session id expires periodically, and you'll have to grab new ones occasionally.

##  How to authenticate yourself when sending a request to the API

Whenever you're sending a request to the API, chances are it'll require authorization.
If it does, you'll want to pass **two headers**:
**x-session-id** Your session id
**authorization** Your token

Voila! If done correctly, you have authenticated yourself with the Minehut API.
