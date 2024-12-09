---
title: How to Delete Specific Text Lines with Find Feature in EmEditor - A Comprehensive Guide
date: 2024-12-06T04:41:23.426Z
updated: 2024-12-08T20:03:53.596Z
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
<li><a href="https://article-helps.techidaily.com/2024-approved-high-speed-photo-inspector-for-windows-11/"><u>2024 Approved High-Speed Photo Inspector for Windows 11</u></a></li>
<li><a href="https://win-bits.techidaily.com/high-resolution-kristen-stewart-wallpaper-collection-stunning-hd-backgrounds-and-images-by-yl-computing/"><u>High-Resolution Kristen Stewart Wallpaper Collection: Stunning HD Backgrounds and Images by YL Computing</u></a></li>
<li><a href="https://extra-information.techidaily.com/honored-proposals-leading-ringtone-creators-iphone/"><u>Honored Proposals Leading Ringtone Creators iPhone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-oneplus-open-to-outlook-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from OnePlus Open to Outlook | Dr.fone</u></a></li>
<li><a href="https://win-bits.techidaily.com/understanding-the-reasons-behind-your-pcs-intermittent-cooling-a-deep-dive-insights-by-yl-software/"><u>Understanding the Reasons Behind Your PC's Intermittent Cooling: A Deep Dive - Insights by YL Software</u></a></li>
<li><a href="https://games-able.techidaily.com/why-serious-games-resist-the-allure-of-gamefi/"><u>Why Serious Games Resist the Allure of GameFi</u></a></li>
<li><a href="https://fake-location.techidaily.com/will-the-ipogo-get-you-banned-and-how-to-solve-it-on-honor-100-drfone-by-drfone-virtual-android/"><u>Will the iPogo Get You Banned and How to Solve It On Honor 100 | Dr.fone</u></a></li>
<li><a href="https://win-bits.techidaily.com/yl-software-unveils-top-reasons-why-cryptocurrencies-outshine-traditional-financial-systems/"><u>YL Software Unveils Top Reasons Why Cryptocurrencies Outshine Traditional Financial Systems</u></a></li>
<li><a href="https://win-bits.techidaily.com/yl-softwares-how-to-enabling-the-built-in-firewall-in-windows-nt-ensure-protection-with-ease/"><u>YL Software's How-To: Enabling the Built-In Firewall in Windows nT – Ensure Protection with Ease</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Nl0Z0eth1u4?si=0eecOBNfc--51AJO" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

