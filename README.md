# PushToSky - En

Phone-based Astronomical Telescope Control, Simply 

Push to Sky is a low-cost control system for astronomical telescopes that uses mobile phone sensors. 

Connect to the world of stars – look up at the sky and control smartly! 

🌟 Key Features

📱 Phone-based manual control The current direction of the telescope can be determined and tracked in real-time using the mobile phone's sensors (gyroscope, accelerometer, compass). 

🎯 Compatible with azimuthal telescopes Specifically designed for alt-azimuth mechanical systems, making it easy to use with Dobsonians, refractors, or beginner non-motorized systems. 

🛰️ Sensor data processing with Kalman filter Filters and smooths noisy mobile sensor data, providing a more reliable position estimate of the telescope's direction. 

✨ Star calibration and correction Through one-star or multi-point teaching, the system can correct sensor errors – ensuring even more precise targeting. 

🌐 Client-server connection Phone data is sent to the PC via Wi-Fi, where the system displays the current direction, suggests movements, and allows orientation using a virtual sky. 

## User Manual 

Installation Kit: 

Phone: 

-TelescopeMotionSender for Push_to_Sky.apk (Sends orientation data to the Push_to_Sky system) 

-GPS Sender for Push_to_Sky.apk (Sends GPS data to the Push_to_Sky system) 

Laptop/Desktop: 

-Push_to_Sky

-config.ini file 

How to use: 

Mount the phone on the telescope. 

Install TelescopeMotionSender for Push_to_Sky.apk and GPS Sender for Push_to_Sky.apk on your phone. 

Place the Push_to_Sky and config.ini files in the same folder on your laptop. 

Start the Push_to_Sky application, then GPS Sender for Push_to_Sky.apk from your phone. This will provide your exact location to the Push_to_Sky application (Remember to provide your laptop's exact IP address). 

Restart the Push_to_Sky application. 

Now, start the TelescopeMotionSender for Push_to_Sky.apk (Sends orientation data to the Push_to_Sky system) application on your phone (Remember to provide your laptop's exact IP address). 

Point the telescope, for example, at Antares and mark it in the one-star teaching. 

Now, in the Tracking tab, you can select an object you like (Deep sky objects/M3), where the system will navigate using the control system. 

Phone sensors are not very accurate, so manual correction may be needed occasionally. 


## Explanation:

*Settings

** Azimuth Correction by Elevation:
A common error with phone sensors is that the azimuth value drifts when measuring elevation from 0 to 90 degrees. This function is designed to correct that drift between 0–180 and 180–360 degrees.

** Direction Indicator Sensitivity (Degrees):
The sensitivity of the direction indicator system located under the “Tracking” tab can be adjusted between 0.3–1 degrees.

** Orientation Data (UDP):
Orientation data received from the phone's sensors (in degrees).


*Tracking

** Target Selection:
Contains a search field and a list of celestial objects from which you can select the object you wish to observe (Bright Stars, Deep Sky Objects, Solar System).

** Calculated Celestial Body Position:
The position of the celestial object selected in the “Target Selection” section.

** Direction Indicator:
Here you can choose whether to use raw or filtered (Kalman filter) data. The latter can assist during telescope movement. Arrows assist in moving the telescope, and a green dot indicates target acquisition.

** Multi-point Alignment:
You can mark multiple objects for calibration purposes from the “Target Selection” section. Point the telescope at a selected object, then mark it with the “Mark for Calibration” button. Repeat as desired with additional objects. After marking 1, 2, 3, or even 4 objects, click the “Perform Calibration” button.
During the day, the PushToSky system can even be calibrated using a single mark on the Moon.

** Current Position and Offset:
Indicates the current direction of the telescope and provides the option for manual correction and offsetting.

** Virtual Sky:
After pressing the button, a virtual sky view opens up, which can help with orientation in the night sky.

*One-Star Alignment

Point the telescope at a star, for example, Polaris. Select Polaris from the list, then press the “Current Position and Offset” button. After this, under the “Tracking” tab in the “Target Selection” section, you can choose a target object.






# PushToSky - Hu

Telefonalapú Csillagászati Teleszkóp Irányítás, Egyszerűen.

Push to Sky egy alacsony költségű vezérlőrendszer csillagászati távcsövekhez, amely mobiltelefon szenzorait használja.

Kapcsolódj a csillagok világához – nézz fel az égre, és irányíts okosan!

🌟 Főbb jellemzők

📱 Telefonalapú kézi vezérlés
A távcső aktuális iránya valós időben meghatározható és követhető a mobiltelefon szenzorai (giroszkóp, gyorsulásmérő, iránytű) segítségével.

🎯 Alt-azimutális távcsövekkel kompatibilis
Kifejezetten az alt-azimutális mechanikai rendszerekhez tervezve, így könnyen használható Dobson-rendszerű, refraktoros vagy kezdő, motor nélküli távcsövekkel.

🛰️ Szenzoradat-feldolgozás Kalman-szűrővel
A rendszer kiszűri és kisimítja a mobiltelefon zajos szenzoradatait, megbízhatóbb iránymeghatározást biztosítva a távcső számára.

✨ Csillagkalibráció és korrekció
Egycsillagos vagy többpontos tanítással a rendszer képes korrigálni a szenzorhibákat – így még pontosabb célzást tesz lehetővé.

🌐 Kliens-szerver kapcsolat
A telefon adatai Wi-Fi-n keresztül jutnak el a számítógéphez, ahol a rendszer megjeleníti az aktuális irányt, mozgásokat javasol, és egy virtuális égbolton segíti a tájékozódást.

## Használati útmutató

Telepítőkészlet:

Telefon:

-TelescopeMotionSender for Push_to_Sky.apk (A távcső irányadatainak küldése a Push_to_Sky rendszer felé)

-GPS Sender for Push_to_Sky.apk (GPS-adatok küldése a Push_to_Sky rendszer felé)

Laptop/Asztali gép:

-Push_to_Sky alkalmazás

-config.ini fájl

Így használd:

Rögzítsd a telefont a távcsőre.

Telepítsd a telefonra a TelescopeMotionSender for Push_to_Sky.apk és a GPS Sender for Push_to_Sky.apk alkalmazásokat.

Helyezd a Push_to_Sky és a config.ini fájlokat ugyanabba a mappába a számítógépen.

Indítsd el a Push_to_Sky alkalmazást, majd indítsd el a telefonon a GPS Sender for Push_to_Sky.apk alkalmazást. Ez továbbítja a pontos helyzetedet a rendszernek (Ne felejtsd el megadni a számítógép pontos IP-címét).

Indítsd újra a Push_to_Sky alkalmazást.

Ezután indítsd el a TelescopeMotionSender for Push_to_Sky.apk alkalmazást a telefonon (Ismét add meg a számítógép pontos IP-címét).

Irányítsd a távcsövet például az Antares csillagra, és jelöld be az egycsillagos tanításban.

Most a Tracking (Követés) fülön kiválaszthatsz egy tetszőleges objektumot (pl. Deep Sky objektum/M3), és a rendszer a vezérlőrendszer segítségével odanavigál.

A telefon szenzorai nem túl pontosak, így időnként kézi korrekcióra szükség lehet.


## Magyarázat:

* Beállítások

** Azimut Korrekció Emelkedésfüggően (Fok):

A telefonszenzoroknál gyakori hiba, hogy magasságmérésnél 0-ról 90 fokig az Azimute érték is elcsúszik. Ez a funkció ezt hivatott korrigálni 0 - 180 illetve 180 - 360 fok között.

** Irányító Rendszer Érzékenysége (Fok):

A „Követés” fülön elhelyezkedő irányjelző rendszer érzékenysége állítható 0,3 -1  fok között.

** Orientációs Adatok (UDP)

A telefonszenzoról érkező orientációs adatok (Fok).


* Követés

** Célpont Kiválasztása:

Tartalmaz egy keresőmezőt és egy égitest listát ahonnan kiválaszthatjuk a megfigyelni kívánt objektumot (Fényes Csillagok, Mélyég Objektumok, Naprendszer).

** Számított Égitest Pozíció:

A  „Célpont Kiválasztása” szekcióban kiválasztott égitest pozíciója. 


** Irányjelző: 

Itt választható, hogy nyers vagy szűrt (Kalman szűrő) adatokat használjunk. Utóbbi teleszkóp mozgatása közben lehet a segítségünkre.
A teleszkóp mozgatását nyilak segítik, célra találás egy zöld pötty jelöli.

** Többpontos Tanítás:

A „Célpont Kiválasztása” szekcióból több objektumot is megjelölhetünk tanítás céljából. Irányítsuk a teleszkópot egy kiválasztott objektumra, majd jelöljük meg a „Megjelölés Kalibrációhoz” gombbal majd ismételjük meg tetszőleges számban további objektumokkal. 1,2,3 vagy akár 4 objektum jelölése után kattintsunk a „Kalibráció Végrehajtása” gombra.
Nappal akár a Hold egyszeri megjelölésével is tanítható a PushToSky rendszer.

** Jelenlegi Pozíció és Eltolás:

Jelöli a teleszkóp aktuális irányát és lehetőséget ad kézi korrigálásra, eltolásra.

** Virtuális Égbolt

A gomb megnyomását követően egy virtuális égbolt nyílik meg amely segíthet az égbolton való tájékozódásban.

* Egycsillagos tanítás (Alignment)

Irányítsuk a teleszkópot például a sarkcsillagra. A listából jelöljük meg a sarkcsillagot majd nyomjuk meg a „Jelölés és Korrekció” gombot. Ez után a „Követés” fülön a „Célpont Kiválasztása” szekcióban választhatunk célpont objektumot.

Contact: pushtoskyhelp@gmail.com
