---
title: How to Delete Specific Text Lines with Find Feature in EmEditor - A Comprehensive Guide
date: 2025-02-06T00:45:03.692Z
updated: 2025-02-09T01:53:32.013Z
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
<li><a href="https://facebook-record-videos.techidaily.com/new-channel-charisma-techniques-for-amplifying-youtube-visibility-for-2024/"><u>[New] Channel Charisma Techniques for Amplifying YouTube Visibility for 2024</u></a></li>
<li><a href="https://article-files.techidaily.com/new-in-2024-smart-shopping-guide-to-best-5k-screens-8/"><u>[New] In 2024, Smart Shopping Guide to Best 5K Screens #8</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-future-filmmaking-favorites-2024s-best-cameras/"><u>[Updated] Future Filmmaking Favorites 2024'S Best Cameras</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-master-fades-with-ease-4-methods-unveiled-for-2024/"><u>[Updated] Master Fades with Ease 4 Methods Unveiled for 2024</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-navigating-youtube-cards-and-tags/"><u>[Updated] Navigating YouTube Cards and Tags</u></a></li>
<li><a href="https://win-bits.techidaily.com/windows-11-10-8-7-2/"><u>運用 Windows 11 / 10 / 8 / 7: 兩種全新方式自動資料同步 - 技術指南 (2 種新型態的解決法)</u></a></li>
<li><a href="https://win-bits.techidaily.com/effective-techniques-for-virtual-machine-replication-using-hyper-vs-importexport-features/"><u>Effective Techniques for Virtual Machine Replication Using Hyper-V's Import/Export Features</u></a></li>
<li><a href="https://win-bits.techidaily.com/erfolgreich-verlorene-dokumente-wiederherstellen-auf-einem-pc-mit-windows-10/"><u>Erfolgreich Verlorene Dokumente Wiederherstellen Auf Einem PC Mit Windows 10</u></a></li>
<li><a href="https://win-bits.techidaily.com/guide-simple-tout-savoir-pour-restaurer-les-documents-de-microsoft-office-perdus-sans-frais/"><u>Guide Simple : Tout Savoir Pour Restaurer Les Documents De Microsoft Office Perdus Sans Frais !</u></a></li>
<li><a href="https://win-bits.techidaily.com/how-to-resolve-itunes-update-1-issue-during-ios-device-restoration/"><u>How to Resolve iTunes Update 1 Issue During iOS Device Restoration</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-turn-off-google-location-to-stop-tracking-you-on-vivo-y55s-5g-2023-drfone-by-drfone-virtual-android/"><u>In 2024, How to Turn Off Google Location to Stop Tracking You on Vivo Y55s 5G (2023) | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-ultimate-guide-to-catch-the-regional-located-pokemon-for-motorola-edge-40-neo-drfone-by-drfone-virtual-android/"><u>In 2024, Ultimate Guide to Catch the Regional-Located Pokemon For Motorola Edge 40 Neo | Dr.fone</u></a></li>
<li><a href="https://win-bits.techidaily.com/migrating-your-data-seamless-transition-between-two-surface-pro-devices/"><u>Migrating Your Data: Seamless Transition Between Two Surface Pro Devices</u></a></li>
<li><a href="https://games-able.techidaily.com/revamp-your-computer-experience-four-advantages-in-corsairs-icue-link/"><u>Revamp Your Computer Experience: Four Advantages in Corsair’s iCUE Link</u></a></li>
<li><a href="https://win-bits.techidaily.com/step-by-step-tutorial-on-retrieving-data-from-silicon-power-external-memory-sticks/"><u>Step-by-Step Tutorial on Retrieving Data From Silicon Power External Memory Sticks</u></a></li>
<li><a href="https://win-bits.techidaily.com/step-by-step-tutorial-clearing-out-everything-from-your-pc-using-two-techniques/"><u>Step-by-Step Tutorial: Clearing Out Everything From Your PC Using Two Techniques</u></a></li>
<li><a href="https://win-bits.techidaily.com/tecniche-essenziali-per-lottimizzazione-del-backup-e-mail-un-guida-completa/"><u>Tecniche Essenziali per L'ottimizzazione Del Backup E-Mail: Un Guida Completa</u></a></li>
<li><a href="https://program-issues.techidaily.com/unleash-endless-prosperity-with-dragons-riches-a-complete-guide-for-pc/"><u>Unleash Endless Prosperity with 'Dragon's Riches': A Complete Guide for PC</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/unova-stone-pokemon-go-evolution-list-and-how-catch-them-for-google-pixel-8-pro-drfone-by-drfone-virtual-android/"><u>Unova Stone Pokémon Go Evolution List and How Catch Them For Google Pixel 8 Pro | Dr.fone</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ZblaBc-v2vs?si=CKW1gJwXQT2vZJYo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

