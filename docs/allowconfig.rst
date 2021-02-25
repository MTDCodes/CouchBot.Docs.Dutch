.. _allowconfig:

===================
Configuratie voor toestemming in/uitschakelen 
===================

Gebruik de volgende commando's om de bot te configureren wat hij wel en niet mag doen.
Sommige van deze zoals ``!cb allow live`` zijn basis commando's om de bot in te stellen.

+------------------+--------------------------+----------------------------------------------------------------------------------------------+
| Naam             | Voorbeeld                | Wat doet het                                                                                 |
+------------------+--------------------------+----------------------------------------------------------------------------------------------+
| allow live       | ``!cb allow live``       | Schakelfunctie (aan/uit) voor stream aankondigingen voor live streamers.                     |
+------------------+--------------------------+----------------------------------------------------------------------------------------------+
| allow published  | ``!cb allow published``  | Schakelfunctie (aan/uit) voor aankondigingen van gepubliceerde video's.                      |
+------------------+--------------------------+----------------------------------------------------------------------------------------------+
| allow greetings  | ``!cb allow greetings``  | Schakelfunctie (aan/uit) voor welkomstberichten als een lid op de server komt.               |
+------------------+--------------------------+----------------------------------------------------------------------------------------------+
| allow goodbyes   | ``!cb allow goodbyes``   | Schakelfunctie (aan/uit) voor vaarwelberichten als een lid de server verlaat.                |
+------------------+--------------------------+----------------------------------------------------------------------------------------------+
| allow stats      | ``!cb allow stats``      | Schakelfunctie (aan/uit) voor het tonen van statistieken zoals "Totaal Bekeken" en "Volgers".|
+------------------+--------------------------+----------------------------------------------------------------------------------------------+
| allow thumbnails | ``!cb allow thumbnails`` | Schakelfunctie (aan/uit) om afbeelding toe te voegen bij het plaatsen van de stream info.    |
+------------------+--------------------------+----------------------------------------------------------------------------------------------+

.. note:: De "LiveDiscovery" optie werkt met alle platforms die worden ondersteunt door **CouchBot**.
`Gebruikers moeten zich registreren op de CouchBot Website <https://couch.bot/User/Registration>`_

**LiveDiscovery** is een optie van **CouchBot** die de noodzaak om elke creator handmatig toe te voegen overbodig maakt.

+---------------------+--------------------------------------------+-----------------------------------------------------------------------------------------------------+
| Name                | Example                                    | Usage                                                                                               |
+---------------------+--------------------------------------------+-----------------------------------------------------------------------------------------------------+
| allow livediscovery | ``!cb allow livediscovery none``           | Voorkomt het automatisch aankondigen van mensen met de status "Streaming".                          |
+---------------------+--------------------------------------------+-----------------------------------------------------------------------------------------------------+
| allow livediscovery | ``!cb allow livediscovery role @Streamer`` | Staat het automatisch aankondigen toe van mensen met de status "Streaming" en de rol van @Streamer. |
+---------------------+--------------------------------------------+-----------------------------------------------------------------------------------------------------+
| allow livediscovery | ``!cb allow livediscovery all``            | Staat het automatisch aankondigen toe van mensen met de status "Streaming".                         |
+---------------------+--------------------------------------------+-----------------------------------------------------------------------------------------------------+
