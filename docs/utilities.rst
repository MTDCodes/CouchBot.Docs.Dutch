.. _utilities:

==========
Extra Tools
==========

Gebruik de volgende commando's om diverse dingen in te stellen en om bits en bobs van de bot te zien.

+--------------------------+--------------------------------------+----------------------------------------------------------+
| Naam                     | Voorbeeld                            | Wat doet het                                             |
+--------------------------+--------------------------------------+----------------------------------------------------------+
| info                     | ``!cb info``                         | Geeft een kort overzicht van de bot.                     |
+--------------------------+--------------------------------------+----------------------------------------------------------+
| invite                   | ``!cb invite``                       | Stuurt je een beicht met de bot uitnodiging.             |
+--------------------------+--------------------------------------+----------------------------------------------------------+
| ytidlookup               | ``!cb ytidlookup "Channel Name"``    | Probeert een channel ID voor YouTube te vinden.          |
+--------------------------+--------------------------------------+----------------------------------------------------------+
| whatsthis                | ``!cb whatsthis``                    | Geef een link naar een afbeelding om het uit te vinden.  |
+--------------------------+--------------------------------------+----------------------------------------------------------+
| config list              | ``!cb config list``                  | Toont de configuratie lijst van de bot.                  |
+--------------------------+--------------------------------------+----------------------------------------------------------+
| config deleteoffline     | ``!cb config deleteoffline``         | Verwijdert offline streams.                              |
+--------------------------+--------------------------------------+----------------------------------------------------------+
| config textannouncements | ``!cb config textannouncements``     | Aankondigingen in text in plaats van koppelingen.        |
+--------------------------+--------------------------------------+----------------------------------------------------------+
| clap                     | ``!cb clap place your text here``    | Plaatst een clap in alle ruimtes.                        |
+--------------------------+--------------------------------------+----------------------------------------------------------+
| cookies                  | ``!cb cookies place your text here`` | Plaatst een cookie in alle ruimtes.                      |
+--------------------------+--------------------------------------+----------------------------------------------------------+

--------------------
Willekeurige aankondigingen
--------------------

+-----------------+--------------------------------+-----------------------------------------------------------------------------------------------+
| Naam            | Voorbeel                       | Wat doet het                                                                                  |
+-----------------+--------------------------------+-----------------------------------------------------------------------------------------------+
| announce random | ``!cb announce random twitch`` | Kondigt een willkeurige stream aan in het kanaal waar je dit in typt (**Alleen Admin Optie**) |
+-----------------+--------------------------------+-----------------------------------------------------------------------------------------------+
| dm random       | ``!cb dm random twitch``       | Stuurt een DM met een willekeurige stream naar de gebruiker die het commando heeft gebruikt.  |
+-----------------+--------------------------------+-----------------------------------------------------------------------------------------------+

-----------------------
Purge (Verwijder) Berichten
-----------------------

Soms wil je misschien kanalen opruimen door berichten te verwijderen of berichten van een specifiek persoon te verwijderen, als ondersteuning voor de moderatie van je server.
Om dat voor elkaar te krijgen kun je de volgende commando's gebruiken.

.. Waarschuwing:: Je moet de **Beheer Berichten** toestemmingen hebben om dit commando te gebruiken!
			 Eenmaal gebruikt kun je verwijderde berichten NIET terughalen.

+-------+------------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------+
| Naam  | Voorbeeld                                      | Wat doet het                                                                                                                        |
+-------+------------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------+
| purge | ``!cb purge``                                  | Verwijdert 100 berichten in het huidige kanaal.                                                                                     |
+-------+------------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------+
| purge | ``!cb purge 25``                               | Dit verwijdert 25 berichten in het huidige kanaal.                                                                                  |
+-------+------------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------+
| purge | ``!cb purge 25 #DiscordChannel``               | Dit verwijdert 25 berichten in het geselecteerde kanaal.                                                                            |
+-------+------------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------+
| purge | ``!cb purge 25 #DiscordChannel true``          | Dit verwijdert 25 berichten in het geselecteerde kanaal plus de gepinde berichten.                                                  |
+-------+------------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------+
| purge | ``!cb purge @MattTheDev``                      | Verwijdert alle berichten van gebruiker kijkend naar de laatste 100 berichten in het huidge kanaal.                                 |
+-------+------------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------+
| purge | ``!cb purge @MattTheDev true``                 | Verwijdert alle berichten van gebruiker kijkend naar de laatste 100 berichten in het huidge kanaal plus de gepinde berichten.       |
+-------+------------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------+
| purge | ``!cb purge @MattTheDev #DiscordChannel``      | Verwijdert alle berichten van gebruiker kijkend naar de laatste 100 berichten in het geselecteerde kanaal.                          |
+-------+------------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------+
| purge | ``!cb purge @MattTheDev #DiscordChannel true`` | Verwijdert alle berichten van gebruiker kijkend naar de laatste 100 berichten in het geselecteerde kanaal plus de gepinde berichten.|
+-------+------------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------+
