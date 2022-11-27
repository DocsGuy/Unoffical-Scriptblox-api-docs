# Upload
- About: Upload an script.

```
{"Authorization": "your scriptblox token here"} -- you need to add that to the headers if you want to e.g request it with python
captcha: "" -- captcha idk, how to automate this process, just use the recaptcha api ig?
features: "Test" -- features
gameLink: "" -- game link
image: "your image" -- you can prb. remove that when it isn't unversial
isUniversal: true -- if its unversial
script: "print(\"\"hi\")"
scriptType: "free"
tags: []
title: "Test"
verified: false
visibility: "private" -- or "Unlisted" or "Public"
https://scriptblox.com/api/script/upload
```