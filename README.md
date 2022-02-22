# App-Marketing
<p>
Im Rahmen des Wahlpflichtfaches App Marketing an der Hochschule Kaiserslautern bei Herrn Speck habe ich mich mit den folgenden Aufgaben beschäftigt: Google Maps - Mapping App, Custom Open Street Map (Bicycle), Bluetooth Hear Rate App.
  </p>
<p>
  Für genaue Infos zur Bearbeitung der Aufgaben ist im Repositorie der Foliensatz hinterlegt. Dort finden sich Beschreibungen zum Erstellen der Apps.
  </p>



# Google Maps - Mapping App

Eine Android Tracking App, die den Standort abrufen, aktualisieren, speichern und in Form von Markern, Linien oder Heatmaps auf der Karte von Google Maps darstellen kann.
Zur Erstellung der App wurde die Dokumentation: „Maps SDK für Android“ genutzt, die von Google bereitgestellt wird.
Sie beinhaltet Guides, Dokumentationen und Beispiele.
Maps SKD für Android: https://developers.google.com/maps/documentation/android-sdk/map

Benötigte Tools: Android Studio

# Custom Open Street Map (Bicycle)
<p>
Eine Android App, die eine benutzerdefinierte, täglich aktualisierte Open Street Map für Fahrradnutzer auf dem Smartphone lädt. Die Open Street Map Daten von Geofabrik werden durch einen automatisierten Prozess akutell gehalten, auf das Saarland heruntergeschnitten, mit OSM Tags gefiltert und über einen FTP-Server verfügbar gestellt. Die App greift sich diese Daten und rendert sie mithilfe eines Renderthemes nach einem gewünschten Layout (hier benutzerfreundlich für Fahrradnutzer). Dieser letzte Schritt ist noch nicht vollendet und wird in naher Zukunft bearbeitet. Entscheidend für die Umsetzung waren folgende Guides von Mapsforge: https://github.com/mapsforge/mapsforge. </p> <p> Wenn Ihr die App selbst testen wollt, benötigt Ihr die Datei saarland.map, die sich hier im Repositorie befindet und das Rendertheme, welches Ihr unter diesem Link findet: https://github.com/mapsforge/mapsforge/tree/master/mapsforge-themes/src/main/resources/assets/mapsforge und benennt es in default.xml um. Beide Dateien müssen nur noch auf eurem Gerät im Root Verzeichnis der SD-Karte hinterlegt werden, dann könnt ihr die App starten. 
</p>  

# Bluetooth Heart Rate App
<p>
Eine Android App, die sich mit einem Bluetooth LE Heart Rate Sensor (Brustgurt) verbindet und den eigenen Herzschlag auf dem Display anzeigt.
Entscheidend für die Umsetzung waren die Guides von Android: https://developer.android.com/guide/topics/connectivity/bluetooth/ble-overview, Shahar Avigezer: https://medium.com/@shahar_avigezer/bluetooth-low-energy-on-android-22bc7310387a. Die Bluetooth Spezikationen lassen sich hier finden: https://www.bluetooth.com/de/specifications/specs/. </p>
<p>
Damit Ihr die App selbst testen könnt, benötigt ihr einen Bluetooth LE Brustgurt. Diesen zieht ihr nach Gebrauchsanweisung an und startet dann die App und sucht nach Bluetooth LE Geräten. Nachdem Ihr euer Gerät gefunden habt, notiert Ihr euch die MAC-Adresse. Diese könnt Ihr dann im Code integrieren, sodass sich die App mit eurem Gerät verbinden kann. Dieser Prozess lässt sich noch optimieren, indem man implementiert, dass durch Anklicken des gefundenen und gewünschten Gerätes die Mac-Adresse übergeben wird. Danach ist es möglich über den Button "Connect to Sensor" den Herzschlag auszulesen.
  </p>
