Soluntion Name: FourOFour
Architecture: Helix
Sitecore version : Sitecore 9 Update 1 (9.0.171219)

Add the following Nuget Feed before you build:
1. Go to  Tools --> Nuget Package Manager --> Package Manager Settings
2. Select Package Sources and add the following nuget feed:
	Name: Sitecore Ofiicial
	Source: https://sitecore.myget.org/F/sc-packages/api/v3/index.json

	 
Binding/Site URL: http://sc90.local/sitecore (you can have a different one as well)

Note: Add references to project using "Manage NuGet Packages for Solution"