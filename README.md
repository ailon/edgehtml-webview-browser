# EdgeHTML WebView Browser
The purpose of this quick solution is to enable web developers to test their code in the "legacy" version of Microsoft Edge which has been removed from most Windows 10 systems by now.

## Build or Download
You can download the "browser" from Releases here on GitHub or build it on your own by pulling the source code (it's a Visual Studio 2017 solution).

## Grant access
By default WebView doesn't have access to `localhost` on Windows 10 and you have to allow it access on your machine by running:

```
checknetisolation LoopbackExempt -a -n="Microsoft.Win32WebViewHost_cw5n1h2txyewy"
```

## Debugging
Get [Microsoft Edge DevTools Preview](https://www.microsoft.com/store/productId/9MZBFRMZ0MNJ) from the Microsoft Store to attach to this "browser" so you get access to all the dev tools for testing and debugging your solution.

## Credits
This solution uses [WebView control from the Windows Community Toolkit](https://docs.microsoft.com/en-us/windows/communitytoolkit/controls/wpf-winforms/webview)
