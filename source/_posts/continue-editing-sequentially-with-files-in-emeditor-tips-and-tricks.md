---
title: Continue Editing Sequentially with Files in EmEditor - Tips & Tricks
date: 2024-10-27T18:16:38.436Z
updated: 2024-10-28T22:10:48.277Z
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
<li><a href="https://fox-links.techidaily.com/new-2024-approved-digital-theater-at-your-fingertips-ioss-best-movie-apps/"><u>[New] 2024 Approved Digital Theater at Your Fingertips - iOS's Best Movie Apps</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-in-2024-camstudio-live-streaming-and-screen-capturing-review/"><u>[New] In 2024, CamStudio Live Streaming & Screen Capturing Review</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/2024-approved-the-essential-guide-to-using-zdsoft-vision/"><u>2024 Approved The Essential Guide to Using ZDSoft Vision</u></a></li>
<li><a href="https://win-bits.techidaily.com/come-crittografare-i-tuoi-file-di-immagini-con-aomei-backupper-pro-per-un-backup-sicuro/"><u>Come Crittografare I Tuoi File Di Immagini Con AOMEI Backupper Pro per Un Backup Sicuro</u></a></li>
<li><a href="https://win-bits.techidaily.com/como-transferir-la-ruta-de-inicio-de-windows-11-a-un-ssd-sin-reinstalacion/"><u>Cómo Transferir La Ruta De Inicio De Windows 11 a Un SSD Sin Reinstalación</u></a></li>
<li><a href="https://win-bits.techidaily.com/convert-and-mimic-ssd-performance-using-a-cloned-hard-disk-sata-across-various-windows-oses/"><u>Convert and Mimic SSD Performance Using a Cloned Hard Disk (SATA) Across Various Windows OSes</u></a></li>
<li><a href="https://win-bits.techidaily.com/effortless-methods-for-a-clean-iphone-transfer-when-preparing-to-sell-your-device/"><u>Effortless Methods for a Clean iPhone Transfer When Preparing to Sell Your Device</u></a></li>
<li><a href="https://win-able.techidaily.com/fixes-unveiled-resolving-pc-issues-in-the-remastered-version-of-yakuza-3/"><u>Fixes Unveiled: Resolving PC Issues in the Remastered Version of Yakuza 3</u></a></li>
<li><a href="https://change-location.techidaily.com/home-button-not-working-on-realme-narzo-60-5g-here-are-real-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Home Button Not Working on Realme Narzo 60 5G? Here Are Real Fixes | Dr.fone</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/mastering-media-conversion-with-actionable-steps-from-xml-for-2024/"><u>Mastering Media Conversion with Actionable Steps From XML for 2024</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/mastering-telephone-job-interviews-proven-strategies-for-impressing-recruiters-and-advance-to-face-to-face-discussions/"><u>Mastering Telephone Job Interviews: Proven Strategies for Impressing Recruiters and Advance to Face-to-Face Discussions</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-lunar-client-failure-errors-quickly/"><u>Overcoming “Windows Lunar Client Failure” Errors Quickly</u></a></li>
<li><a href="https://win-bits.techidaily.com/repertuaran-membuatnya-sederhana-cara-bimbingan-untuk-menyelesaikan-masalah-iphone-di-icloud/"><u>Repertuaran Membuatnya Sederhana: Cara Bimbingan Untuk Menyelesaikan Masalah iPhone Di iCloud</u></a></li>
<li><a href="https://win-bits.techidaily.com/surface-pro-8ssd/"><u>Surface Pro 8のSSDを新しく輝かせる! - 改良・交換方法ガイド</u></a></li>
<li><a href="https://win-bits.techidaily.com/transferer-en-douceur-vos-donnees-vers-onedrive-methodes-alternatives-a-la-mise-en-place-de-depositaires-3-options/"><u>Transférer en Douceur Vos Données Vers OneDrive - Méthodes Alternatives À La Mise en Place De Dépositaires (3 Options) !</u></a></li>
<li><a href="https://win-bits.techidaily.com/troubleshoot-and-repair-how-to-get-your-computer-to-boot-from-media-in-windows-10-4-proven-techniques/"><u>Troubleshoot and Repair: How to Get Your Computer to Boot From Media in Windows 10 (4 Proven Techniques)</u></a></li>
<li><a href="https://win-bits.techidaily.com/turbocharge-your-dell-xps-8930-performance-by-switching-to-a-speedy-ssd/"><u>Turbocharge Your Dell XPS 8930 Performance by Switching to a Speedy SSD</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/unlock-6-free-youtube-endings-for-pros-for-2024/"><u>Unlock 6 Free YouTube Endings for Pros for 2024</u></a></li>
<li><a href="https://discover-comparisons.techidaily.com/wie-man-die-anderungsprotokolle-von-datenversionen-unter-windows-10-entfernt-anleitung-und-tipps/"><u>Wie Man Die Änderungsprotokolle Von Datenversionen Unter Windows 10 Entfernt - Anleitung Und Tipps</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<span id="1977020">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1977020.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1977020">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1977020.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1977020%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1977020/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

