---
layout: SiteMaster
---
### Recent Plugins
 
 * [CR_TemplateImporter](https://github.com/RoryBecker/CR_TemplateImporter) - Imports CodeRush templates direct from the web.
 * [CR_IntroduceLocalAllArguments](https://github.com/RoryBecker/CR_IntroduceLocalAllArguments) - Provides a new command to expand a template and then collapsing any regions it might generate.
 * [CR_TemplateExpandWithCollapsedRegions](https://github.com/RoryBecker/CR_TemplateExpandWithCollapsedRegions) - Provides a new command to expand a template and then collapsing any regions it might generate.
 * [CR_ExtractMethodAndInlineLiterals](https://github.com/RoryBecker/CR_ExtractMethodAndInlineLiterals) - Extracts all literals in the selected code, then extracts the code, before inlining the literals again.
 * [CR_CleanupFileAndNamespaces](https://github.com/RoryBecker/CR_CleanupFileAndNamespaces) - Executes the CleaupFile action and OptimizeNamespace rafactorings in sequence.
 * [CR_RemoveQuotesFromString](https://github.com/RoryBecker/CR_RemoveQuotesFromString) - One step command to remove the initial and trailing double quotes from around a string literal.
 * [CR_XMLNav](https://github.com/RoryBecker/CR_XMLNav) - Provides enhanced navigation within XML files.
 * [CR_RenameFileSync](https://github.com/RoryBecker/CR_RenameFileSync) - Hooks the CodeRush rename refactoring and renames the corresponding file at the same time.
 * [CR_Fader](https://github.com/RoryBecker/CR_Fader) - Reduces the visibility of lines that start with certain prefixes. ie ' TODO
 * [CR_WrapInTryFunction](https://github.com/RoryBecker/CR_WrapInTryFunction) - Generates a method that wraps the active method, in the same way that 'TryParse' wraps 'Parse'.
 * [CR_PreventDeleteCollapsedCode](https://github.com/RoryBecker/CR_PreventDeleteCollapsedCode) - Attempts to prevent the usefrom deleting code which contains a collapsed comment.
 * [CR_TemplateByExample](https://github.com/RoryBecker/CR_TemplateByExample) - CodeRush plugin designed to help create simple templates.
 
 
### Where else can I find more CodeRush plugins?
CodeRush plugins can be found all over the place, but they tend to congregate in 3 locations in particular.

#### The DXCore Community Site
The [original site for Community CodeRush plugins](http://code.google.com/p/dxcorecommunityplugins/). This site was created back in the day, when the best source control available appeared to be SVN. 
The site hosted all plugins that were contributed to it in a single repository, which made many things difficult, but at the time there appeared to be no obvious better approach.
Plugins based here are still maintained but new plugins are unlikely to be stored here since better options have become available.

#### Visual Studio Gallery
Later it was suggested that certain plugins would benefit from being showcased in a more prominent setting. By this time we had developed the facility to create plugins which would install via VSIX. This meant that we could use the Visual Studio Gallery to host VSIX versions of some plugins.

Therefore we have some [CodeRush plugins hosted on the Visual Studio Gallery](http://visualstudiogallery.msdn.microsoft.com/site/search?query=CodeRush%20Plugin&f[0].Value=CodeRush%20Plugin&f[0].Type=SearchText&ac=4)

In addition, plugins can be discovered from within Visual studio itself. (Tools\Extensions and Updates)

#### GitHub.com
Most recently I (Rory) have transitioned to using git for most source control. I find it very flexible and never seems to get in my way. 
I started storing my newer plugins in git repositories (one plugin to a repo). After that the natural next-step seemed to be to host them on github.com

Hosting my plugins in this manner has a number of benefits. 
 
 * Plugin repos can be forked (copied) __without needing any explicit permission__.
 * Anyone can make a pull request (improve code and offer it back) __without needing any explicit permission__.
 * [github.com](http://github.com) has __releases__. Tags to which you can attach binaries etc which eases the process of distribution. I typically attach the VSIX directly to the release.
 
...and I'm sure there are other benefits as well.

Therefore you can now also typically find [__My__ plugins on github](https://github.com/search?q=CodeRush++user%3ARoryBecker&type=Repositories&ref=advsearch&l=)
