---
title: "EmEditor's Shortcut-Mapped Macro Issue: Potential Bugs Detected and Solutions Explored"
date: 2024-10-16T12:49:57.624Z
updated: 2024-10-16T16:09:40.002Z
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
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-earn-more-maximizing-income-through-youtube-mobile-advertising/"><u>[New] 2024 Approved Earn More Maximizing Income Through YouTube Mobile Advertising</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-increasing-onscreen-detail-in-virtual-spaces/"><u>[Updated] Increasing Onscreen Detail in Virtual Spaces</u></a></li>
<li><a href="https://win-bits.techidaily.com/1-problemenfrei-hochladen-von-fotos-auf-ihrem-iphone/"><u>1. Problemenfrei Hochladen Von Fotos Auf Ihrem iPhone</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-key-iphone-photography-utilities-for-watermarking/"><u>2024 Approved Key iPhone Photography Utilities for Watermarking</u></a></li>
<li><a href="https://win-bits.techidaily.com/adding-songs-from-your-computer-to-apples-icloud-music-library-a-step-by-step-guide/"><u>Adding Songs From Your Computer to Apple's iCloud Music Library - A Step-by-Step Guide</u></a></li>
<li><a href="https://app-tips.techidaily.com/anthropic-unveils-the-next-generation-of-enterprise-scale-ai-with-its-advanced-claude-initiative-insights-from-zdnet/"><u>Anthropic Unveils the Next Generation of Enterprise-Scale AI with Its Advanced Claude Initiative - Insights From ZDNet</u></a></li>
<li><a href="https://win-bits.techidaily.com/aomei-backupper-pro-your-go-to-expert-for-secure-backups-on-windows-server-2012/"><u>AOMEI Backupper Pro: Your Go-To Expert for Secure Backups on Windows Server 2012</u></a></li>
<li><a href="https://win-bits.techidaily.com/backing-up-your-iphone-top-3-methods-using-a-usb-flash-drive/"><u>Backing Up Your iPhone: Top 3 Methods Using a USB Flash Drive</u></a></li>
<li><a href="https://win-bits.techidaily.com/bios-based-complete-windows-reinstall-erasing-data-securely-from-your-hard-drive/"><u>BIOS-Based Complete Windows Reinstall: Erasing Data Securely From Your Hard Drive</u></a></li>
<li><a href="https://discover-bits.techidaily.com/comment-programmer-des-sauvegardes-automatiques-hourly-dans-windows-11-10-8-ou-7-2-methodes-simples/"><u>Comment Programmer Des Sauvegardes Automatiques Hourly Dans Windows 11, 10, 8 Ou 7: 2 Méthodes Simples</u></a></li>
<li><a href="https://win-bits.techidaily.com/comprehensive-troubleshooting-steps-for-fixing-pfn-list-corruption-issues/"><u>Comprehensive Troubleshooting Steps for Fixing PFN List Corruption Issues</u></a></li>
<li><a href="https://win-howtos.techidaily.com/dimming-device-sudden-blackout/"><u>Dimming Device: Sudden Blackout</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-sim-unlock-itel-a60-phones-without-code-2-ways-to-remove-android-sim-lock-by-drfone-android/"><u>In 2024, Sim Unlock Itel A60 Phones without Code 2 Ways to Remove Android Sim Lock</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/instagrams-audio-alteration-the-ultimate-guide/"><u>Instagram's Audio Alteration The Ultimate Guide</u></a></li>
<li><a href="https://win-bits.techidaily.com/transitionner-en-safran-a-linfini-vers-un-sshd-de-seagate-methodes-securisees-and-gratuites/"><u>Transitionner en Safran À L'Infini Vers Un SSHD De Seagate - Méthodes Sécurisées & Gratuites</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/why-is-ipogo-not-working-on-xiaomi-redmi-note-13-5g-fixed-drfone-by-drfone-virtual-android/"><u>Why is iPogo not working On Xiaomi Redmi Note 13 5G? Fixed | Dr.fone</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134498/18498" target="_top" id="2134498">
  <img src="//a.impactradius-go.com/display-ad/18498-2134498" border="0" alt="https://techidaily.com" width="720" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134498/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

