---
layout: SiteMaster
---


The modern way to package up and deploy a CodeRush plugin, is through a VSIX package.

However there are many plugins available which have not yet been upgraded to take advantage of this facility.

### How to install older plugins - Abridged

 * Download the latest version of the plugin.
 * Place the plugin's .dll file in your 'Plugins' folder.
 * Restart Studio.

### How to install older plugins - Unabridged

 * Download the latest zip containing the latest version of the plugin that you wish to install. 
 * Locate your CodeRush '**Plugins**' folder.
     * Its current location can be determined from the **Core\Settings** options page.
     * This folder will most likely be a path like:
         * C:\Documents and Settings\YOURUSERNAME\My Documents\DevExpress\IDE Tools\Community\PlugIns
         * C:\Users\YOURUSERNAME\Documents\DevExpress\IDE Tools\Community\PlugIns
     * Your community plugin folder may have been reconfigured to be elsewhere.
 * Exit Visual Studio to ensure no files are locked.
 * Extract the plugin DLL from the zip file you downloaded, and save it in your community plugins folder.
 * Restart Visual Studio. The new plugin should be available. 

 
 
### FAQ

I installed my plugin, but it doesn't work. Why is this?

#### Is CodeRush Installed and operational?
CodeRush features are implemented so seemlessly that you can forget that CodeRush is even there. When setting up a new machine, it can be easy to forget to install until that moment where CodeRush or one of it's plugins fails to work. Crazy as it seems, you should check that CodeRush is actually instaled and running before proceeding further down this list. :)

#### Is your plugin dll in the correct location?
The default location for older plugins is:

    C:\Users\USERNAME\Documents\DevExpress\IDE Tools\Community\Plugins
    
This can of course be changed. To discover your current plugin folder visit **CodeRush Options: Core\Settings**. The 2nd option on this page will give you your plugin folder. Please ensure that your plugin dll and any dependancies are located here.

#### Have you restarted Visual Studio since installing your plugin?
Restarting Studio causes CodeRush to restart as well. This can give both the chance to reinitialize. 

#### Has CodeRush loaded your plugin dll?
- Visit **CodeRush Options: Core\Plug-in Manager (Level: Expert)**
- Locate your plugin by name in this list.
- Locate the **Load State** column
- Is your plugin listed as Loaded?

If your plugin is not loaded, there might be a problem with the plugin.

If your plugin is not listed then it might have been blocked by your OS (see next point)

#### Is your plugin blocked?
Some versions of windows attempt to block the use of dlls that have come from another computer by default.

In these cases you will need to unblock them.

 * Right-click the plugin DLL, select "Properties," and on the "General" tab, click the "Unblock" button. 
 * Alternatively try [this blog post](http://www.paraesthesia.com/archive/2010/05/19/unblocking-multiple-files-at-once.aspx)
     
#### Is your plugin enabled?
Some plugins ship disabled by default. Check their documentation for details on how to turn them on.

#### Does the plugin require additional configuration?
Check your plugin's documentation. Is there any additional configuration

#### Does your plugin require Templates?
Some plugins ship with a set of Templates that will need to be imported. check the Zip file your plugin shipped in.
