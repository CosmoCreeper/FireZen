<h1 align="center">🔥FireZEN</h1>
<p align="center">The only Zen with DRM support.</p>

## About
FireZEN is a way to modify Firefox into Zen by bringing all the JavaScript that makes up Zen into Firefox, but leaving binaries alone.
By doing this, you're left with a very Zen-like experience and you get to keep your DRM.
While this may seem amazing, there is a very high chance you will encounter bugs and you may even lose your data.
For this reason, we do not recommend that you try this unless you know what you're doing, and we do not take liability for any problems that arise along the way.

## Installation
There is only one method of installation as of right now, manual.

1. **Install Firefox and Zen:** FireZEN requires that both Firefox and Zen are installed on your machine, but don't get too attached to the Firefox that you install, because that's what we'll have to turn into Zen. You cannot just create a new profile for Firefox and hope the previous one remains just like the way you left it, as installing FireZEN on Firefox results in a global change to all profiles. Make note of the location of each of your browsers. Whatever Firefox version you choose to install has to be the same Firefox version that the Zen verison you're installing is built off of (as of right now in Twilight, it should be 147.0, but the release notes for Zen will tell you).
2. **Copy Zen's primary files:** The core things that must be edited here to have FireZEN are the omni.ja files and the xul.dll file. So navigate to your Zen Browser folder (e.g., `C:\Program Files\Zen Browser\`) and copy the `browser` folder, `xul.dll` file, and the `omni.ja` file from the root of the folder.
3. **Install the Zen files into Firefox:** Once you have copied Zen's primary files, navigate to Firefox's installation folder (e.g., `C:\Program Files\Mozilla Firefox\`) and paste it all in. Make sure to overwrite the original files and accept permissions.
4. **Install Sine:** Now that you have FireZEN's core functionality set up, there's only a few things you need to do, and the first of which is to install Sine. Sine can be installed from https://github.com/CosmoCreeper/Sine/ and the reason for this is so that you can install the FireZEN mod inside of it that fixes some bugs that it has.
5. **Launch FireZEN:** With FireZEN and Sine fully installed, you may now open up Firefox once more and see the new changes. The first thing that will happen is Firefox will open up with Zen's welcome page. If a dialog box appears asking if you want to make Zen the default browser and if you cannot escape the dialog box, press enter. From here, Firefox will launch, but we're not quite done yet.
6. **Install the FireZEN mod:** The next step is to install the FireZEN mod via Sine. This will fix a couple of styling issues and potentially functionality issues in the future. Simply navigate to the settings page, click on the Sine tab, then inside of the input box for a repository, input `CosmoCreeper/FireZen`, then click `Install`. Now you should see some styling bugs resolve themselves.
7. **Additional Setup:** The final steps are optional, but highly recommended. The first one is to right-click the toolbar and click `Customize Toolbar...`. Now, disable the second sidebar toggle button as it's from Firefox and not from Zen, and will be confusing. Secondly and finally, go to your settings page, the `General` tab, and scroll down to `Updates`. Here you will find the `Automatically install updates` toggle. Make sure to switch it to `Let me choose` as letting it update will constantly overwrite your FireZEN `omni.ja` files.

And that is all for FireZEN! Thank you for giving it a try!🔥
