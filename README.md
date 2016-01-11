#### This Classic SDK is not actively supported and will be deprecated in the future. For full support on new integrations, please use the [PayPal .NET SDK](https://github.com/paypal/PayPal-NET-SDK)

## TLSv1.2 Update
> **The Payment Card Industry (PCI) Council has [mandated](http://blog.pcisecuritystandards.org/migrating-from-ssl-and-early-tls) that early versions of TLS be retired from service.  All organizations that handle credit card information are required to comply with this standard. As part of this obligation, PayPal is updating its services to require TLS 1.2 for all HTTPS connections. At this time, PayPal will also require HTTP/1.1 for all connections. [Click here](https://github.com/paypal/tls-update) for more information**

> A new `mode` has been created to test if your server/machine handles TLSv1.2 connections. Please use `security-test-sandbox` mode instead of `sandbox` to verify. You can return back to `sandbox` mode once you have verified.

---

# PayPal Invoice Classic SDK for .NET

The repository contains the PayPal Invoice SDK C#.NET Class Library Application and the InvoiceSampleApp Sample ASP.NET C# Web Application.


## SDK Integration

*	Integrate the PayPal Invoice SDK with an ASP.NET Web Application

*	Use NuGet to install the 'PayPalInvoiceSDK' package 

*	The NuGet package installs the dependencies to the solution and automatically updates the project

*	Dependent library references:
	•	'log4net.dll'
	•	'PayPalCoreSDK.dll'	
	•	'PayPalInvoiceSDK.dll'
	•	'PayPalPermissionsSDK.dll'

*	Namespaces:
	•	PayPal
	•	PayPal.Invoice
	•	PayPal.Invoice.Model
	•	PayPal.Permissions
	•	PayPal.Permissions.Model
	•	PayPal.Util
	•	PayPal.Exception

*	Aliases:
	•	extern alias InvoiceAlias
	•	extern alias PermissionsAlias
	
## Using Classic SDKs and PayPal .NET SDK

[See here](https://github.com/paypal/merchant-sdk-dotnet#using-classic-sdks-and-paypal-net-sdk) for instructions on how to use this SDK along with the [PayPal .NET SDK](https://github.com/paypal/PayPal-NET-SDK).

## Help

*	Build.bat - Automation script that builds the PayPal Invoice SDK C#.NET Class Library Application in release mode and copies the built dlls to the lib folder in the InvoiceSampleApp Sample ASP.NET C# Web Application

*	Changelog.txt - Release Notes

*	DotNetSDK.SandcastleGUI - Tool to create the documentation of the PayPal Invoice SDK

*	LICENSE.txt - PayPal, Inc. SDK License

*	Installing NuGet in Visual Studio 2010 and 2012.pdf - Guide to Install NuGet in Visual Studio 2010 and 2012

*	Integrating NuGet with Visual Studio 2005 and 2008.pdf - Guide to Integrate NuGet with Visual Studio 2005 and 2008
