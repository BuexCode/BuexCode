<!-----

You have some errors, warnings, or alerts. If you are using reckless mode, turn it off to see inline alerts.
* ERRORs: 0
* WARNINGs: 0
* ALERTS: 4

Conversion time: 0.743 seconds.


Using this Markdown file:

1. Paste this output into your source file.
2. See the notes and action items below regarding this conversion run.
3. Check the rendered output (headings, lists, code blocks, tables) for proper
   formatting and use a linkchecker before you publish this page.

Conversion notes:

* Docs to Markdown version 1.0β33
* Fri Mar 04 2022 06:57:54 GMT-0800 (PST)
* Source doc: Buexaus _IT_ Betriebshandbuch
* Tables are currently converted to HTML tables.
* This document has images: check for >>>>>  gd2md-html alert:  inline image link in generated source and store images to your server. NOTE: Images in exported zip file from Google Docs may not appear in  the same order as they do in your doc. Please check the images!

----->


<p style="color: red; font-weight: bold">>>>>>  gd2md-html alert:  ERRORs: 0; WARNINGs: 0; ALERTS: 4.</p>
<ul style="color: red; font-weight: bold"><li>See top comment block for details on ERRORs and WARNINGs. <li>In the converted Markdown or HTML, search for inline alerts that start with >>>>>  gd2md-html alert:  for specific instances that need correction.</ul>

<p style="color: red; font-weight: bold">Links to alert messages:</p><a href="#gdcalert1">alert1</a>
<a href="#gdcalert2">alert2</a>
<a href="#gdcalert3">alert3</a>
<a href="#gdcalert4">alert4</a>

<p style="color: red; font-weight: bold">>>>>> PLEASE check and correct alert issues and delete this message and the inline alerts.<hr></p>


Büxaus - IT - Betriebshandbuch

Versionen:


<table>
  <tr>
   <td>Datum
   </td>
   <td>Version
   </td>
   <td>Kommentar
   </td>
  </tr>
  <tr>
   <td>26.01.2022
   </td>
   <td>V0.1
   </td>
   <td>Idee, Grundlegende Erstellung, Inhalte, Kapitel
   </td>
  </tr>
  <tr>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
</table>



[TOC]




1. Idee

Das Dokument kann mit etwas Glück und Arbeit helfen die Übersicht über das ganze Netzwerk und die Systeme, wie sie aufgesetzt sind und funktionieren zu behalten. Entweder durch Texte, Bilder, Tabellen oder aber durch  Verweise auf andere Dateien oder Links ins Web. 

Das Dokument wird nie fertig sein sondern leben und zwischendurch Updates bekommen.

Im Idealfall ist es so umfassend dass jemand anderes damit die IT vollständig neu aufbauen kann. 



2. 
Übersicht


3. 
IP-Konzept


4. 
Backup & System Templates


    1. 
Templates


        1. 
zB Scripte / Vorlagen


    2. Backup Systeme/Shares/Verzeichnisse
        2. Google Share : Buexaus_Geteilt: z_Backup bzw direkt im Buexaus Share z_Backup (zu klären)
        3. BuexServ Share Backup
        4. jeweils Lokal
    3. TAR-Backup
    4. RASPI-Backup Backups
    5. Windows PC Backups
5. Systemgruppen
6. Systemliste
7. Netzwerk
8. User Konzept
9. ESPs
10. Rechner
    6. sdsa
    7. Rechner und Konfigurationen
        5. JamesBerry



<p id="gdcalert1" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image1.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert2">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image1.png "image_tooltip")




        6. BuexEins



<p id="gdcalert2" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image2.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert3">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image2.png "image_tooltip")




        7. BuexZwei
        8. BuexDrei



<p id="gdcalert3" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image3.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert4">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image3.png "image_tooltip")




        9. BuexVier



<p id="gdcalert4" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image4.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert5">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image4.png "image_tooltip")


In der RDP Cosole von Buexserv



        10. BuexServ
        11. BuexBuero
11. Kameras
12. Videoausgabe
13. Drucker
14. Scanner
15. Steuerung Strom
16.  Tools

Systemtools:

sysinto4wp.sh:

Zweck: Systeminfo auf dem Desktop Hintergund

Installation : standradscript sammlung + Hintrergrund für die Auflösung + crontab für aktualisierung

vnc server:

neofetch:


```
Install : sudo apt-get neofetch (auf lubuntu bereits standard)
Config: ${HOME}/.config/neofetch/config.conf
Standard + 'info "Disk" disk' und 'info "Local IP" local_ip' 
Aufruf: neofetch


Browser: "falkon"
```


Arduino IDE (Sloeber/PlatformIO IDE)

SSH

VNC

RDP

mRemoteNG (Win) / Remmina (Linux)

 \
Toolset Programmierung

Arduino IDE

Python

GitHub

VSCode



* Plattformio Extension
* GitHub Extension
* C/C++ Extensioj Pack
