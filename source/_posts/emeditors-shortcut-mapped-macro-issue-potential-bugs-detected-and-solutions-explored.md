---
title: "EmEditor's Shortcut-Mapped Macro Issue: Potential Bugs Detected and Solutions Explored"
date: 2024-11-11T20:18:17.102Z
updated: 2024-11-12T16:52:13.799Z
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
<li><a href="https://tiktok-videos.techidaily.com/new-in-2024-how-to-create-stunning-tiktok-videos-with-templates/"><u>[New] In 2024, How To Create Stunning TikTok Videos With Templates</u></a></li>
<li><a href="https://youtube-data.techidaily.com/evenue-revolution-leveraging-the-youtube-premium-opportunity-for-2024/"><u>[New] Revenue Revolution Leveraging the YouTube Premium Opportunity for 2024</u></a></li>
<li><a href="https://win-bits.techidaily.com/1728480161815-windows-11-dropbox-2/"><u>快速上手：在 Windows 11 中利用 Dropbox 同步圖書館的 2 種方式</u></a></li>
<li><a href="https://win-bits.techidaily.com/1728505491815-5/"><u>如何使用5大步骤创建系统备份，确保操作系统安全</u></a></li>
<li><a href="https://fox-that.techidaily.com/how-to-fix-a-non-responsive-chatgpt-app-on-iphone-easy-fixes-in-9-steps/"><u>How to Fix a Non-Responsive ChatGPT App on iPhone - Easy Fixes in 9 Steps</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-easy-tutorial-for-activating-icloud-on-apple-iphone-xs-safe-and-legal-by-drfone-ios/"><u>In 2024, Easy Tutorial for Activating iCloud on Apple iPhone XS Safe and Legal</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/new-best-of-the-best-top-10-free-4k-video-converter-tools/"><u>New Best of the Best Top 10 Free 4K Video Converter Tools</u></a></li>
<li><a href="https://win11.techidaily.com/nine-no-go-areas-for-novice-windows-11-users/"><u>Nine No-Go Areas for Novice Windows 11 Users</u></a></li>
<li><a href="https://win-bits.techidaily.com/step-by-step-guide-setting-up-full-system-recovery-for-windows-server-201n-r2-dcs/"><u>Step-by-Step Guide: Setting Up Full System Recovery for Windows Server 201N R2 DCs</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/the-ultimate-look-at-samsung-galaxy-s8-in-4k/"><u>The Ultimate Look at Samsung Galaxy S8 in 4K</u></a></li>
<li><a href="https://win-able.techidaily.com/top-tips-and-tricks-to-stop-discord-from-crashing-on-your-device/"><u>Top Tips and Tricks to Stop Discord From Crashing on Your Device</u></a></li>
<li><a href="https://win-bits.techidaily.com/troubleshoot-vanished-quick-access-items-in-windows-11-file-explorer-effective-fixes/"><u>Troubleshoot Vanished Quick Access Items in Windows 11 File Explorer - Effective Fixes</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2014859/22899" target="_top" id="2014859">
  <img src="//a.impactradius-go.com/display-ad/22899-2014859" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014859/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

