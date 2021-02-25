.. _messages:

==============
Berichten Setup
==============

Gebruik de volgende commando's voor instellen van aangepaste berichten en om ze te testen.

.. Opmerking:: De volgende variabelen zijn beschikbaar om te gebruiken voor de **Live** en **Published** berichten.
.. code-block:: none

    %TITLE%
    %GAME% - Werkt niet voor YouTube
    %CHANNEL%
    %URL%

.. Opmerking:: De volgende variabelen zijn beschikbaar om te gebruiken voor de **Welkom** en **Vaarwel** berichten.
.. code-block:: none

    %USER%
    %RANDOMUSER%

+-------------------+---------------------------------------------------------+-----------------------------------------------+
| Naam              | Voorbeeld                                               | Wat doet het                                  |
+-------------------+---------------------------------------------------------+-----------------------------------------------+
| message live      | ``!cb message live "Your Custom Live Message"``         | Verandert je live bericht voor de server.     |
+-------------------+---------------------------------------------------------+-----------------------------------------------+
| message published | ``!cb message published "Your Custom VOD Message"``     | Verandert je VOD bericht voor de server.      |
+-------------------+---------------------------------------------------------+-----------------------------------------------+
| message offline   | ``!cb message offline "Your Custom Offline Message"``   | Verandert je offline bericht voor de server.  |
+-------------------+---------------------------------------------------------+-----------------------------------------------+
| message greeting  | ``!cb message greeting "Your Custom Greeting Message"`` | Verandert je welkom bericht voor de server.   |
+-------------------+---------------------------------------------------------+-----------------------------------------------+
| message goodbye   | ``!cb message goodbye "Your Custom Goodbye Message"``   | Verandert je vaarwel message voor de server.  |
+-------------------+---------------------------------------------------------+-----------------------------------------------+

Als je je berichten wil resetten naar de standaard berichten, gebruik dan de volgende commando's;

+-------------------+---------------------------------+----------------------------------------------+
| Naam              | Voorbeeld                       | Wat doet het                                 |
+-------------------+---------------------------------+----------------------------------------------+
| message live      | ``!cb message live clear``      | Resets je live bericht voor de server.       |
+-------------------+---------------------------------+----------------------------------------------+
| message published | ``!cb message published clear`` | Resets je VOD bericht voor de server.        |
+-------------------+---------------------------------+----------------------------------------------+
| message offline   | ``!cb message offline clear``   | Resets je offline bericht voor de server.    |
+-------------------+---------------------------------+----------------------------------------------+
| message greeting  | ``!cb message greeting clear``  | Resets je welkom bericht voor de server.     |
+-------------------+---------------------------------+----------------------------------------------+
| message goodbye   | ``!cb message goodbye clear``   | Resets je vaarwel bericht voor de server.    |
+-------------------+---------------------------------+----------------------------------------------+

Om het bericht buiten de embed leeg te laten, gebruik het volgende;

+-------------------+---------------------------------+---------------------------------------------------------------------+
| Naam              | Voorbeeld                       | Wat doet het                                                        |
+-------------------+---------------------------------+---------------------------------------------------------------------+
| message live      | ``!cb message live empty``      | Verwijder het bericht buiten de embed voor live stream aankondiging.|
+-------------------+---------------------------------+---------------------------------------------------------------------+
| message published | ``!cb message published empty`` | Verwijder het bericht buiten de embed voor published aankondiging.  |
+-------------------+---------------------------------+---------------------------------------------------------------------+

Als je je berichten wilt testen, gebruik de volgende commando's;

+-------------------+----------------------------------------+----------------------------------------------+
| Naam              | Voorbeeld                              | Wat doet het                                 |
+-------------------+----------------------------------------+----------------------------------------------+
| test live         | ``!cb test live #DiscordChannel``      | Test je live bericht voor de server.         |
+-------------------+----------------------------------------+----------------------------------------------+
| test published    | ``!cb test published #DiscordChannel`` | Test je VOD bericht voor de server.          |
+-------------------+----------------------------------------+----------------------------------------------+
| test greeting     | ``!cb test greeting``                  | Test je welkom bericht voor de server.       |
+-------------------+----------------------------------------+----------------------------------------------+
| test goodbye      | ``!cb test goodbye``                   | Test je vaarwel bericht voor de server.      |
+-------------------+----------------------------------------+----------------------------------------------+
