---
title: Continue Editing Sequentially with Files in EmEditor - Tips & Tricks
date: 2024-10-09T18:20:08.950Z
updated: 2024-10-17T07:36:02.770Z
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
<li><a href="https://facebook-clips.techidaily.com/new-in-2024-anonymous-artifacts-auction-2023-the-quest-for-digital-secrecy/"><u>[New] In 2024, Anonymous Artifacts Auction-2023 The Quest for Digital Secrecy</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-achieving-seamless-video-communication-between-xbox-and-zoom/"><u>2024 Approved Achieving Seamless Video Communication Between Xbox & Zoom</u></a></li>
<li><a href="https://location-fake.techidaily.com/4-methods-to-turn-off-life-360-on-nokia-c110-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>4 Methods to Turn off Life 360 On Nokia C110 without Anyone Knowing | Dr.fone</u></a></li>
<li><a href="https://win-bits.techidaily.com/aomei-backupper-erfahrung-beheben-sie-fehler-404-wenn-seiten-nicht-gefunden-werden/"><u>AOMEI Backupper Erfahrung: Beheben Sie Fehler 404, Wenn Seiten Nicht Gefunden Werden</u></a></li>
<li><a href="https://win-howtos.techidaily.com/five-steps-to-resolve-chromecast-connectivity-problems-quickly/"><u>Five Steps to Resolve Chromecast Connectivity Problems Quickly</u></a></li>
<li><a href="https://driver-download.techidaily.com/get-the-latest-realtek-rtl81eacw-based-rtl8188cu-wifi-driver-suite-for-win-107/"><u>Get the Latest Realtek RTL81eacw-Based RTL8188CU WiFi Driver Suite for Win 10/7</u></a></li>
<li><a href="https://win-bits.techidaily.com/guarantee-seamless-windows-start-up-with-these-11-proven-strategies-avoid-powering-down/"><u>Guarantee Seamless Windows Start-Up with These 11 Proven Strategies – Avoid Powering Down</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-oppo-a1x-5g-location-on-skout-drfone-by-drfone-virtual-android/"><u>How to Change Oppo A1x 5G Location on Skout | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-detailed-guide-of-ispoofer-for-pogo-installation-on-vivo-v27-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Detailed guide of ispoofer for pogo installation On Vivo V27 Pro | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-unlock-vivo-t2-5g-phone-without-any-data-loss-by-drfone-android/"><u>In 2024, How to Unlock Vivo T2 5G Phone without Any Data Loss</u></a></li>
<li><a href="https://win-bits.techidaily.com/klopfen-sie-auf-die-festplatten-kopie-und-vergrosserung-in-windows-mit-variabler-dateigrosse/"><u>Klopfen Sie Auf Die Festplatten-Kopie Und -Vergrößerung in Windows Mit Variabler Dateigröße</u></a></li>
<li><a href="https://win-bits.techidaily.com/maitriser-la-creation-de-points-de-restauration-dans-windows-11-tutoriel-complementaire-et-detaille/"><u>Maîtriser La Création De Points De Restauration Dans Windows 11: Tutoriel Complémentaire Et Détaillé</u></a></li>
<li><a href="https://article-helps.techidaily.com/navigating-the-ipodiverse-compreenasol-for-ios-podcast-downloads/"><u>Navigating the iPodiverse Compreenasol for iOS Podcast Downloads</u></a></li>
<li><a href="https://win-bits.techidaily.com/professionelle-anleitung-zum-ausfuhren-einer-datenablage-fur-windows-server-2022-mit-hilfe-eines-usb-speichersticks/"><u>Professionelle Anleitung Zum Ausführen Einer Datenablage Für Windows Server 2022 Mit Hilfe Eines USB-Speichersticks</u></a></li>
<li><a href="https://win-bits.techidaily.com/quick-steps-for-erasing-disk-partitions-on-your-windows-1011-system/"><u>Quick Steps for Erasing Disk Partitions on Your Windows 10/11 System</u></a></li>
<li><a href="https://win-bits.techidaily.com/repariere-deine-dateisystemprobleme-3-effektive-strategien-fur-den-windows-server-2003/"><u>Repariere Deine Dateisystemprobleme: 3 Effektive Strategien Für Den Windows-Server 2003</u></a></li>
<li><a href="https://win-bits.techidaily.com/windows-1110-dell/"><u>Windows 11から10へのスムーズなダウングレード - Dellを使用</u></a></li>
<li><a href="https://techidaily.com/xiaomi-wont-play-hevc-h265-media-how-to-fix-by-aiseesoft-video-converter-play-hevc-video-on-android/"><u>Xiaomi won’t play HEVC H.265 media, how to fix?</u></a></li>
<li><a href="https://win-bits.techidaily.com/44oh44o844k5pcn5asx44ks6ziy44gq44gf44kb44gr44cb44gp44gt44gn44cb44ge44gk5akx5yig44oq44od44kv44ki44od44ox44ks6kgm44gg44gl77yf/"><u>データ損失を防ぐために、どこで、いつ増分バックアップを行うか？</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1886069/19272" target="_top" id="1886069">
  <img src="//a.impactradius-go.com/display-ad/19272-1886069" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1886069/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

