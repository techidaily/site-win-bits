---
title: How to Delete Specific Text Lines with Find Feature in EmEditor - A Comprehensive Guide
date: 2025-01-23T00:06:00.515Z
updated: 2025-01-26T20:21:46.830Z
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
<li><a href="https://article-tips.techidaily.com/new-2024-approved-understanding-the-magic-behind-m1-max-clips/"><u>[New] 2024 Approved Understanding the Magic Behind M1 Max Clips</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-snapsizesecrets-perfecting-photo-and-video-sizes-in-instagram/"><u>[New] SnapSizeSecrets Perfecting Photo and Video Sizes in Instagram</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-maximizing-yt-videos-for-igtv-presence/"><u>2024 Approved Maximizing YT Videos for IGTV Presence</u></a></li>
<li><a href="https://win-bits.techidaily.com/5aac5l2v5zyo57ui56uv546v5akd5lit5ogi5asn5yig6zmk5pah5lu255qe5oqa5ben/"><u>如何在终端环境中恢复删除文件的技巧</u></a></li>
<li><a href="https://win-bits.techidaily.com/access-gratis-top-rated-hard-drive-rescue-applications-for-your-windows-device/"><u>Access Gratis: Top Rated Hard Drive Rescue Applications for Your Windows Device</u></a></li>
<li><a href="https://win-bits.techidaily.com/deciphering-pm-narendra-modi-an-insight-into-his-7-key-strategies-and-vision/"><u>Deciphering PM Narendra Modi: An Insight Into His 7 Key Strategies and Vision</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enabling-windows-user-sign-in-overcoming-failures/"><u>Enabling Windows User Sign-In: Overcoming Failures</u></a></li>
<li><a href="https://win-bits.techidaily.com/loschfreie-deaktivierung-der-iphone-icloud-einfache-schritte-zum-ausloggen/"><u>Löschfreie Deaktivierung Der iPhone-iCloud - Einfache Schritte Zum Ausloggen</u></a></li>
<li><a href="https://some-techniques.techidaily.com/massive-tesla-recall-more-than-300k-cars-affected-by-safety-issue/"><u>Massive Tesla Recall: More Than 300K Cars Affected by Safety Issue</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-cure-for-onedrives-0x8004dec5-sign-in-crisis-in-windows/"><u>Mastering the Cure for OneDrive's 0X8004DEC5 Sign In Crisis in Windows</u></a></li>
<li><a href="https://techtrends.techidaily.com/step-by-step-guide-capturing-images-using-your-computer-screen/"><u>Step-by-Step Guide: Capturing Images Using Your Computer Screen</u></a></li>
<li><a href="https://win-bits.techidaily.com/step-by-step-guide-restoring-lost-files-using-a-data-recovery-live-usb/"><u>Step-by-Step Guide: Restoring Lost Files Using a Data Recovery Live USB</u></a></li>
<li><a href="https://win-blog.techidaily.com/two-in-one-strategy-awaited-launch-the-tandem-project/"><u>Two-in-One Strategy Awaited Launch - The 'Tandem Project'</u></a></li>
<li><a href="https://win-bits.techidaily.com/1728488924846-windows-112/"><u>Windows 11対応ソフトウェアを確認するための必見ツール2点</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/g6xXIR_Uh1A?si=TMXzklPEY50MUM05" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

