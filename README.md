This repository contains .NET SDK and samples for PayPal Invoice API.

Prerequisites:
--------------
*	Visual Studio 2005 or higher

SDK Integration:
----------------
*	Create a new ASP.NET Web Application with appropriate web application and solution name

*	Add reference to 'PayPal_Invoicing_SDK.dll' from the 'lib' folder in 'PayPal_Invoicing_SDK' project

*	Add reference to 'PayPal_Core_SDK.dll' from the 'lib' folder in 'PayPal_Invoicing_SDK' project

*	Namespaces to be used
	�	PayPal
	�	PayPal.Invoice
	�	PayPal.Invoice.Model
	�	PayPal.Permissions
	�	PayPal.Permissions.Model
	�	PayPal.Util
	�	PayPal.Exception
 
Web.config:
-----------
Please refer to the sample web.config file in 'InvoicingSampleApp' sample application to configure the following
 
*	Configuration Sections
	�	paypal
	�	log4net

*	PayPal Settings
	�	endpoint
	�	connectionTimeout
	�	requestRetries
	�	IPAddress
	�	sandboxEmailAddress

*	PayPal (Multiple) Accounts API credentials
	�	apiUsername
	�	apiPassword
	�	applicationId
	�	apiSignature
	�	apiCertificate
	�	privateKeyPassword

Tools:
------
*	log4net.dll - included in 'lib' folder in 'PayPal_AdaptiveAccounts_SDK' project
	log4net is a tool to help output log statements to a variety of output targets.