# universal-redirector

![logo](./_assets/logo.png)

Redirect any text with Universal Redirector, it supports `http(s)://`, `slack://`, `obsidian://` and any other custom schema.
It helps you to open any link in your browser or app.

What is a custom schema? For example, `obsidian://` is a custom schema, it is used to open Obsidian vaults and files.
How to register a custom schema? It depends on your browser and OS. For example,
The following is a guide for macOS and Safari: [Defining a custom URL scheme for your app | Apple Developer Documentation](https://developer.apple.com/documentation/xcode/defining-a-custom-url-scheme-for-your-app)

## Usage

You can using https://r.0xyz.com/new.html to create a new link. For example, I want to create a link to open Obsidian vaults and files, I can use the following link:

```
https://r.0xyz.com/new.html?to=obsidian%3A%2F%2Fopen%3Fvault%3Dyours%26file%3Dyours
```

If you want to call somebody with Facetime, you can use the following link:

```
https://r.0xyz.com/?to=facetime%3A%2F%2F15555555555
```

More useful schemas your can find in [Complete List of iOS URL Schemes for Apple Apps and Services (Always-Updated) | by Justin Meyers | Medium](https://medium.com/@contact.jmeyers/complete-list-of-ios-url-schemes-for-apple-apps-and-services-always-updated-800c64f450f)

## One more thing

[universal-redirector.alfredworkflow](https://github.com/alswl/universal-redirector/blob/master/universal-redirector.alfredworkflow) is an Alfred workflow for quick access.
