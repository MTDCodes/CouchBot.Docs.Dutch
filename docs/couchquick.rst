.. _couchquick:

============================
CouchBot Installatie Uitleg
============================

Om CouchBot in je server te krijgen en te houden, zul je je moeten inschrijven op Patreon en je server moeten whitelisten.
Om dit te doen volg de uitleg hieronder;

.. Waarschuwing:: Dit MOET worden gedaan als je CouchBot wilt gebruiken!

1. `Schrijf je in voor 1 van de Patreon tiers! <https://patreon.com/CouchBot>`_
2. `Link je Patreon met je Discord account <https://www.patreon.com/settings/apps>`_
3. `Meld je aan op de support server om je servers toe te voegen <https://discord.couch.bot>`_
4. Voeg je Mixer, Picarto, Twitch of YouTube Kanalen toe:

.. code-block:: none

    !cb mixer YourMixerName #ChannelName
    !cb picarto YourPicartoName #ChannelName
    !cb twitch YourTwitchName #ChannelName
    !cb youtube YourYouTubeChannelID #ChannelName vod
    !cb youtube YourYouTubeChannelID #ChannelName live
    !cb youtube YourYouTubeChannelID #ChannelName both

.. Opmerking:: Om je YouTube Channel ID te krijgen bekijk `deze uitleg <https://youtube.com/account_advanced>`_.
          Het is 24 karakters lang en begint met UC.


5. Tot slot, vertel **CouchBot** of het is toegestaan om live en gepubliceerd te plaatsen

.. code-block:: none

    !cb allow published (wel of niet toestaan van gepubliceerde content)
    !cb allow live (wel of niet toestaan van live content)

Klaar!

.. Opmerking:: Als je tegen problemen aanloopt, controleer de toestemmingen die zijn toegewezen aan het kanaal en de bot.
