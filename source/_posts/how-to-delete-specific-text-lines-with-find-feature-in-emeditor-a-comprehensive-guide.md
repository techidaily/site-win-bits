---
title: How to Delete Specific Text Lines with Find Feature in EmEditor - A Comprehensive Guide
date: 2024-12-19T21:48:19.766Z
updated: 2024-12-23T19:01:03.897Z
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
<li><a href="https://some-techniques.techidaily.com/updated-fabricate-personalized-viral-memes/"><u>[Updated] Fabricate Personalized Viral Memes</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-personalized-gift-boxes-unlocked-the-best-online-shopping-spots/"><u>2024 Approved Personalized Gift Boxes Unlocked The Best Online Shopping Spots</u></a></li>
<li><a href="https://win-bits.techidaily.com/comparing-crypto-and-traditional-money-insights-from-yl-computings-expertise/"><u>Comparing Crypto and Traditional Money: Insights From YL Computing's Expertise</u></a></li>
<li><a href="https://win-bits.techidaily.com/diagnosing-hardware-failure-steps-to-determine-why-your-device-wont-power-up-guidance-by-yl-software/"><u>Diagnosing Hardware Failure: Steps to Determine Why Your Device Won't Power Up – Guidance by YL Software</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-tips-for-restoring-access-to-systemprofiledesktop-on-windows-systems/"><u>Expert Tips for Restoring Access to Systemprofile Desktop on Windows Systems</u></a></li>
<li><a href="https://win-bits.techidaily.com/how-to-resolve-issues-with-non-functional-sound-cards-expert-advice-by-yl-software/"><u>How to Resolve Issues with Non-Functional Sound Cards: Expert Advice by YL Software</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/24-creative-channel-titling-techniques-for-growth/"><u>In 2024, Creative Channel Titling Techniques for Growth</u></a></li>
<li><a href="https://blog-min.techidaily.com/in-depth-assessment-weighing-the-benefits-and-limitations-of-modern-nas-systems-compared-to-cloud-data-archiving/"><u>In-Depth Assessment: Weighing the Benefits and Limitations of Modern NAS Systems Compared to Cloud Data Archiving</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/ios-update-fixes-unsettling-glitch-that-brought-back-erased-images-insights-from-zdnet/"><u>IOS Update Fixes Unsettling Glitch That Brought Back Erased Images: Insights From ZDNet</u></a></li>
<li><a href="https://win-blog.techidaily.com/nier-replicant-remaster-launch-problem-fixes-and-solutions-available/"><u>NieR Replicant Remaster Launch Problem: Fixes and Solutions Available</u></a></li>
<li><a href="https://win-bits.techidaily.com/reset-your-devices-network-configuration-with-simple-steps-guide-by-yl-software/"><u>Reset Your Device's Network Configuration with Simple Steps: Guide by YL Software</u></a></li>
<li><a href="https://win-bits.techidaily.com/resolving-issues-with-your-video-card-a-step-by-step-guide-tips-from-yl-software/"><u>Resolving Issues with Your Video Card: A Step-by-Step Guide - Tips From YL Software</u></a></li>
<li><a href="https://win-bits.techidaily.com/unraveling-the-mystery-how-to-fix-repeating-dll-file-missing-errors-insights-from-yl-software/"><u>Unraveling the Mystery: How to Fix Repeating DLL File Missing Errors - Insights From YL Software</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6KXVWj6Ar1M?si=Cd_jktmoN3e9OzH3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

