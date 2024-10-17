---
title: How to Delete Specific Text Lines with Find Feature in EmEditor - A Comprehensive Guide
date: 2024-10-16T01:53:34.003Z
updated: 2024-10-17T10:35:58.966Z
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
<li><a href="https://youtube-web.techidaily.com/ed-investors-intuition-selecting-stock-channel-wisely-for-2024/"><u>[Updated] Investor's Intuition Selecting Stock Channel Wisely for 2024</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/approved-charting-the-course-of-knowledge-best-history-yt-channels-for-students/"><u>2024 Approved Charting the Course of Knowledge Best History YT Channels for Students</u></a></li>
<li><a href="https://win-bits.techidaily.com/1728507568957-windows-11/"><u>立马解决Windows 11某个文件夹为空的方法</u></a></li>
<li><a href="https://win-bits.techidaily.com/complete-fix-it-manual-how-to-solve-fdisk-cant-erase-partition-issues/"><u>Complete Fix-It Manual: How To Solve 'Fdisk Can't Erase Partition' Issues</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/easy-steps-to-recover-deleted-data-from-infinix-hot-40-pro-by-fonelab-android-recover-data/"><u>Easy steps to recover deleted data from Infinix Hot 40 Pro</u></a></li>
<li><a href="https://blog-min.techidaily.com/effortless-hd-video-conversion-made-easy-upload-movies-and-videos-to-ios-devices-with-winx-mediamaker-for-macos/"><u>Effortless HD Video Conversion Made Easy: Upload Movies and Videos to iOS Devices with WinX MediaMaker for MacOS</u></a></li>
<li><a href="https://article-tips.techidaily.com/optimal-selection-top-cost-effective-iosandroid-live-streamers/"><u>Optimal Selection Top Cost-Effective iOS/Android Live Streamers</u></a></li>
<li><a href="https://technical-tips.techidaily.com/1722902338124-slash-your-spending-6-unbeatable-online-deal-destinations-revealed/"><u>Slash Your Spending: 6 Unbeatable Online Deal Destinations Revealed!</u></a></li>
<li><a href="https://win-bits.techidaily.com/speedy-transfer-move-images-from-external-hdd-to-idevices-effortlessly/"><u>Speedy Transfer: Move Images From External HDD to iDevices Effortlessly</u></a></li>
<li><a href="https://location-social.techidaily.com/top-7-skype-hacker-to-hack-any-skype-account-on-your-xiaomi-civi-3-disney-100th-anniversary-edition-drfone-by-drfone-virtual-android/"><u>Top 7 Skype Hacker to Hack Any Skype Account On your Xiaomi Civi 3 Disney 100th Anniversary Edition | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/troubleshoot-and-resolve-iphone-usb-transfer-problems-mastering-the-mtp-driver-fixes/"><u>Troubleshoot & Resolve iPhone USB Transfer Problems: Mastering the MTP Driver Fixes</u></a></li>
<li><a href="https://win-bits.techidaily.com/windows-11-surface-pro-3/"><u>Windows 11への安全且つ迅速な Surface Pro 3 アップグレードガイド</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1902273/19272" target="_top" id="1902273">
  <img src="//a.impactradius-go.com/display-ad/19272-1902273" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1902273/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

