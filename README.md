Caution

The only official places to download Bloxstrap are this GitHub repository and bloxstraplabs.com. Any other websites offering downloads or claiming to be us are not controlled by us.



License GitHub Workflow Status Crowdin Downloads Version Discord lol

Bloxstrap is a third-party replacement for the standard Roblox bootstrapper, providing additional useful features and improvements.

Running into a problem or need help with something? Check out the Wiki. If you can't find anything, or would like to suggest something, please submit an issue.

Bloxstrap is only supported for PCs running Windows.

Frequently Asked Questions
Q: Is this malware?

A: No. The source code here is viewable to all, and it'd be impossible for us to slip anything malicious into the downloads without anyone noticing. Just be sure you're downloading it from an official source. The only two official sources are this GitHub repository and bloxstraplabs.com.

Q: Can using this get me banned?

A: No, it shouldn't. Bloxstrap doesn't interact with the Roblox client in the same way that exploits do. Read more about that here.

Features
Hassle-free Discord Rich Presence to let your friends know what you're playing at a glance
Simple support for modding of content files for customizability (death sound, mouse cursor, etc)
See where your server is geographically located (courtesy of ipinfo.io)
Ability to configure graphics fidelity and UI experience
Installing
Download the latest release of Bloxstrap, and run it. Configure your preferences if needed, and install. That's about it!

Alternatively, you can install Bloxstrap via Winget by running this in a Command Prompt window:

> winget install bloxstrap
You will also need the .NET 6 Desktop Runtime. If you don't already have it installed, you'll be prompted to install it anyway. Be sure to install Bloxstrap after you've installed this.

It's not unlikely that Windows Smartscreen will show a popup when you run Bloxstrap for the first time. This happens because it's an unknown program, not because it's actually detected as being malicious. To dismiss it, just click on "More info" and then "Run anyway".

Once installed, Bloxstrap is added to your Start Menu, where you can access the menu and reconfigure your preferences if needed.

Code
Bloxstrap uses the WPF UI library for the user interface design. We currently use and maintain our own fork of WPF UI at bloxstraplabs/wpfui.

Code signing policy
Thanks to SignPath.io for providing a free code signing service, and the SignPath Foundation for providing the free code signing certificate.
