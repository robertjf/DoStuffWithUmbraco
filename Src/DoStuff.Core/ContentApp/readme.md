﻿# ContentApp


## ContentApp setup 
You can setup a content app in two ways either via a package.manifest file or by 
haveing a class that impliments IContentAppFactory (and is registered via a composer)

you can control most things via the package.manifest file - registering via code 
just gives you slightly more control over when or when not to include your app.

- [CustomContentApp.cs](CustomContentApp.cs)

the content app will show html/js from the app_plugins folder as defined by you

- [App_Plugins ContentApp Folder](../App_Plugins/DoStuff.ContentApp/)


# See Also

- Content App Intro https://umbraco.com/blog/umbraco-8-content-apps/
- Documentation https://our.umbraco.com/documentation/Extending/Content-Apps/


