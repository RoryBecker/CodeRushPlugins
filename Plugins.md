---
layout: SiteMaster
---
### Plugin Locations
CodeRush plugins can be found all over the place, but they tend to congregate in 3 locations in particular.

#### Community Site
The original site for Community CodeRush plugins. this site was created back in the day, when the best source control available appeared to be SVN. 
The site hosted all plugins that were contributed to it in a single repository, which made many things difficult, but at the time there appeared to be no obvious better approach.
Plugins based here are still maintained but new plugins are unlikely to be stored here since better options have become available.

#### Visual Studio Gallery
Later it was suggested that certain plugins would benefit from being show cased in a more well known setting. By this time we had developed the facility to create plugins which would install via VSIX. This meant that we could use the Visual Studio Gallery to host VSIX versions of some plugins.
In addition to the stated benefits, plugins can be discovered from within Visual studio itself. 
Therefore we have some [CodeRush plugins hosted on the Visual Studio Gallery](http://visualstudiogallery.msdn.microsoft.com/site/search?query=CodeRush&f[0].Value=CodeRush%20&f[0].Type=SearchText&ac=4)

#### GitHub.com
Most recently I (Rory) have transitioned to using git for most source control. I find it very flexible and never seems to get in my way. 
I started storing my newer plugins in git repositories (one plugin to a repo). After that the natural next-step seemed to be to host them on github.com

Hosting my plugins in this manner has a number of benefits. 
 
 # Plugin repos can be forked (copied) *without needing any explicit permission*.
 # Anyone can make a pull request (improve code and offer it back) *without needing any explicit permission*.
 # github.com has *releases*. Tags to which you can attach binaries etc which eases the process of distribution. I typically attach the VSIX directly to the release.
 
 ...and I'm sure there are other benefits as well.

 Therefore you can now also typically find [*My* plugins on github](https://github.com/search?q=CodeRush++user%3ARoryBecker&type=Repositories&ref=advsearch&l=
 
 (https://github.com/RoryBecker/CR_ExtractMethodAndInlineLiterals)
 (https://github.com/RoryBecker/CR_CleanupFileAndNamespaces)
 (https://github.com/RoryBecker/CR_TemplateExpandWithCollapsedRegions)
 (https://github.com/RoryBecker/CR_RemoveQuotesFromString)
 (https://github.com/RoryBecker/CR_XMLNavapsedRegions)
 (https://github.com/RoryBecker/CR_RenameFileSync)
 (https://github.com/RoryBecker/CR_Fader)
 (https://github.com/RoryBecker/CR_WrapInTryFunction)
 (https://github.com/RoryBecker/CR_PreventDeleteCollapsedCode)
 (https://github.com/RoryBecker/CR_TemplateByExample)
 
 