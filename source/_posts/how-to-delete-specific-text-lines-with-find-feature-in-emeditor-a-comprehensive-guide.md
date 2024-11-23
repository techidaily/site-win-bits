---
title: How to Delete Specific Text Lines with Find Feature in EmEditor - A Comprehensive Guide
date: 2024-11-21T22:49:43.843Z
updated: 2024-11-22T17:04:46.225Z
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
<li><a href="https://video-screen-grab.techidaily.com/updated-in-2024-step-by-step-minecraft-recording-guide-for-mac-enthusiasts/"><u>[Updated] In 2024, Step by Step Minecraft Recording Guide for Mac Enthusiasts</u></a></li>
<li><a href="https://win-bits.techidaily.com/1-the-ultimate-list-of-top-partition-recovery-software-for-quick-fixes/"><u>1. The Ultimate List of Top Partition Recovery Software for Quick Fixes</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/2024-approved-overcoming-the-barriers-to-distance-podcasting/"><u>2024 Approved Overcoming the Barriers to Distance Podcasting</u></a></li>
<li><a href="https://win-bits.techidaily.com/aomei-aomei-legal-compliance-tips-for-safe-use/"><u>利用規約で守るAOMEIセキュリティガイドライン - 合法的な使い方をおさらい | AOMEI Legal Compliance Tips for Safe Use</u></a></li>
<li><a href="https://win-bits.techidaily.com/guida-passo-passo-alla-creazione-di-un-backup-immagina-sistema-sui-computer-dell-con-windows-1011/"><u>Guida Passo-Passo Alla Creazione Di Un Backup Immagina Sistema Sui Computer Dell Con Windows 10/11</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-can-we-unlock-our-meizu-21-pro-phone-screen-by-drfone-android/"><u>How Can We Unlock Our Meizu 21 Pro Phone Screen?</u></a></li>
<li><a href="https://win-bits.techidaily.com/how-to-fix-apricorn-ez-gig-iv-external-hard-drive-copying-issues/"><u>How to Fix Apricorn EZ Gig IV External Hard Drive Copying Issues</u></a></li>
<li><a href="https://article-tips.techidaily.com/in-2024-mastering-lengthy-iphone-photo-captures/"><u>In 2024, Mastering Lengthy iPhone Photo Captures</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-podcasters-playlist-the-best-music-spots-to-open-your-ears/"><u>In 2024, Podcaster’s Playlist The Best Music Spots to Open Your Ears</u></a></li>
<li><a href="https://win-bits.techidaily.com/mbr-to-gpt-transition-on-windows-systems-a-guide-to-non-converting-disk-reformation-techniques/"><u>MBR to GPT Transition on Windows Systems - A Guide to Non-Converting Disk Reformation Techniques</u></a></li>
<li><a href="https://activate-lock.techidaily.com/new-multiple-ways-how-to-remove-icloud-activation-lock-from-your-iphone-7-by-drfone-ios/"><u>New Multiple Ways How To Remove iCloud Activation Lock From your iPhone 7</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/no-cost-3gp-video-rotation-solutions-top-5-tools-you-need/"><u>No-Cost 3GP Video Rotation Solutions Top 5 Tools You Need</u></a></li>
<li><a href="https://win-bits.techidaily.com/overcoming-obstacles-in-gaming-strategies-to-resolve-your-xbox-ones-constant-green-screen-error/"><u>Overcoming Obstacles in Gaming: Strategies to Resolve Your Xbox One's Constant Green Screen Error</u></a></li>
<li><a href="https://tech-haven.techidaily.com/revolutionizing-in-room-entertainment-choose-top-hotels-with-new-apple-airplay-feature-explained/"><u>Revolutionizing In-Room Entertainment: Choose Top Hotels with New Apple AirPlay Feature Explained</u></a></li>
<li><a href="https://some-tips.techidaily.com/the-essential-tutorial-on-using-snapchat-spotlight-for-2024/"><u>The Essential Tutorial on Using Snapchat Spotlight for 2024</u></a></li>
<li><a href="https://win-bits.techidaily.com/unable-to-access-raw-drive-conversion-functionality-fix-required/"><u>Unable to Access RAW Drive Conversion Functionality - Fix Required</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/BmegThMdrJE?si=rILo1FJb9DgnPljV&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

