---
title: Continue Editing Sequentially with Files in EmEditor - Tips & Tricks
date: 2024-11-02T21:36:55.619Z
updated: 2024-11-03T21:38:10.372Z
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
<li><a href="https://some-techniques.techidaily.com/updated-finding-your-ideal-broadcast-channel-top-10-guidelines/"><u>[Updated] Finding Your Ideal Broadcast Channel Top 10 Guidelines</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-prime-ringtone-retailers-for-game-of-thrones-fans/"><u>[Updated] Prime Ringtone Retailers for Game of Thrones Fans</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-rights-and-recourse-following-sudden-account-suspension-on-fb-for-2024/"><u>[Updated] Rights and Recourse Following Sudden Account Suspension on FB for 2024</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-trailblaze-your-way-to-success-insights-on-youtube-metrics-with-social-blade/"><u>2024 Approved Trailblaze Your Way to Success Insights on YouTube Metrics with Social Blade</u></a></li>
<li><a href="https://tech-hub.techidaily.com/bringing-gpt-conversations-to-android-widgets/"><u>Bringing GPT Conversations to Android Widgets</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/can-t-view-hevc-h-265-content-on-redmi-13c-by-aiseesoft-video-converter-play-hevc-video-on-android/"><u>Can’t view HEVC H.265 content on Redmi 13C</u></a></li>
<li><a href="https://win-bits.techidaily.com/come-crittografare-i-tuoi-file-di-immagini-con-aomei-backupper-pro-per-un-backup-sicuro/"><u>Come Crittografare I Tuoi File Di Immagini Con AOMEI Backupper Pro per Un Backup Sicuro</u></a></li>
<li><a href="https://win-bits.techidaily.com/como-transferir-la-ruta-de-inicio-de-windows-11-a-un-ssd-sin-reinstalacion/"><u>Cómo Transferir La Ruta De Inicio De Windows 11 a Un SSD Sin Reinstalación</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/navigating-the-latest-tech-trends-insightful-articles-from-toms-hardware-hub/"><u>Navigating the Latest Tech Trends - Insightful Articles From Tom's Hardware Hub</u></a></li>
<li><a href="https://win-bits.techidaily.com/surface-pro-8ssd/"><u>Surface Pro 8のSSDを新しく輝かせる! - 改良・交換方法ガイド</u></a></li>
<li><a href="https://buynow-info.techidaily.com/top-netgear-orbi-mesh-router-analysis-why-its-a-must-have-in-your-home-network/"><u>Top Netgear Orbi Mesh Router Analysis: Why It's a Must-Have in Your Home Network</u></a></li>
<li><a href="https://win-bits.techidaily.com/troubleshoot-and-repair-how-to-get-your-computer-to-boot-from-media-in-windows-10-4-proven-techniques/"><u>Troubleshoot and Repair: How to Get Your Computer to Boot From Media in Windows 10 (4 Proven Techniques)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-guide-resolving-non-functioning-integrated-webcams-in-windows/"><u>Ultimate Guide: Resolving Non-Functioning Integrated Webcams in Windows</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<span id="1328683">
					<video width="200" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1328683.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/15852-1328683">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1328683.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:125px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fthefitville.pxf.io%2Fc%2F5597632%2F1328683%2F15852'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1328683/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

