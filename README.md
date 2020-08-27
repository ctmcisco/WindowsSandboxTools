# Windows Sandbox Tools

![sandbox](images/sandbox.jpg)

This repository is a collection of PowerShell tools and scripts that I use run and configure the Windows Sandbox. Many of these commands were first explained on my [blog](https://jdhitsolutions.com/blog/powershell/7621/doing-more-with-windows-sandbox/). Note that most of the code here will __reduce the security__ of the sandbox application. This is a trade-off I am willing to make for the sake of functionality that meets *my* requirements. You have to decide how much of my code you would like to use.

__*All code is offered as-is with no guarantees. Nothing in this repository should be considered production-ready or used in critical environments.*__

## Installing the Windows Sandbox

You need to have the 2004 version of Windows 10. You should then be able to run these PowerShell commands.

```powershell
Get-WindowsOptionalFeature -online -FeatureName Containers-DisposableClientVM
Enable-WindowsOptionalFeature -Online -FeatureName Containers-DisposableClientVM
```
