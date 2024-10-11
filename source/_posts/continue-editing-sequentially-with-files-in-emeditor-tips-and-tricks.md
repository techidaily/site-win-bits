---
title: Continue Editing Sequentially with Files in EmEditor - Tips & Tricks
date: 2024-10-05T20:50:35.456Z
updated: 2024-10-10T20:26:07.838Z
tags:
  - product
categories:
  - emeditor
thumbnail: https://thmb.techidaily.com/8e7f29503e1809da37fe391a31647712629490bb93b62275ef9ee0f83d862d33.jpg
---

## Continue Editing Sequentially with Files in EmEditor - Tips & Tricks

July 13, 2010 at 6:04 pm [#8742](https://tools.techidaily.com/emeditor/products/) 

[![](https://secure.gravatar.com/avatar/a0a6377144ed3636f985d87303f65ed2?s=80&d=identicon&r=g)Yutaka Emura](https://www.emeditor.com/forums/users/yemura/ "View Yutaka Emura's profile")

Keymaster

This is an example of the macro that opens the next .txt file in the same folder as the opened file.
  

	// This macro opens the next ".txt" file in the current folder.  

	//  

	sFolder = document.Path;  

	if(sFolder != ""){  

	    fso = new ActiveXObject("Scripting.FileSystemObject");  

	    f = fso.GetFolder(sFolder);  

	    fc = new Enumerator(f.files);  

	    sItem = "";  

	    for (; !fc.atEnd(); fc.moveNext()) {  

	       if(fc.item().name == document.Name) {  

	           for(fc.moveNext(); !fc.atEnd(); fc.moveNext()) {  

	               n = fc.item().name.lastIndexOf(".");  

	               if(n != -1){  

	                   if(fc.item().name.slice(n) == ".txt"){  

	                       sPath = sFolder + "" + fc.item().name;  

	                       try {  

	                            editor.OpenFile(sPath);  

	                       catch(e){  

	                       break;  

	           break;

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
<li><a href="https://instagram-video-files.techidaily.com/new-2024-approved-4-effective-ways-to-captivate-ig-audiences-with-loop-videos/"><u>[New] 2024 Approved 4 Effective Ways to Captivate IG Audiences with Loop Videos</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-break-through-the-crowd-key-youtube-seo-strategies-to-rank-high-for-2024/"><u>[Updated] Break Through the Crowd Key YouTube SEO Strategies to Rank High for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-flip-the-script-learning-to-negative-play-in-instagram/"><u>[Updated] In 2024, Flip the Script Learning to Negative Play in Instagram</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-new-buzzwords-for-vlogger-dialogues-for-2024/"><u>[Updated] New Buzzwords for Vlogger Dialogues for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/acquire-personalized-wonderfox-picture-branding-feature-with-protection-layer/"><u>Acquire Personalized WonderFox Picture Branding Feature with Protection Layer</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/mastering-gadgets-with-toms-comprehensive-hardware-guide/"><u>Mastering Gadgets with Tom's Comprehensive Hardware Guide</u></a></li>
<li><a href="https://win-bits.techidaily.com/troubleshooting-dvd-shrink-issues-on-windows-11-effective-solutions/"><u>Troubleshooting DVD Shrink Issues on Windows 11: Effective Solutions</u></a></li>
<li><a href="https://win-bits.techidaily.com/ultimate-guide-choosing-the-best-mp3-to-wav-conversion-tools-on-pcmac/"><u>Ultimate Guide: Choosing the Best MP3 to WAV Conversion Tools on PC/Mac</u></a></li>
<li><a href="https://win-bits.techidaily.com/unlocking-the-secrets-of-part-files-steps-to-access-and-conversion-guidelines/"><u>Unlocking the Secrets of PART Files: Steps to Access and Conversion Guidelines</u></a></li>
<li><a href="https://win-bits.techidaily.com/windows-11youtube/"><u>Windows 11によるYouTube動画の効果的な記録テクニック</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075461/7443" target="_top" id="2075461">
  <img src="//a.impactradius-go.com/display-ad/7443-2075461" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075461/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

