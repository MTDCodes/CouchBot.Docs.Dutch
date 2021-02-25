.. _troubleshooting:

=====================
Hulp bij problemen
=====================

------------------------
Bot Vereiste Toestemmingen
------------------------

Wanneer **CouchBot** zich aanmeld op je server zou hij moeten vragen om alle vereiste toestemmingen als het scherm komt van toetreden tot je server.
Om zeker te zijn dat **CouchBot** volledig op je server kan functioneren, zorg ervoor dat de volgende toestemmingen zijn gegeven aan zijn server rol:

- Rollen beheren (Voor Live Discovery / Rol Toewijzing)
- Text kanalen lezen (Voor ALLE Functies)
- Berichten sturen (Voor ALLE Functies)
- Berichten beheren (Voor DeleteOffline Functie)
- Links met koppelingen toevoegen (Voor ALLE Functies)
- Lees berichtgeschiedenis (Voor ALLE Functies)
- Everyone noemen (Voor Ping Functie)

Als je problemen hebt kun je de volgende commando's gebruiken om uit te vinden waar het probleem in zit.

.. Let op:: Controleer dat het kanaal ook de juiste toestemmingen heeft zodat **CouchBot** kan reageren!

+-------------+----------------------------------+--------------------------------------------------------+
| Naam        | Voorbeeld                        | Wat doet het                                           |
+-------------+----------------------------------+--------------------------------------------------------+
| ping        | ``!cb ping``                     | Zou een "*pong*" reactie moeten geven.                 |
+-------------+----------------------------------+--------------------------------------------------------+
| permissions | ``!cb permissions #ChannelName`` | Controleert de toestemmingen van de bot in het kanaal. |
+-------------+----------------------------------+--------------------------------------------------------+
| prefix      | ``@CouchBot#9915 prefix``        | Vertelt je je prefix                                   |
+-------------+----------------------------------+--------------------------------------------------------+
| uptime      | ``!cb uptime``                   | Toont de uptime van de bot                             |
+-------------+----------------------------------+--------------------------------------------------------+