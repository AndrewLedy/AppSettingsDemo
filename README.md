# AppSettingsDemo
Appsettings practice in .Net Core

Here You can find my notes for my Practice.

This solution is based on .Net Core 8 and latest at the time when I am working on this.


# The standard hirarchy of appsettings (from bottom to top, totally 5)

	-   AppSettings.json
	-	AppSettings.{customname}.json (Environment specific appsettins.json)
	-   User secrets (Not ideal for production)
	-   Environment variables (User, System, Hosted)
	-   Command line

That is AppSettings.json is out last place to look at.
However, this can be flipped which I will be practising on this. 
