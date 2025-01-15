---
title: How to Delete Specific Text Lines with Find Feature in EmEditor - A Comprehensive Guide
date: 2025-01-08T22:55:22.010Z
updated: 2025-01-15T02:54:58.463Z
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
<li><a href="https://youtube-blog.techidaily.com/-techniques-to-retrieve-and-save-youtubes-iconic-images/"><u>[New] 3 Techniques to Retrieve & Save YouTube's Iconic Images</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/new-in-2024-metaverse-versus-multimetase-analyzing-their-core-disparities/"><u>[New] In 2024, Metaverse Versus MultiMetase Analyzing Their Core Disparities</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-key-practices-for-soundless-media-gathering-for-2024/"><u>[New] Key Practices for Soundless Media Gathering for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-ps4-broadcasting-made-easy-your-obs-guide-for-2024/"><u>[New] PS4 Broadcasting Made Easy Your OBS Guide for 2024</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-in-2024-pinnacle-performances-in-figure-skate-22/"><u>[Updated] In 2024, Pinnacle Performances in Figure Skate '22</u></a></li>
<li><a href="https://blog-min.techidaily.com/5-easy-ways-to-copy-contacts-from-sony-xperia-5-v-to-iphone-14-and-15-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>5 Easy Ways to Copy Contacts from Sony Xperia 5 V to iPhone 14 and 15 | Dr.fone</u></a></li>
<li><a href="https://win-bits.techidaily.com/windows-1187discord/"><u>两种方法：怎样在Windows 11、8或7系统中找回删除的Discord图片</u></a></li>
<li><a href="https://win-bits.techidaily.com/complete-step-by-step-manual-on-retrieving-files-from-your-simpletech-hdd/"><u>Complete Step-by-Step Manual on Retrieving Files From Your SimpleTech HDD</u></a></li>
<li><a href="https://win-bits.techidaily.com/copybootsecurely-an-reliable-alternative-to-xml-drive-duplication/"><u>CopyBootSecurely: An Reliable Alternative to XML Drive Duplication</u></a></li>
<li><a href="https://win-bits.techidaily.com/etapes-faciles-pour-la-synchronisation-dun-ordinateur-portable-et-dun-bureau-dans-windows-10-techniques-provenantes/"><u>Étapes Faciles Pour La Synchronisation D'un Ordinateur Portable Et D'un Bureau Dans Windows 10 - Techniques Provenantes</u></a></li>
<li><a href="https://tech-hub.techidaily.com/favorite-phones-spotlighted-the-top-handsets-chosen-by-zdnets-tech-experts/"><u>Favorite Phones Spotlighted: The Top Handsets Chosen by ZDNet's Tech Experts</u></a></li>
<li><a href="https://win-bits.techidaily.com/guia-paso-a-paso-para-rescatar-emails-borrados-tecnicas-probadas-y-confirmadas/"><u>Guía Paso a Paso Para Rescatar Emails Borrados: Técnicas Probadas Y Confirmadas</u></a></li>
<li><a href="https://win-bits.techidaily.com/guide-etape-par-etape-creation-dune-copie-de-securite-avec-lutilitaire-ghost-disk-sur-votre-ordinateur/"><u>Guide Étape Par Étape: Création D'une Copie De Sécurité Avec L'utilitaire Ghost Disk Sur Votre Ordinateur.</u></a></li>
<li><a href="https://win-bits.techidaily.com/how-to-restore-and-retrieve-lost-data-from-your-memory-stick-a-step-by-step-guide/"><u>How to Restore and Retrieve Lost Data From Your Memory Stick: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-bits.techidaily.com/recovering-lost-memories-a-guide-to-retrieving-deleted-images-from-your-nikon-device/"><u>Recovering Lost Memories: A Guide to Retrieving Deleted Images From Your Nikon Device</u></a></li>
<li><a href="https://win-bits.techidaily.com/ultimate-manual-on-samsung-t5-unlock-the-power-of-automatic-backups/"><u>Ultimate Manual on Samsung T5: Unlock the Power of Automatic Backups</u></a></li>
<li><a href="https://tech-revival.techidaily.com/unveiling-the-timeline-origins-and-milestones-in-artificial-intelligence/"><u>Unveiling the Timeline: Origins and Milestones in Artificial Intelligence</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/upgrade-your-smartphone-game-with-apples-latest-a-comprehensive-comparison-of-iphone-16-vs-iphone-15-features-expert-review/"><u>Upgrade Your Smartphone Game with Apple's Latest - A Comprehensive Comparison of iPhone 16 Vs. IPhone 15 Features Expert Review</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/youtube-masterclass-advanced-techniques-for-video-commentary-embedding-for-2024/"><u>YouTube Masterclass Advanced Techniques for Video Commentary Embedding for 2024</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/umvX4ZdWbxk?si=tPXL0-Kzf9SQaY8z" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

