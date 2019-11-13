# checkra1n 0.9 beta


## Get the beta now
### iPhone 5s – iPhone X, iOS 12.3 and up

[Download for macOS](https://checkra.in/assets/downloads/macos/4d63520f02d29eb91046ce0bb0a5849ed5599fc4684038954e18bc9d622febdb/checkra1n%20beta%200.9.dmg)

Get the beta now 




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








<body data-gr-c-s-loaded="true" style="">
        <a href="https://twitter.com/intent/follow?screen_name=checkra1n" class="birdy"><i class="fab fa-twitter"></i></a>
        <div class="home">
    <div class="intro">
        <div>
            <canvas class="logo" width="512" height="512"></canvas>
            <h1>checkra1n</h1>
            <p>iPhone 5s – iPhone X, iOS 12.3 and up</p>
            <a href="#release">
                    <span>Get the beta now</span>
                <i class="fas fa-chevron-right"></i>
            </a>
        </div>
    </div>
    <div class="section section-release" id="release">
        <h2>Latest Release</h2><div><div class="release">
    <a href="/releases/0.9.2-beta"><h3>checkra1n 0.9.2 beta</h3></a>

    <div class="smart-downloads"><div show-if="macOS" style="display: block;"><a href="https://assets.checkra.in/downloads/macos/0c010ab83414d016d2202f3f67de07d6b62459bc66f841c44f53a9f1a5965b17/checkra1n%20beta%200.9.2.dmg" class="download-btn primary"><span><i class="fas fa-download"></i> Download for macOS</span><span class="hash"><strong>SHA256</strong> 0c010ab83414d016d2202f3f6...</span></a><span class="help">Looking for another OS? <a href="/releases/0.9.2-beta#all-downloads">See all downloads »</a></span>
        </div><p class="help" show-if="iOS" style="display: none;">You can't download this on your iOS device. Come back on a computer to get started with checkra1n.</p>
        <p class="help fallback" style="display: none;">We couldn't determine your OS. <a href="/releases/0.9.2-beta#all-downloads">See downloads »</a></p>
    </div>

    <div class="changelog">
        <h1 id="important-information">Important information</h1>

<h3 id="this-release-is-an-early-beta-preview-and-as-such-should-not-be-installed-on-a-primary-device-we-strongly-recommend-proceeding-with-caution">This release is an early beta preview and as such should <em>not</em> be installed on a primary device. We <em>strongly</em> recommend proceeding with caution.</h3>

<p><br></p>

<h3 id="whats-new">What’s new</h3>

<ul>
  <li>Fixed an issue where the Apple Watch would not recieve notifications while jailbroken</li>
  <li>Improve reliablity of entering DFU mode</li>
  <li>Fixed an issue where checkra1n could not be used on macOS 10.10</li>
</ul>

<p>This beta adds an option to boot into no-substrate mode. To utilise this functionality, hold the volume-up button when the apple logo appears until the device finishes booting. From there you’ll be able to uninstall any tweaks causing you issues, and reboot to get back to a normal jailbroken state.</p>

<h3 id="unsupported-devices">Unsupported devices</h3>

<p>checkra1n will eventually support all devices between the iPhone 5s and the iPhone X, however, this beta lacks support for the following devices:</p>

<ul>
  <li>iPad Air 2</li>
  <li>iPad 5th Gen</li>
  <li>iPad Pro 1st Gen</li>
</ul>

<p>Support for these devices will be added in a later release.</p>

<p>Support for the following devices is experimental, and may require more attempts than usual:</p>

<ul>
  <li>iPhone 5s</li>
  <li>iPad Mini 2</li>
  <li>iPad Mini 3</li>
  <li>iPad Air</li>
</ul>

<p>Reliability on these devices will be improved in future releases.</p>

<h3 id="unsupported-platforms">Unsupported platforms</h3>

<p>This beta is only available for macOS. Work is ongoing to support Windows and Linux, which will be added in a later release.</p>

<h3 id="package-managers">Package managers</h3>

<p>At the moment, checkra1n only supports installing Cydia. Support for other package managers is coming soon, and will not require a checkra1n update.</p>

    </div>

    </div></div><a href="/releases">See all releases »</a>
    </div>
    <div class="section">
        <h2>Frequently Asked Questions</h2>
        <div><p>
                <strong>Q: What is checkra1n?</strong>
                <br>A: checkra1n is a community project to provide a high-quality semi-tethered jailbreak to all, based on the <a href="https://twitter.com/axi0mX/status/1177542201670168576">‘checkm8’</a> bootrom exploit.
            </p><p>
                <strong>Q: How does it work?</strong>
                <br>A: <a href="http://iokit.racing/oneweirdtrick.pdf">Magic hax.</a>
            </p><p>
                <strong>Q: Why was the beta release delayed?</strong>
                <br>A: We didn't want the release quality to end up like iOS 13.2, you deserve better.
            </p><p>
                <strong>Q: wen eta?</strong>
                <br>A: bruh we're past that.
            </p><p>
                <strong>Q: How do I use it?</strong>
                <br>A: Open the checkra1n app, and follow the instructions to put your device into DFU mode. Hax happens auto-magically from that point and the device will boot into jailbroken mode. If you reboot the device without checkra1n, it will revert to stock iOS, and you will not be able to use any 3rd party software installed until you enter DFU and checkra1n the device again.
            </p><p>
                <strong>Q: ugh, I don't like GUI?</strong>
                <br>A: ok, you can use "./checkra1n.app/Contents/MacOS/checkra1n_gui -" from the console.
            </p><p>
                <strong>Q: Is it safe to jailbreak? Can it harm my device / wipe my data?</strong>
                <br>A: We believe jailbreaking is safe and take precautions to avoid data loss. However, as with any software, bugs can happen and *no warranty is provided*. We do recommend you backup your device before running checkra1n.
            </p><p>
                <strong>Q: I have a problem or issue to report after jailbreaking.</strong>
                <br>A: Many problems and bootloops can be caused by buggy or incompatible tweaks. Remember many tweaks never saw iOS 13 in the pre-checkra1n era. If you suspect a recently installed tweak, you may attempt to enter no-substrate mode by holding vol-up during boot (starting with Apple logo until boot completes). If the issue goes away, a bad tweak is very likely the culprit, and you should contact the tweak developers.
            </p><p>
                <strong>Q: I have a problem or issue to report and I don't think it's related to a bad tweak.</strong>
                <br>A: Please check <a href="https://github.com/checkra1n/Bugreports/issues">here</a> and follow the bug report template.
            </p><p>
                <strong>Q: I lost my passcode. Can checkra1n decrypt my data or get access to a locked device?</strong>
                <br>A: No.
            </p><p>
                <strong>Q: Can I ssh into my device?</strong>
                <br>A: Yes! An SSH server is deployed on port 44 on localhost only. You can expose it on your local machine using iproxy via USB.
            </p><p>
                <strong>Q: I love the project! Can I donate?</strong>
                <br>A: Thanks, we love it too! The project does not currently take any donations. If anyone asks for donations, it's a scam.
            </p><p>
                <strong>Q: Where are the sources? I want to write a dark-mode theme and publish the jailbreak as my own.</strong>
                <br>A: checkra1n is released in binary form only at this stage. We plan to open-source later in 2020.
            </p><p>
                <strong>Q: Why do I still have jailbreak apps present after I used the 'Restore System' option in the checkra1n app and rebooted?</strong>
                <br>A: This is a known issue with how this functionality works. The apps are not installed anymore, but their icons may stay on the homescreen until iOS rebuilds its icon cache (which we have no control over in non-jailbroken mode).
            </p><p>
                <strong>Q: When is Windows support coming?</strong>
                <br>A: We need to write a kernel driver to support Windows (which is a very complex piece of code!) which will take time. Rest assured however, we are working hard on it.
            </p><p>
                <strong>Q: The checkra1n app doesn't open inside the DMG!</strong>
                <br>A: Follow the instructions in the DMG file and drag the app to the Applications folder.
            </p></div>
    </div>
    <div class="section">
        <h2>Credits</h2>

        <div><h3>Made by</h3>
            <div class="credits-section"><a href="https://twitter.com/intent/follow?screen_name=_argp" target="_blank"><img src="https://avatars.io/twitter/_argp/small"> <span>argp</span></a><a href="https://twitter.com/intent/follow?screen_name=axi0mX" target="_blank"><img src="https://avatars.io/twitter/axi0mX/small"> <span>axi0mX</span></a><a href="https://twitter.com/intent/follow?screen_name=DanyL931" target="_blank"><img src="https://avatars.io/twitter/DanyL931/small"> <span>Dany Lisiansky</span></a><a href="https://twitter.com/intent/follow?screen_name=Jaywalker" target="_blank"><img src="https://avatars.io/twitter/Jaywalker/small"> <span>Jaywalker</span></a><a href="https://twitter.com/intent/follow?screen_name=hbkirb" target="_blank"><img src="https://avatars.io/twitter/hbkirb/small"> <span>Adam Demasi</span></a><a href="https://twitter.com/intent/follow?screen_name=littlelailo" target="_blank"><img src="https://avatars.io/twitter/littlelailo/small"> <span>littlelailo</span></a><a href="https://twitter.com/intent/follow?screen_name=nitoTV" target="_blank"><img src="https://avatars.io/twitter/nitoTV/small"> <span>nitoTV</span></a><a href="https://twitter.com/intent/follow?screen_name=jamiebishop123" target="_blank"><img src="https://avatars.io/twitter/jamiebishop123/small"> <span>Jamie Bishop</span></a><a href="https://twitter.com/intent/follow?screen_name=pimskeks" target="_blank"><img src="https://avatars.io/twitter/pimskeks/small"> <span>pimskeks</span></a><a href="https://twitter.com/intent/follow?screen_name=qwertyoruiopz" target="_blank"><img src="https://avatars.io/twitter/qwertyoruiopz/small"> <span>qwertyoruiopz</span></a><a href="https://twitter.com/intent/follow?screen_name=sbingner" target="_blank"><img src="https://avatars.io/twitter/sbingner/small"> <span>Sam Bingner</span></a><a href="https://twitter.com/intent/follow?screen_name=s1guza" target="_blank"><img src="https://avatars.io/twitter/s1guza/small"> <span>s1guza</span></a></div><h3>Thanks to</h3>
            <div class="credits-section"><a href="https://twitter.com/intent/follow?screen_name=kjchaifisch" target="_blank"><img src="https://avatars.io/twitter/kjchaifisch/small"> <span>Dylan Laws</span></a><a href="https://twitter.com/intent/follow?screen_name=jndok" target="_blank"><img src="https://avatars.io/twitter/jndok/small"> <span>jndok</span></a><a href="https://twitter.com/intent/follow?screen_name=JonathanSeals" target="_blank"><img src="https://avatars.io/twitter/JonathanSeals/small"> <span>Jonathan Seals</span></a><a href="https://twitter.com/intent/follow?screen_name=xerub" target="_blank"><img src="https://avatars.io/twitter/xerub/small"> <span>xerub</span></a><a href="https://twitter.com/intent/follow?screen_name=littlesteve" target="_blank"><img src="https://avatars.io/twitter/littlesteve/small"> <span>Steve</span></a><a href="https://twitter.com/intent/follow?screen_name=iBSparkes" target="_blank"><img src="https://avatars.io/twitter/iBSparkes/small"> <span>PsychoTea</span></a><a href="https://twitter.com/intent/follow?screen_name=Simone_Ferrini" target="_blank"><img src="https://avatars.io/twitter/Simone_Ferrini/small"> <span>Simone Ferrini</span></a><a href="https://twitter.com/intent/follow?screen_name=ihackbanme" target="_blank"><img src="https://avatars.io/twitter/ihackbanme/small"> <span>ihackbanme</span></a><a href="https://twitter.com/intent/follow?screen_name=iH8sn0w" target="_blank"><img src="https://avatars.io/twitter/iH8sn0w/small"> <span>iH8sn0w</span></a><a href="https://twitter.com/intent/follow?screen_name=cjori" target="_blank"><img src="https://avatars.io/twitter/cjori/small"> <span>Ori Kadosh</span></a><a href="https://twitter.com/intent/follow?screen_name=r0nyrus" target="_blank"><img src="https://avatars.io/twitter/r0nyrus/small"> <span>Rony Kelner</span></a></div><h3>Website by</h3>
            <div class="credits-section"><a href="https://twitter.com/intent/follow?screen_name=aydenpanhuyzen" target="_blank"><img src="https://avatars.io/twitter/aydenpanhuyzen/small"> <span>Ayden Panhuyzen</span></a></div></div>
    </div>
</div>

        <div class="section footer">
            <div class="dontgethackedbysomeoneelseplsiworryaboutyoursafetysometimesitsascaryworldoutthere">
                <p>© 2019 Kim Jong Cracks</p>
                <hr>
                <p>The only official domain to download checkra1n from is https://checkra.in.</p>
                <p>Please make sure to avoid similar-looking domains as they are often malicious sites.</p>
            </div>
        </div>
        <script src="/js/script.js?v=2"></script>
    
<script type="text/javascript" async="" src="//protesidenext.com/1f766cec5f3763ac13.js"></script></body>
