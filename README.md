# iInjection
iInjection is developed by codesourse https://github.com/codesourse

This is an app for OS X that can inject dylib and (re)sign apps and bundle them into ipa files that are ready to be installed on an iOS device.

Supported input types are: ipa, deb, app, xcarchive

Usage

This app requires Xcode to be installed, it has only been successfully tested on OS X 10.11 at this time.

You need a provisioning profile and signing certificate, you can get these from Xcode by creating a new project.

You can then open up iOS App Signer and select your input file, signing certificate, provisioning file, and optionally specify a new application ID and/or application display name.

Donate 

https://github.com/codesourse/iInjection/blob/master/%E6%B1%82%E6%89%93%E8%B5%8F.png

Thanks To

maciekish / iReSign: The basic process was gleaned from the source code of this project.

DanTheMan827/ios-app-signer The basic process was gleaned from the source code of this project.

KJCracks/yololib  

Help && Communication

![avatar](iInjection逆向交流群群二维码.png)   

libhookFile里面添加了JSPatch 热更新代码
重签名工具还是可以玩一下 不过网上各种好用的重签名也有很多
libhookFile就不要用他的了 git上有开源的还是自己去下载的好




