---
title: Continue Editing Sequentially with Files in EmEditor - Tips & Tricks
date: 2024-11-23T23:39:38.356Z
updated: 2024-11-30T16:18:14.646Z
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
<li><a href="https://desktop-recording.techidaily.com/new-the-top-8-multiparty-android-conferencing-apps-for-2024/"><u>[New] The Top 8 Multiparty Android Conferencing Apps for 2024</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-cutting-edge-conversion-tips-avi-to-gif-using-filmora-for-windowsmac-users-for-2024/"><u>[Updated] Cutting-Edge Conversion Tips AVI to GIF Using Filmora for Windows/Mac Users for 2024</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/updated-essential-asmr-channel-discoveries/"><u>[Updated] Essential ASMR Channel Discoveries</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-replay-rare-relationship-recaps/"><u>[Updated] Replay Rare Relationship Recaps</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-superior-storytellers-sanctuary/"><u>[Updated] Superior Storyteller's Sanctuary</u></a></li>
<li><a href="https://win-bits.techidaily.com/windowsd/"><u>迅速修正方法：如何在Windows電腦中克服D槽存取被限制的困境</u></a></li>
<li><a href="https://win-bits.techidaily.com/compreender-a-solucao-de-backup-da-aomei-artigos-detalhados-guias-facilitadores-e-promocoes-agora/"><u>Compreender a Solução De Backup Da AOMEI: Artigos Detalhados, Guias Facilitadores E Promoções Agora!</u></a></li>
<li><a href="https://buynow-help.techidaily.com/nokia-71-phone-analysis-stunning-display-and-photography-at-an-exceptional-value/"><u>Nokia 7.1 Phone Analysis - Stunning Display & Photography at an Exceptional Value</u></a></li>
<li><a href="https://win-bits.techidaily.com/recuperation-efficace-des-fichiers-perdus-ou-supprimes-sous-windows-11-guide-facile-et-pratique/"><u>Récupération Efficace Des Fichiers Perdus Ou Supprimés Sous Windows 11 : Guide Facile Et Pratique</u></a></li>
<li><a href="https://win-bits.techidaily.com/speichereinrichtung-wiederaufbau-tipps-zur-wiedererlangung-unformatierter-festplattendaten/"><u>Speichereinrichtung Wiederaufbau - Tipps Zur Wiedererlangung Unformatierter Festplattendaten</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/L603QXgjb3I?si=sMYHfMGy2kNPSHPt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

