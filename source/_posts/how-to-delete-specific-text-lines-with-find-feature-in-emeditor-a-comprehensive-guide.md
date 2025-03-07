---
title: How to Delete Specific Text Lines with Find Feature in EmEditor - A Comprehensive Guide
date: 2025-03-03T16:31:36.659Z
updated: 2025-03-07T16:21:51.888Z
tags:
  - product
categories:
  - emeditor
thumbnail: https://thmb.techidaily.com/b7ec02702d51d57959e5bd1248adaf8d9c4e1536be03bd52fccab5d6aa482430.jpg
---

## How to Delete Specific Text Lines with Find Feature in EmEditor - A Comprehensive Guide

Viewing 2 posts - 1 through 2 (of 2 total)

* Author  
Posts
* December 14, 2006 at 3:38 pm [#4057](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/93e551d84395f0fc57f55c24feb7037f?s=80&d=identicon&r=g)abgibbs](https://www.emeditor.com/forums/users/abgibbs/ "View abgibbs's profile")  
Member  
Hello all,  
 Fist off — great editor! Best I’ve ever used, by a long shot.  
 I need to remove all lines beginning with “IF EXISTS” from a couple thousand .SQL files, but I’m confused on how the “find in files” box handles regex.  
 I \*should\* use:  
 Find: IFs{1}EXISTS.+n  
 replace:  
 However, it doesn’t find any matches when I do this. if I remove the n from the “find” regex it finds all the corret matches but doesn’t include the CRLF at the end of the line. I want to remove the entire line, including the CRLF. Is there something weird about how the “find in files” handles end-of-line characters?  
 Thanks!  
December 15, 2006 at 3:27 am [#4062](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/a0a6377144ed3636f985d87303f65ed2?s=80&d=identicon&r=g)Yutaka Emura](https://www.emeditor.com/forums/users/yemura/ "View Yutaka Emura's profile")  
Keymaster  
The regular expression is correct if the **Keep Modified Files Open** is on. However, if the **Keep Modified Files Open** is off, you must use **/r/n** for a new line. So the regular expression should be  
 IFs{1}EXISTS.+rn  
 (if the **Keep Modified Files Open** is off in the Replace in Files dialog box).  
 See Also [How to Specify New Lines](https://tools.techidaily.com/emeditor/products/)
* Author  
Posts

Viewing 2 posts - 1 through 2 (of 2 total)

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
<li><a href="https://article-knowledge.techidaily.com/updated-capture-the-big-one-best-fishing-camers-ranked-for-2024/"><u>[Updated] Capture the Big One Best Fishing Camers Ranked for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-in-2024-fix-chromium-and-youtube-streams/"><u>[Updated] In 2024, Fix Chromium and YouTube Streams</u></a></li>
<li><a href="https://win-bits.techidaily.com/1-the-ultimate-list-of-top-partition-recovery-software-for-quick-fixes/"><u>1. The Ultimate List of Top Partition Recovery Software for Quick Fixes</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/6-reasons-for-vigilance-when-dealing-with-automated-systems/"><u>6 Reasons for Vigilance when Dealing with Automated Systems</u></a></li>
<li><a href="https://win-bits.techidaily.com/1728486637667-windows-11/"><u>如何有效地在Windows 11系统中保存和撤销数据</u></a></li>
<li><a href="https://win-bits.techidaily.com/breaking-free-from-obsolete-systems-solve-your-windows-10-version-upgrade-dilemma-windows-10-21h2/"><u>Breaking Free From Obsolete Systems: Solve Your Windows 10 Version Upgrade Dilemma (Windows 10 21H2)</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/discover-the-ultimate-list-of-affordable-screen-capture-tools-for-entry-level-pcs-movavi-edition/"><u>Discover the Ultimate List of Affordable Screen Capture Tools for Entry-Level PCs - Movavi Edition</u></a></li>
<li><a href="https://win-bits.techidaily.com/guida-passo-passo-alla-creazione-di-un-backup-immagina-sistema-sui-computer-dell-con-windows-1011/"><u>Guida Passo-Passo Alla Creazione Di Un Backup Immagina Sistema Sui Computer Dell Con Windows 10/11</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-change-your-apple-id-password-on-your-iphone-13-pro-drfone-by-drfone-ios/"><u>How To Change Your Apple ID Password On your iPhone 13 Pro | Dr.fone</u></a></li>
<li><a href="https://win-bits.techidaily.com/how-to-recover-deleted-pages-in-microsoft-onenote-step-by-step-guide/"><u>How to Recover Deleted Pages in Microsoft OneNote - Step-by-Step Guide</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-streamlining-color-grading-incorenasive-guide-to-lut-integration-in-obs/"><u>In 2024, Streamlining Color Grading Incorenasive Guide to LUT Integration in OBS</u></a></li>
<li><a href="https://screen-recording.techidaily.com/navigating-google-meets-virtual-whiteboards-across-appleandroid-and-laptops-for-2024/"><u>Navigating Google Meet's Virtual Whiteboards Across Apple/Android & Laptops for 2024</u></a></li>
<li><a href="https://win-bits.techidaily.com/troubleshoot-iphone-airdrop-restrictions-bypassing-contacts-only-mode-with-proven-fixes/"><u>Troubleshoot iPhone AirDrop Restrictions: Bypassing 'Contacts Only' Mode with Proven Fixes</u></a></li>
<li><a href="https://howto.techidaily.com/why-does-my-honor-play-8t-keep-turning-off-by-itself-6-fixes-are-here-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Why Does My Honor Play 8T Keep Turning Off By Itself? 6 Fixes Are Here | Dr.fone</u></a></li>
<li><a href="https://tech-revival.techidaily.com/why-relying-on-ai-generated-codes-is-a-no-go-for-legitimate-windows-11-software-licenses/"><u>Why Relying on AI-Generated Codes Is a No-Go for Legitimate Windows 11 Software Licenses</u></a></li>
</ul></div>

