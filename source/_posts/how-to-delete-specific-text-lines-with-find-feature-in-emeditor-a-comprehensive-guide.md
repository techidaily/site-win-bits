---
title: How to Delete Specific Text Lines with Find Feature in EmEditor - A Comprehensive Guide
date: 2025-02-16T00:10:43.592Z
updated: 2025-02-18T18:32:41.187Z
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
<li><a href="https://video-capture.techidaily.com/updated-2024-approved-best-quality-hd-screensaver-recorders/"><u>[Updated] 2024 Approved Best Quality HD Screensaver Recorders</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-2024-approved-secrets-unlocked-starting-your-own-hit-gaming-stream/"><u>[Updated] 2024 Approved Secrets Unlocked Starting Your Own Hit Gaming Stream</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-in-2024-sharex-examined-evaluations-and-alternatives/"><u>[Updated] In 2024, ShareX Examined Evaluations & Alternatives</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-synchronized-tasks-and-engaging-podcast-episodes/"><u>2024 Approved Synchronized Tasks and Engaging Podcast Episodes</u></a></li>
<li><a href="https://win-bits.techidaily.com/comprehensive-evaluation-best-screen-recording-apps-on-iphone-6/"><u>Comprehensive Evaluation: Best Screen Recording Apps on iPhone 6</u></a></li>
<li><a href="https://fox-access.techidaily.com/in-2024-harmonizing-your-windows-photos-how-to-incorporate-audio-visual-features/"><u>In 2024, Harmonizing Your Windows Photos How to Incorporate Audio-Visual Features</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-the-ultimate-guide-to-get-the-rare-candy-on-pokemon-go-fire-red-on-apple-iphone-12-mini-drfone-by-drfone-virtual-ios/"><u>In 2024, The Ultimate Guide to Get the Rare Candy on Pokemon Go Fire Red On Apple iPhone 12 mini | Dr.fone</u></a></li>
<li><a href="https://win-bits.techidaily.com/leading-software-for-professional-video-transformations-and-special-effects/"><u>Leading Software for Professional Video Transformations and Special Effects</u></a></li>
<li><a href="https://win-bits.techidaily.com/mastering-raid-shadow-legends-a-step-by-step-guide-for-pc-gamers/"><u>Mastering Raid Shadow Legends: A Step-by-Step Guide for PC Gamers</u></a></li>
<li><a href="https://win-bits.techidaily.com/mastering-video-capture-a-comprehensive-guide-to-recording-with-obs-and-other-top-tools/"><u>Mastering Video Capture: A Comprehensive Guide to Recording with OBS & Other Top Tools</u></a></li>
<li><a href="https://win-bits.techidaily.com/step-by-step-guide-sharing-your-content-on-instagram-via-pc-or-mac/"><u>Step-by-Step Guide: Sharing Your Content on Instagram via PC or Mac</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/streamlining-song-selection-for-youtube-playlist-curation-for-2024/"><u>Streamlining Song Selection for YouTube Playlist Curation for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/the-professionals-playbook-mastering-live-video-sharing-on-fb/"><u>The Professional's Playbook Mastering Live Video Sharing on FB</u></a></li>
<li><a href="https://win-bits.techidaily.com/ultimate-guide-to-flawlessly-capturing-your-pc-screenshots-on-windows-7810/"><u>Ultimate Guide to Flawlessly Capturing Your PC Screenshots on Windows 7/8/10</u></a></li>
<li><a href="https://win-bits.techidaily.com/ultimate-vlogging-editor-tools-the-aplus-picks-for-online-content-makers/"><u>Ultimate Vlogging Editor Tools: The A+ Picks for Online Content Makers</u></a></li>
<li><a href="https://fake-location.techidaily.com/will-ispoofer-update-on-honor-x7b-drfone-by-drfone-virtual-android/"><u>Will iSpoofer update On Honor X7b | Dr.fone</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/oySc0DiqmKc?si=8pynRzuhlq2RUPZ6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

