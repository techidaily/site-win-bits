---
title: How to Delete Specific Text Lines with Find Feature in EmEditor - A Comprehensive Guide
date: 2024-12-24T16:09:16.092Z
updated: 2024-12-29T17:38:58.875Z
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
<li><a href="https://youtube-tips.techidaily.com/024-approved-instantaneous-video-downloader-selection-guide/"><u>[New] 2024 Approved Instantaneous Video Downloader Selection Guide</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/updated-in-2024-lightroom-workflow-creating-and-merging-professional-hdr-images/"><u>[Updated] In 2024, Lightroom Workflow Creating & Merging Professional HDR Images</u></a></li>
<li><a href="https://win-bits.techidaily.com/toshiba-hard-disk-troubleshooting-selective-methods/"><u>無料解決東芝硬碟問題：選擇性方法 [六個選擇] (Toshiba Hard Disk Troubleshooting: Selective Methods)</u></a></li>
<li><a href="https://win-bits.techidaily.com/clonage-de-windows-11-en-seulement-3-etapes-comment-refaire-copie-sur-un-ssd-compact/"><u>Clonage De Windows 11 en Seulement 3 Etapes: Comment Refaire Copie Sur Un SSD Compact</u></a></li>
<li><a href="https://win-community.techidaily.com/guida-per-trasferire-le-applicazioni-tra-gli-ipads-come-spostare-e-condividere-con-semplicita/"><u>Guida per Trasferire Le Applicazioni Tra Gli iPads: Come Spostare E Condividere Con Semplicità</u></a></li>
<li><a href="https://win-bits.techidaily.com/how-to-successfully-replace-your-toshiba-tecra-a50-cs-hard-drive-in-depth-guide-for-users/"><u>How to Successfully Replace Your Toshiba Tecra A50-C's Hard Drive - In-Depth Guide for Users</u></a></li>
<li><a href="https://youtube-data.techidaily.com/24-transforming-viewers-into-income-how-many-votes-yield-earnings/"><u>In 2024, Transforming Viewers Into Income How Many Votes Yield Earnings?</u></a></li>
<li><a href="https://tech-hub.techidaily.com/is-it-slower-for-a-reason-understanding-the-differences-between-chatgpt-4-and-chatgpt-35/"><u>Is It Slower for a Reason? Understanding the Differences Between ChatGPT-4 and ChatGPT-3.5</u></a></li>
<li><a href="https://win-bits.techidaily.com/itaomei-backupper/"><u>IT業界メディアによるAOMEI Backupper ソフトウェアの厳選批評</u></a></li>
<li><a href="https://win-bits.techidaily.com/losung-fur-verlorene-dateien-nach-betriebssystem-update/"><u>Lösung Für Verlorene Dateien Nach Betriebssystem-Update</u></a></li>
<li><a href="https://sound-issues.techidaily.com/onikuma-microphone-malfunction-troubleshooting-solutions-revealed/"><u>Onikuma Microphone Malfunction - Troubleshooting Solutions Revealed</u></a></li>
<li><a href="https://program-issues.techidaily.com/resolving-the-ls-0013-initialization-issue-on-fortnite-expert-advice-and-tips/"><u>Resolving the LS-0013 Initialization Issue on Fortnite: Expert Advice and Tips</u></a></li>
<li><a href="https://win-bits.techidaily.com/section-3c-qanda-with-solutions/"><u>Section 3C: Q&A with Solutions</u></a></li>
<li><a href="https://win-bits.techidaily.com/top-rated-tools-for-efficient-hard-drive-duplication-on-windows-server-versions-2003-2008-2012/"><u>Top Rated Tools for Efficient Hard Drive Duplication on Windows Server Versions (2003, 2008, 2012)</u></a></li>
<li><a href="https://discover-answers.techidaily.com/windows-defender-vs-windows-security-app-on-windows-nt-whats-the-distinction-insights-from-yl-software-experts/"><u>Windows Defender Vs. Windows Security App on Windows nT: What's the Distinction? Insights From YL Software Experts</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XIUatTFH0Zw?si=ZCtoBtIy18y2F5Vc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

