---
title: How to Delete Specific Text Lines with Find Feature in EmEditor - A Comprehensive Guide
date: 2024-11-24T22:40:24.071Z
updated: 2024-12-01T01:07:49.636Z
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
<li><a href="https://youtube-tips.techidaily.com/024-approved-exclusive-youtube-snippet-access-high-quality-free-download/"><u>[New] 2024 Approved Exclusive YouTube Snippet Access - High Quality, Free Download!</u></a></li>
<li><a href="https://article-helps.techidaily.com/new-in-2024-image-editing-excellence-with-top-apps-list/"><u>[New] In 2024, Image Editing Excellence with Top Apps List</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ptimize-video-pace-on-youtube-for-devices-speed-adjustments/"><u>[New] Optimize Video Pace on YouTube for Devices (Speed Adjustments)</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-transform-speeches-into-animated-videos/"><u>[Updated] Transform Speeches Into Animated Videos</u></a></li>
<li><a href="https://win-bits.techidaily.com/einfuhrung-in-das-schnelle-neuladen-auf-dem-iphone-modell-der-serie-1514-die-perfekte-anleitung/"><u>Einführung in Das Schnelle Neuladen Auf Dem iPhone-Modell Der Serie 15/14: Die Perfekte Anleitung</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/enhanced-game-recorders-beyond-fbx-frameworks/"><u>Enhanced Game Recorders Beyond FBX Frameworks</u></a></li>
<li><a href="https://win-bits.techidaily.com/erfolgreich-verlorene-dokumente-wiederherstellen-auf-einem-pc-mit-windows-10/"><u>Erfolgreich Verlorene Dokumente Wiederherstellen Auf Einem PC Mit Windows 10</u></a></li>
<li><a href="https://win-bits.techidaily.com/guide-simple-tout-savoir-pour-restaurer-les-documents-de-microsoft-office-perdus-sans-frais/"><u>Guide Simple : Tout Savoir Pour Restaurer Les Documents De Microsoft Office Perdus Sans Frais !</u></a></li>
<li><a href="https://win-bits.techidaily.com/how-to-resolve-itunes-update-1-issue-during-ios-device-restoration/"><u>How to Resolve iTunes Update 1 Issue During iOS Device Restoration</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-a-perfect-guide-to-remove-or-disable-google-smart-lock-on-oppo-a78-5g-by-drfone-android/"><u>In 2024, A Perfect Guide To Remove or Disable Google Smart Lock On Oppo A78 5G</u></a></li>
<li><a href="https://win-bits.techidaily.com/migrating-your-data-seamless-transition-between-two-surface-pro-devices/"><u>Migrating Your Data: Seamless Transition Between Two Surface Pro Devices</u></a></li>
<li><a href="https://tech-revival.techidaily.com/navigating-through-intellectual-property-laws-for-ai-produced-artwork-who-gains-the-recognition/"><u>Navigating Through Intellectual Property Laws for AI-Produced Artwork: Who Gains the Recognition?</u></a></li>
<li><a href="https://win-bits.techidaily.com/step-by-step-tutorial-on-retrieving-data-from-silicon-power-external-memory-sticks/"><u>Step-by-Step Tutorial on Retrieving Data From Silicon Power External Memory Sticks</u></a></li>
<li><a href="https://win-bits.techidaily.com/step-by-step-tutorial-clearing-out-everything-from-your-pc-using-two-techniques/"><u>Step-by-Step Tutorial: Clearing Out Everything From Your PC Using Two Techniques</u></a></li>
<li><a href="https://howto.techidaily.com/want-to-uninstall-google-play-service-from-tecno-spark-10-pro-here-is-how-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Want to Uninstall Google Play Service from Tecno Spark 10 Pro? Here is How | Dr.fone</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/HtM7d4dpN1I?si=2vN_xgVGD4eYGORu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

