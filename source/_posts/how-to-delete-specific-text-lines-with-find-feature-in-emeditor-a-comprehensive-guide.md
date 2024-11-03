---
title: How to Delete Specific Text Lines with Find Feature in EmEditor - A Comprehensive Guide
date: 2024-11-02T17:22:33.363Z
updated: 2024-11-03T18:04:39.218Z
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
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-differentiate-with-style-on-snapchat-top-120plus-narratives-for-your-private-stories/"><u>[New] In 2024, Differentiate with Style on Snapchat Top 120+ Narratives for Your Private Stories</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-streaming-success-recorded-google-chats-for-2024/"><u>[New] Streaming Success Recorded Google Chats for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-transformative-meme-making-discovering-the-best-8-tools/"><u>[Updated] Transformative Meme-Making Discovering the Best 8 Tools</u></a></li>
<li><a href="https://win-bits.techidaily.com/ziprar5/"><u>「圧縮ファイル(zip/Rar)が壊れてしまったりなくなったりした場合の復元手順5つ」</u></a></li>
<li><a href="https://win-bits.techidaily.com/1728506289344-ssd/"><u>既存のSSDでは起動ができないときのデータ回復手順</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/creating-convincing-news-final-buzzes-for-2024/"><u>Creating Convincing News Final Buzzes for 2024</u></a></li>
<li><a href="https://win-bits.techidaily.com/dell-computers-installieren-sie-eine-wiederherstellungspartition-fur-das-zurucksetzen-auf-werkseinstellungen/"><u>Dell Computers - Installieren Sie Eine Wiederherstellungspartition Für Das Zurücksetzen Auf Werkseinstellungen</u></a></li>
<li><a href="https://win-bits.techidaily.com/easy-guide-to-moving-files-between-two-ssds-simple-tutorial/"><u>Easy Guide to Moving Files Between Two SSDs - Simple Tutorial</u></a></li>
<li><a href="https://extra-tips.techidaily.com/elite-laughter-photo-artificializer/"><u>Elite Laughter Photo Artificializer</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-unlock-motorola-moto-g24-phone-with-broken-screen-by-drfone-android/"><u>How to Unlock Motorola Moto G24 Phone with Broken Screen</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-3-ways-to-change-location-on-facebook-marketplace-for-vivo-v30-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Ways to Change Location on Facebook Marketplace for Vivo V30 | Dr.fone</u></a></li>
<li><a href="https://fox-web3.techidaily.com/step-by-step-guide-transferring-data-from-an-android-device-to-your-iphone-via-bluetooth/"><u>Step-by-Step Guide: Transferring Data From an Android Device to Your iPhone via Bluetooth</u></a></li>
<li><a href="https://win-bits.techidaily.com/windows-11-updates-handhabung-verlorener-dateien-ohne-panik-mit-tipps-und-tricks-von-sorgenfrei/"><u>Windows 11 Updates - Handhabung Verlorener Dateien Ohne Panik Mit Tipps Und Tricks Von Sorgenfrei</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2016143/19272" target="_top" id="2016143">
  <img src="//a.impactradius-go.com/display-ad/19272-2016143" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2016143/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

