# Verkehrssignalanlagen (CODESYS)
<h1>Aufgabenstellung</h1>
Ziel dieses Projekts ist die Entwicklung eines Programms zur Steuerung einer Ampelanlage an einer Kreuzung. Dabei soll sichergestellt werden, dass sich kreuzende Straßen nicht gleichzeitig grünes Licht erhalten, um die Verkehrssicherheit zu gewährleisten.​
<br />
<br />
<img src="https://i.imgur.com/SokOxJy.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
● Variablendefinition: Identifikation und Deklaration aller notwendigen Variablen für die Ampelsteuerung.​
<br />
● Einzelne Ampelsteuerung: Entwicklung eines Funktionsbausteins zur Steuerung einer einzelnen Ampel.​
<br />
● Synchronisation der Ampeln: Koordination der vier Ampeln an der Kreuzung, sodass keine zwei sich kreuzenden Straßen gleichzeitig grünes Licht erhalten.
<br />

<h2>2. Umsetzung </h2>
<h3>Einzelne Ampelsteuerung implementieren </h3>
Beginnen Sie mit der Programmierung einer einzelnen Ampelsteuerung, indem Sie eine Funktion namens "Ampel" erstellen. Diese Funktion sollte die grundlegenden Abläufe einer Ampel regeln, einschließlich der Phasen für Rot, Gelb und Grün.
Da gegenüberliegende Ampeln identisch arbeiten, können Sie die zuvor erstellte Funktion Ampel duplizieren und für die gegenüberliegende Ampel verwenden. Dies gewährleistet, dass beide Ampeln synchron geschaltet werden.
<br />
<br />
<img src="https://i.imgur.com/9YrcMLH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<h3>Kreuzungslogik implementieren </h3>
Um sicherzustellen, dass sich kreuzende Straßen nicht gleichzeitig grünes Licht erhalten, nutzen Sie RS-Flipflops, Timerbausteine (TON) und Sensoren. Diese Komponenten ermöglichen es, die Ampelphasen so zu steuern, dass immer nur eine Fahrtrichtung Grün erhält, während die anderen auf Rot stehen.
<br />
<br />
<img src="https://i.imgur.com/Rtd2zyP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

<h2> Vorführung visualisieren </h2>
<a href="https://youtu.be/DQ7Vontirnc" target="_blank">
    <img src="https://i.imgur.com/skqjKPr.png" alt="Video abspielen" style="width:50px;height:50px;">
</a>
<img src="https://i.imgur.com/gBQBU0V.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />


