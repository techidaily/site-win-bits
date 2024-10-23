---
title: How to Delete Specific Text Lines with Find Feature in EmEditor - A Comprehensive Guide
date: 2024-10-18T02:11:27.272Z
updated: 2024-10-22T19:20:25.537Z
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
<li><a href="https://youtube-web.techidaily.com/ed-in-2024-drive-more-traffic-effective-strategies-for-youtube-outros/"><u>[Updated] In 2024, Drive More Traffic Effective Strategies for YouTube Outros</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-craft-the-perfect-blurred-photo-with-these-essentials/"><u>2024 Approved Craft the Perfect Blurred Photo with These Essentials</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/2024-approved-online-tv-downloading-a-complete-recording-blueprint/"><u>2024 Approved Online TV Downloading A Complete Recording Blueprint</u></a></li>
<li><a href="https://win-bits.techidaily.com/despeje-tu-registro-de-arranque-con-estos-dos-metodos-faciles/"><u>Despeje Tu Registro De Arranque Con Estos Dos Métodos Fáciles</u></a></li>
<li><a href="https://network-issues.techidaily.com/driver-update-halt-blackout/"><u>Driver Update Halt: Blackout</u></a></li>
<li><a href="https://win-bits.techidaily.com/expertentaugliche-clone-software-fur-effizientes-betriebssystemmigrieren-auf-ssds-und-hdds/"><u>Expertentaugliche Clone-Software Für Effizientes Betriebssystemmigrieren Auf SSDs Und HDDs</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/future-proof-your-career-with-these-9-essential-skype-interview-tips-for-job-seekers/"><u>Future-Proof Your Career with These 9 Essential Skype Interview Tips for Job Seekers</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-9-infinix-note-30-pro-monitoring-apps-for-parental-controls-drfone-by-drfone-virtual-android/"><u>In 2024, Top 9 Infinix Note 30 Pro Monitoring Apps for Parental Controls | Dr.fone</u></a></li>
<li><a href="https://win-bits.techidaily.com/windows-10-ssdhdd-clonezilla/"><u>Windows 10 SSD/HDDへのコピー: Clonezilla利用ガイド</u></a></li>
<li><a href="https://win-bits.techidaily.com/pcssd-yogabook/"><u>デスクトップPCにおけるSSDの交換手順 - YogaBook向けガイド</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2012401/19272" target="_top" id="2012401">
  <img src="//a.impactradius-go.com/display-ad/19272-2012401" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2012401/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

