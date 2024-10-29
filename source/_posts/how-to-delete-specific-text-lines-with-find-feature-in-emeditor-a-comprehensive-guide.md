---
title: How to Delete Specific Text Lines with Find Feature in EmEditor - A Comprehensive Guide
date: 2024-10-27T23:25:08.425Z
updated: 2024-10-29T02:33:04.051Z
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
<li><a href="https://win-bits.techidaily.com/8windows-1110/"><u>8則によるファイル検索ガイド:Windows 11・10で行うべきこと</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/enhancing-ps5-performance-by-replacing-the-hdd-with-an-ssd/"><u>Enhancing PS5 Performance by Replacing the HDD with an SSD</u></a></li>
<li><a href="https://hardware-help.techidaily.com/find-and-install-samsung-nvme960-evo-driver-a-comprehensive-guide-for-windows-users/"><u>Find and Install Samsung Nvme960 EVO Driver - A Comprehensive Guide for Windows Users</u></a></li>
<li><a href="https://win-bits.techidaily.com/guide-express-installation-dun-hdd-portable-en-lecteur-principal/"><u>Guide Express: Installation D'un HDD Portable en Lecteur Principal</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-unleashing-potential-the-easy-path-to-blending-linktree-with-tiktok-bios/"><u>In 2024, Unleashing Potential The Easy Path to Blending Linktree with TikTok Bios</u></a></li>
<li><a href="https://fox-that.techidaily.com/resolving-whatsapp-icloud-backup-problems-for-seamless-chat-history-syncing-on-iphone-and-ipad/"><u>Resolving WhatsApp iCloud Backup Problems for Seamless Chat History Syncing on iPhone and iPad</u></a></li>
<li><a href="https://win-bits.techidaily.com/ripara-i-download-non-riusciti-di-windows-11-con-questi-5-semplici-passaggi/"><u>Ripara I Download Non Riusciti Di Windows 11 Con Questi 5 Semplici Passaggi</u></a></li>
<li><a href="https://win-bits.techidaily.com/solution-implemented-for-fixing-iphone-backup-restore-problems-with-itunes/"><u>Solution Implemented for Fixing iPhone Backup Restore Problems with iTunes</u></a></li>
<li><a href="https://extra-tips.techidaily.com/subtlety-matters-fading-out-sounds-in-logic-pro/"><u>Subtlety Matters Fading Out Sounds in Logic Pro</u></a></li>
<li><a href="https://win-bits.techidaily.com/top-gratuite-de-sync-et-backup-avec-aomei-backupper-solutions-innovantes-pour-la-protection-des-donnees/"><u>Top Gratuite De Sync Et Backup Avec AOMEI Backupper : Solutions Innovantes Pour La Protection Des Données</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/what-legendaries-are-in-pokemon-platinum-on-lava-yuva-2-pro-drfone-by-drfone-virtual-android/"><u>What Legendaries Are In Pokemon Platinum On Lava Yuva 2 Pro? | Dr.fone</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2137380/7443" target="_top" id="2137380">
  <img src="//a.impactradius-go.com/display-ad/7443-2137380" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2137380/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

