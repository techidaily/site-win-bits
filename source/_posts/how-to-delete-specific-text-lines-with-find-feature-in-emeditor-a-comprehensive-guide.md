---
title: How to Delete Specific Text Lines with Find Feature in EmEditor - A Comprehensive Guide
date: 2025-01-14T18:55:23.076Z
updated: 2025-01-21T05:50:00.213Z
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
<li><a href="https://article-helps.techidaily.com/new-breakdown-of-funds-required-for-music-video-shooting/"><u>[New] Breakdown of Funds Required for Music Video Shooting</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-2024-approved-time-saving-tips-for-documenting-virtual-meeting-events/"><u>[Updated] 2024 Approved Time-Saving Tips for Documenting Virtual Meeting Events</u></a></li>
<li><a href="https://win-bits.techidaily.com/boost-your-pcs-ram-efficiency-expert-tips-from-yl-computings-tech-experts/"><u>Boost Your PC's RAM Efficiency: Expert Tips From YL Computing's Tech Experts</u></a></li>
<li><a href="https://media-tips.techidaily.com/effortless-setup-for-enjoying-high-quality-4k-hdr-video-on-your-pc-with-windows-11/"><u>Effortless Setup for Enjoying High-Quality 4K HDR Video on Your PC with Windows 11</u></a></li>
<li><a href="https://win-bits.techidaily.com/how-to-diagnose-and-fix-frequent-memory-failures-on-your-windows-system-tips-by-yl-software/"><u>How to Diagnose and Fix Frequent Memory Failures on Your Windows System - Tips by YL Software</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-fix-android-app-not-installed-error-on-xiaomi-mix-fold-3-quickly-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix Android App Not Installed Error on Xiaomi Mix Fold 3 Quickly? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-successfully-uninstall-epic-games-hub-in-w11/"><u>How to Successfully Uninstall Epic Games Hub in W11</u></a></li>
<li><a href="https://article-tips.techidaily.com/navigate-motion-sickness-in-virtual-reality-with-ease/"><u>Navigate Motion Sickness in Virtual Reality with Ease</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-vn-video-editor-pc-version-a-quick-overview/"><u>New VN Video Editor PC Version A Quick Overview</u></a></li>
<li><a href="https://win-bits.techidaily.com/section-3a-the-next-concept-neurotransmission/"><u>Section 3A: The Next Concept – Neurotransmission</u></a></li>
<li><a href="https://win-bits.techidaily.com/step-by-step-guide-modifying-windows-defender-firewall-via-control-panel-tips-from-yl-computing/"><u>Step-by-Step Guide: Modifying Windows Defender Firewall via Control Panel - Tips From YL Computing</u></a></li>
<li><a href="https://win-bits.techidaily.com/understanding-the-root-of-ram-malfunctions-insights-from-yl-computing/"><u>Understanding the Root of RAM Malfunctions: Insights From YL Computing</u></a></li>
<li><a href="https://win-bits.techidaily.com/which-graphics-processor-is-built-into-your-windows-setup-find-out-with-yl-software-expertise/"><u>Which Graphics Processor Is Built Into Your Windows Setup? Find Out with YL Software Expertise</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/zen-zapped-grooves-top-20-soothing-country-music-for-easy-dancing-tiktok-for-2024/"><u>Zen-Zapped Grooves Top 20 Soothing Country Music for Easy Dancing (TikTok) for 2024</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/E1ax-vnGdeo?si=bgTkOhOEwDTlRQE3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

