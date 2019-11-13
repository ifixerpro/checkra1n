# checkra1n 0.9 beta
### iPhone 5s – iPhone X, iOS 12.3 and up


![Image](https://media.idownloadblog.com/wp-content/uploads/2019/10/checkra1n.jpg)


[Download for macOS](https://checkra.in/assets/downloads/macos/4d63520f02d29eb91046ce0bb0a5849ed5599fc4684038954e18bc9d622febdb/checkra1n%20beta%200.9.dmg)





## Important information

This release is an early beta preview and as such should not be installed on a primary device. We strongly recommend proceeding with caution.


Unsupported devices
checkra1n will eventually support all devices between the iPhone 5s and the iPhone X, however, this release candidate lacks support for the following devices:

iPad Air 2
iPad 5th Gen
iPad Pro 1st Gen
Support for these devices will be added in a later release.

Support for the following devices is experimental, and may require more attempts than usual:

iPhone 5s
iPad Mini 2
iPad Mini 3
iPad Air
To test on these devices, run the checkra1n app with ./checkra1n.app/Contents/MacOS/checkra1n_gui - to run the CLI.

Reliability on these devices will be improved in future releases.

Unsupported platforms
This beta is only available for macOS. Work is ongoing to support Windows and Linux, which will be added in a later release.

Package managers
At the moment, checkra1n only supports installing Cydia. Support for other package managers is coming soon, and will not require a checkra1n update.





## Frequently Asked Questions

Q: What is checkra1n?
A: checkra1n is a community project to provide a high-quality semi-tethered jailbreak to all, based on the ‘checkm8’ bootrom exploit.

Q: How does it work?
A: Magic hax.

Q: Why was the beta release delayed?
A: We didn't want the release quality to end up like iOS 13.2, you deserve better.

Q: wen eta?
A: bruh we're past that.

Q: How do I use it?
A: Open the checkra1n app, and follow the instructions to put your device into DFU mode. Hax happens auto-magically from that point and the device will boot into jailbroken mode. If you reboot the device without checkra1n, it will revert to stock iOS, and you will not be able to use any 3rd party software installed until you enter DFU and checkra1n the device again.

Q: ugh, I don't like GUI?
A: ok, you can use "./checkra1n.app/Contents/MacOS/checkra1n_gui -" from the console.

Q: Is it safe to jailbreak? Can it harm my device / wipe my data?
A: We believe jailbreaking is safe and take precautions to avoid data loss. However, as with any software, bugs can happen and *no warranty is provided*. We do recommend you backup your device before running checkra1n.

Q: I have a problem or issue to report.
A: Please check here and follow the bug report template.

Q: I lost my passcode. Can checkra1n decrypt my data or get access to a locked device?
A: No.

Q: Can I ssh into my device?
A: Yes! An SSH server is deployed on port 44 on localhost only. You can expose it on your local machine using iproxy via USB.

Q: I love the project! Can I donate?
A: Thanks, we love it too! The project does not currently take any donations. If anyone asks for donations, it's a scam.

Q: Where are the sources? I want to write a dark-mode theme and publish the jailbreak as my own.
A: checkra1n is released in binary form only at this stage. We plan to open-source later in 2020.

Q: Why do I still have jailbreak apps present after I used the 'Restore System' option in the checkra1n app and rebooted?
A: This is a known issue with how this functionality works. The apps are not installed anymore, but their icons may stay on the homescreen until iOS rebuilds its icon cache (which we have no control over in non-jailbroken mode).

Q: When is Windows support coming?
A: We need to write a kernel driver to support Windows (which is a very complex piece of code!) which will take time. Rest assured however, we are working hard on it.

Q: The checkra1n app doesn't open inside the DMG!
A: Follow the instructions in the DMG file and drag the app to the Applications folder.

<link rel="shortcut icon" type="image/x-icon" href="favicon.ico">
