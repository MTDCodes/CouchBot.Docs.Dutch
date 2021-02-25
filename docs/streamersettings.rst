.. _creatorsettings:

===============
Creators toevoegen
===============

.. Opmerking:: Deze commando's zijn een schakelfunctie (aan/uit), als je iemand van de lijst wilt verwijderen, gebruik het commando nog een keer.

+--------------+-------------------------------------------------+-----------------------------------------------------------+
| Naam         | Voorbeeld                                       | Wat doet het                                              |
+--------------+-------------------------------------------------+-----------------------------------------------------------+
| mixer        | ``!cb mixer MattTheDev #DiscordChannel``        | Voegt een Mixer creator toe aan je lijst.                 |
+--------------+-------------------------------------------------+-----------------------------------------------------------+
| picarto      | ``!cb picarto MattTheDev #DiscordChannel``      | Voegt een Picarto creator toe aan je lijst.               |
+--------------+-------------------------------------------------+-----------------------------------------------------------+
| twitch       | ``!cb twitch MattTheDev #DiscordChannel``       | Voegt een Twitch creator toe aan je lijst.                |
+--------------+-------------------------------------------------+-----------------------------------------------------------+
| youtube      | ``!cb youtube UC24569877 #DiscordChannel vod``  | Voegt een Youtube creator (VOD) toe aan je lijst.         |
+--------------+-------------------------------------------------+-----------------------------------------------------------+
| youtube      | ``!cb youtube UC24569877 #DiscordChannel live`` | Voegt een Youtube creator (Live) toe aan je lijst.        |
+--------------+-------------------------------------------------+-----------------------------------------------------------+
| youtube      | ``!cb youtube UC24569877 #DiscordChannel both`` | Voegt een Youtube creator (VOD & Live) toe aan je lijst.  |
+--------------+-------------------------------------------------+-----------------------------------------------------------+
| creator list | ``!cb creator list``                            | Toont lijst van alle toegevoegde creators op de server.   |
+--------------+-------------------------------------------------+-----------------------------------------------------------+

Als je het graag wat persoonlijker wilt maken als je een specifieke creator toevoegt dan kan dat door het bericht in te stellen wat aangekondigt wordt.

.. note:: Je kan **@everyone** en **@here** gebruiken als je aangepaste berichten maakt!

Het 1e commando voegt een Mixer streamer met de naam MattTheDev toe om aangekondigt te worden in het kanaal #DiscordChannel.
Je ziet dat het een basis Discord formaat heeft en zal @everyone benoemen.

Het 2e commando bewerkt de aankondiging voor MattTheDev door het bericht aan te passen en de rol die wordt benoemd te veranderen.

Het 3e commando zal, als het na het 1e of het 2e commando wordt gebruikt, de aankondiging van de lijst van creators verwijderen en niet aankondigen in de toekomst.

.. code-block:: none

	!cb mixer MattTheDev #DiscordChannel "The Developer of CouchBot has gone **LIVE**, come watch @everyone"
	!cb mixer MattTheDev #DiscordChannel "Come watch Matt play @here"
	!cb mixer MattTheDev #DiscordChannel

.. important:: Je kan de onderstaande variabelen gebruiken voor **Live** and **Published** berichten.
.. code-block:: none

    %TITLE%
    %GAME% - Werkt niet voor YouTube
    %CHANNEL%
    %URL%
