---
title: How to Delete Specific Text Lines with Find Feature in EmEditor - A Comprehensive Guide
date: 2024-10-07T02:46:05.741Z
updated: 2024-10-11T10:41:10.207Z
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
<li><a href="https://fox-hovers.techidaily.com/new-launchpad-for-novice-gopro-owners-must-have-gear-guide/"><u>[New] Launchpad for Novice GoPro Owners - Must-Have Gear Guide</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-surprise-your-friends-with-these-unheard-memes/"><u>[New] Surprise Your Friends with These Unheard Memes</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-2024-approved-how-to-screenshot-on-mac-5-simple-ways/"><u>[Updated] 2024 Approved How to Screenshot on Mac - 5 Simple Ways</u></a></li>
<li><a href="https://techtrends.techidaily.com/boosting-your-iphones-incoming-call-volume-a-simple-guide/"><u>Boosting Your iPhone's Incoming Call Volume: A Simple Guide</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-lava-yuva-3-location-on-skout-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Lava Yuva 3 Location on Skout | Dr.fone</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/in-depth-analysis-of-extollo-lansocket-1500-enjoy-ultrafast-connectivity-with-minimal-delay-and-dual-power-feature/"><u>In-Depth Analysis of Extollo LANSocket 1500: Enjoy Ultrafast Connectivity with Minimal Delay and Dual Power Feature</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/quickeye-ff-plugins-for-2024/"><u>QuickEye FF Plugins for 2024</u></a></li>
<li><a href="https://sound-issues.techidaily.com/razer-kraken-mic-problems-solved-a-step-by-step-guide/"><u>Razer Kraken Mic Problems Solved: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-bits.techidaily.com/simple-steps-to-insert-a-logo-into-your-videos-using-pc-tools-and-online-apps/"><u>Simple Steps to Insert a Logo Into Your Videos Using PC Tools and Online Apps</u></a></li>
<li><a href="https://win-bits.techidaily.com/simple-tricks-for-free-downloading-jet-lis-movie-collection/"><u>Simple Tricks for FREE Downloading Jet Li's Movie Collection</u></a></li>
<li><a href="https://win-bits.techidaily.com/spotifymp3/"><u>SpotifyからMP3に: 専用フリープログラムで簡単な音楽変換</u></a></li>
<li><a href="https://win-bits.techidaily.com/step-by-step-guide-to-transforming-pro-tools-sdii-and-sound-designer-ii-recordings-into-wav-audio/"><u>Step-by-Step Guide to Transforming Pro Tools' SDII and Sound Designer II Recordings Into WAV Audio</u></a></li>
<li><a href="https://win-bits.techidaily.com/step-by-step-tutorial-how-to-stream-mkv-videos-on-sony-playstation-3-console/"><u>Step-by-Step Tutorial: How to Stream MKV Videos on Sony PlayStation 3 Console</u></a></li>
<li><a href="https://win-bits.techidaily.com/step-by-step-tutorial-optimizing-your-kodi-box-with-gridiron-legends-for-superior-live-football-streams/"><u>Step-by-Step Tutorial: Optimizing Your Kodi Box with Gridiron Legends for Superior Live Football Streams</u></a></li>
<li><a href="https://tech-haven.techidaily.com/streamline-collaboration-in-onlyoffice-docspace-powered-by-ai-discover-the-chatgpt-edge/"><u>Streamline Collaboration in ONLYOFFICE DocSpace Powered by AI - Discover the ChatGPT Edge</u></a></li>
<li><a href="https://win-bits.techidaily.com/troubleshooting-dvd-shrink-issues-on-windows-11-effective-solutions/"><u>Troubleshooting DVD Shrink Issues on Windows 11: Effective Solutions</u></a></li>
<li><a href="https://win-bits.techidaily.com/ultimate-guide-choosing-the-best-mp3-to-wav-conversion-tools-on-pcmac/"><u>Ultimate Guide: Choosing the Best MP3 to WAV Conversion Tools on PC/Mac</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/unlock-the-power-of-partnerships-youtube-ads-with-a-famebit-edge-for-2024/"><u>Unlock the Power of Partnerships YouTube Ads with a FameBit Edge for 2024</u></a></li>
<li><a href="https://win-bits.techidaily.com/unlocking-the-secrets-of-part-files-steps-to-access-and-conversion-guidelines/"><u>Unlocking the Secrets of PART Files: Steps to Access and Conversion Guidelines</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<span id="1374820">
					<video width="200" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1374820.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/15852-1374820">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1374820.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:125px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fthefitville.pxf.io%2Fc%2F5597632%2F1374820%2F15852'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1374820/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

