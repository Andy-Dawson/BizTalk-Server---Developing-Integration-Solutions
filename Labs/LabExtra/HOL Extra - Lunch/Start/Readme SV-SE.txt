

1. Generera ett schema utifr�n Mat.xml

F�r att aktivera Generate Schema from Well-know XML, k�r C:\Program Files (x86)\Microsoft BizTalk Server 2013\SDK\Utilities\Schema Generator\InstallWFX.vbs

2. Importera schema Restaurang.xsd

3. Skapa en mappning mellan Mat och Restaurang

4. Signera projektet

5. Deploya projektet

6. Skapa en OneWay receive port f�r att kunna ta in Mat.xml
OBS! Uppdatera Mat med namnet p� den restaurang du vill bes�ka p� Fredag
OBS 2! Gl�m inte att konfigurera mappningen

7. Skapa en OneWay send port som skall s�nda meddelanden till addressen 
https://a372wabs.servicebus.windows.net/Lunch
OBS! Gl�m inte filter

8. Aktivera och starta portarna

9. Skicka meddelandet

