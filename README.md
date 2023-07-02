# universal-redirector

<image src="./_assets/logo.png" width="200" height="200"></image>

Online: [https://r.0xyz.com](https://r.0xyz.com)

Redirect any text with Universal Redirector, it supports `http(s)://`, `slack://`, `obsidian://` and any other custom schema.
It helps you to open any link in your browser or app. You can put this links to any place, such as your notes, your bookmarks, your blog, etc.

what is a custom schema? for example, `obsidian://` is a custom schema, it is used to open obsidian vaults and files.
how to register a custom schema? it depends on your browser and os. for example,
the following is a guide for macos and safari: [defining a custom url scheme for your app | apple developer documentation](https://developer.apple.com/documentation/xcode/defining-a-custom-url-scheme-for-your-app)

## usage

you can using [https://r.0xyz.com/new.html](https://r.0xyz.com/new.html) to create a new link. for example,
I want to using a link to open Obsidian vaults and files, I can use the following link:

```
https://r.0xyz.com/?to=obsidian%3A%2F%2Fopen%3Fvault%3Dmy-kms%26file%3Djournals%252F2014%252F2014-09%252F2014-09-03
```

If you want to call somebody with Facetime, you can use the following link:

```
https://r.0xyz.com/?to=facetime%3A%2F%2F15555555555
```

More useful schemas your can find in [Complete List of iOS URL Schemes for Apple Apps and Services (Always-Updated) | by Justin Meyers | Medium](https://medium.com/@contact.jmeyers/complete-list-of-ios-url-schemes-for-apple-apps-and-services-always-updated-800c64f450f)

## One more thing

[universal-redirector.alfredworkflow](https://github.com/alswl/universal-redirector/blob/master/universal-redirector.alfredworkflow) is an Alfred workflow for quick access.
