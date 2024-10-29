---
title: "EmEditor's Shortcut-Mapped Macro Issue: Potential Bugs Detected and Solutions Explored"
date: 2024-10-21T16:33:03.436Z
updated: 2024-10-29T03:52:18.090Z
tags:
  - product
categories:
  - emeditor
thumbnail: https://thmb.techidaily.com/0cd373a6b0eece48a6e2d5d0248da5d1df8fff3f71196cdaae4af6176a3b33bf.jpg
---

## EmEditor's Shortcut-Mapped Macro Issue: Potential Bugs Detected and Solutions Explored

Tagged: [bug](https://tools.techidaily.com/emeditor/products/), [macro](https://tools.techidaily.com/emeditor/products/), [shortcut](https://tools.techidaily.com/emeditor/products/)

Viewing 4 posts - 1 through 4 (of 4 total)

* Author  
Posts
* October 27, 2017 at 5:39 am [#22587](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/21bf85a5da27278c7f73ff85a8eb81ab?s=80&d=identicon&r=g)LifeTimer](https://www.emeditor.com/forums/users/lifetimer/ "View LifeTimer's profile")  
Participant  
I just found a serious bug regarding macros mapped to shortcuts.  
I have several such mappings configured in my EmEditor, and when I create and insert a new macro and insert it before any such shortcut-mapped macros, all mappings of shortcuts to macros that are **after it** in the defined macro order (i.e. the order in which the macros appear in the macro toolbar and the “Customize macros” dialog box) will shift, i.e. the shortcut mappings of those will now point to other macros than before!  
This is very dangerous (depending on what the macros do of course), and it is seemingly because the mappings of the shortcuts point at _indexes_ in the macro list, rather than the macro items/files in the list themselves (i.e. no matter if they are moved in the list or not. in this case by having other macros inserted before them).  
This should probably be fixed ASAP in order to avoid accidents that may cause data loss for customers.  
October 27, 2017 at 5:53 am [#22588](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/b5695857a6ecfde5db964f5b842293d1?s=80&d=identicon&r=g)Patrick C](https://www.emeditor.com/forums/users/patrick-c/ "View Patrick C's profile")  
Participant  
Are you using the latest version (17.2.2)?  
As far as I can remember this was one of the early v17.0 perhaps also v17.1 bugs which were fixed with ≈ v17.1 or v17.2.  
I btw just re-tested on v17.2.2 – in my case this error doesn’t occur.  
October 27, 2017 at 6:03 am [#22589](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/21bf85a5da27278c7f73ff85a8eb81ab?s=80&d=identicon&r=g)LifeTimer](https://www.emeditor.com/forums/users/lifetimer/ "View LifeTimer's profile")  
Participant  
Thanks, I was running 17.1.3.  
I just upgraded though, and then I found an apparently other bug that made the macro shortcuts stop working completely. :-(
I had a macro mapped to ctrl+i and another mapped to ctrl+u for example. When I try these (in cell mode) now, the only thing that happens is that the cell that is currently selected goes into “edit mode” and is also emptied. The shortcuts don’t even show up in the “Keyboard” config dialog anymore, are they completely deleted now? :-(
Please take a look at this as soon as possible, since I now cannot run macros at all after this upgrade to 17.2.2.  
October 27, 2017 at 6:55 am [#22590](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/b5695857a6ecfde5db964f5b842293d1?s=80&d=identicon&r=g)Patrick C](https://www.emeditor.com/forums/users/patrick-c/ "View Patrick C's profile")  
Participant  
Now I recall – I had to reassign the macro shortcuts after the bug was fixed.  
In my case this wasn’t too bad an issue as I have a list of my custom shortcut settings. EmEditor isn’t the only program where my custom shortcuts got reset after updating (LibreOffice was another recent one) so over time I learnt – it remains annoying nevertheless.
* Author  
Posts

Viewing 4 posts - 1 through 4 (of 4 total)

* You must be logged in to reply to this topic.

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>

<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-share.techidaily.com/new-youtube-as-a-learning-tool-insider-advice-for-teachers/"><u>[New] YouTube as a Learning Tool Insider Advice for Teachers</u></a></li>
<li><a href="https://win-bits.techidaily.com/aomei-data-security-update-log-enhancements-and-fixes/"><u>AOMEI Data Security Update Log: Enhancements and Fixes</u></a></li>
<li><a href="https://win-bits.techidaily.com/comprehensive-walkthrough-restoring-default-settings-via-windows-factory-reset-on-the-chuwi-hi10-laptop/"><u>Comprehensive Walkthrough: Restoring Default Settings via Windows Factory Reset on the Chuwi Hi10 Laptop</u></a></li>
<li><a href="https://tech-haven.techidaily.com/crypto-insights-unlocked-top-5-gpt-trading-tools/"><u>Crypto Insights Unlocked: Top 5 GPT Trading Tools</u></a></li>
<li><a href="https://extra-tips.techidaily.com/elevate-your-cinematography-through-portable-luts/"><u>Elevate Your Cinematography Through Portable LUTs</u></a></li>
<li><a href="https://win-bits.techidaily.com/fixing-the-issue-when-microsoft-word-fails-in-office-365/"><u>Fixing the Issue When Microsoft Word Fails in Office 365</u></a></li>
<li><a href="https://win-bits.techidaily.com/four-effective-strategies-for-retrieving-data-from-ransomware-attacks/"><u>Four Effective Strategies for Retrieving Data From Ransomware Attacks</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-do-vivo-y27s-screen-sharing-drfone-by-drfone-android/"><u>In 2024, How To Do Vivo Y27s Screen Sharing | Dr.fone</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-is-gsm-flasher-adb-legit-full-review-to-bypass-your-honor-90-gtfrp-lock-by-drfone-android/"><u>In 2024, Is GSM Flasher ADB Legit? Full Review To Bypass Your Honor 90 GTFRP Lock</u></a></li>
<li><a href="https://win-bits.techidaily.com/losungen-zum-speichern-auf-dem-netzlaufwerk/"><u>Lösungen Zum Speichern Auf Dem Netzlaufwerk</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/revamped-policies-and-tandu-your-guide/"><u>Revamped Policies & T&U: Your Guide</u></a></li>
<li><a href="https://win-bits.techidaily.com/schlusselstrategien-fur-das-wiederherstellen-von-systemen-beseitigung-der-rucksetzprobleme-bei-windows-11/"><u>Schlüsselstrategien Für Das Wiederherstellen Von Systemen: Beseitigung Der Rücksetzprobleme Bei Windows 11</u></a></li>
<li><a href="https://win-help.techidaily.com/seamless-m4a-to-wma-file-conversion-techniques-for-optimal-audio-quality/"><u>Seamless M4A to WMA File Conversion Techniques for Optimal Audio Quality</u></a></li>
<li><a href="https://win-bits.techidaily.com/top-3-fixes-pour-resoudre-les-problemes-de-sauvegarde-sous-windows-10-8-et-7/"><u>Top 3 Fixes Pour Résoudre Les Problèmes De Sauvegarde Sous Windows 10, 8 Et 7</u></a></li>
<li><a href="https://win-bits.techidaily.com/ultimate-tutorial-full-reboot-of-your-pc-using-windows-11s-built-in-feature/"><u>Ultimate Tutorial: Full Reboot of Your PC Using Windows 11'S Built-In Feature</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/unveiling-samsungs-tech-masterpiece-buds-pro-review/"><u>Unveiling Samsung's Tech Masterpiece: Buds Pro Review</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/why-apple-airtag-is-the-number-one-choice-for-iphone-users-a-detailed-review/"><u>Why Apple AirTag Is the Number One Choice for iPhone Users: A Detailed Review</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2136536/16384" target="_top" id="2136536">
  <img src="//a.impactradius-go.com/display-ad/16384-2136536" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ursime.pxf.io/i/5597632/2136536/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

