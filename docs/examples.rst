.. _examples:

=============
Voorbeelden Setup
=============

--------------
Aankondigingen
--------------

In deze scenario's, hebben we al :ref:`Installatie Uitleg <couchquick>` gevolgd en hebben we de correcte :ref:`Toestemmingen <troubleshooting>` structuur.
We zullen ``MattTheDev`` gebruiken als streamer account en ``#notification`` als het Discord kanaal om de aankondigingen te plaatsen.

.. admonition:: Scenario 1

   Alleen aankondigen als de Server Owner **Live** gaat met een everyone ping.

Veel mensen willen een bot die hun aankondigt als ze live gaan. CouchBot kan dit!
We beginnen met toestaan dat de bot live stream aankondigingen doet, gevolgd door toevoegen van de creator.
Dan vertellen we de bot om de everyone rol te pingen en gaan de bot die toestemming geven.

.. code-block:: none

    !cb allow live
    !cb twitch MattTheDev #notification

.. admonition:: Scenario 2

   Mensen automatisch aankondigen zonder ze 1 voor 1 toe te voegen.

In plaats van mensen 1 voor 1 toe te voegen, heb je de optie de bot automatisch mensen uit je server te laten kiezen.
Dit verkort de setup tijd drastisch en maakt het setup proces makkelijker voor je.
Als eerste, moet je toestaan dat de bot live aankondigingen mag plaatsen en dan stel je het standaard kanaal in.
Daarna vertel je de bot om iedereen met een streaming status te zoeken en je bent klaar!

.. Opmerking:: De streamer moet de status "Streaming" hebben om automatisch te worden aangekondigt.

.. code-block:: none

    !cb allow live
    !cb channel live #notification
    !cb allow livediscovery all

.. admonition:: Scenario 3

   Automatisch een specifieke rol aankondigen als mensen met die rol live gaan

Stel je voor dat je iemand met de rol VIP automatisch wilt laten aankondigen. Om dit te doen, moet je de bot toestemming 
geven om Live te plaatsen en vertellen in welke kanaal dat te doen.
Alles wat dan nog gedaan moet worden is de bot vertellen welke rol mensen moeten hebben om aangekondigt te worden!

.. Opmerking:: De streamer moet de status "Streaming" hebben om automatisch aangekondigt te worden.

.. code-block:: none

    !cb allow live
    !cb channel live #notification
    !cb allow livediscovery role @VIP

.. admonition:: Scenario 4

   Owner aankondigingen apart van alle anderen

Sommige servers willen misschien dat de Owner of andere "VIP" types apart van de anderen worden aangekondigt.
Om dit voor elkaar te krijgen geven we toestemmingen voor Live te plaatsen, daarna voegen we de streamers toe zoals gewenst en het kanaal waarin ze aangekondigt moeten worden.

.. code-block:: none

    !cb allow live
    !cb twitch MattTheDev #ownerchannel
    !cb twitch Jaymei #otherchannel

.. admonition:: Scenario 5

   YouTube VOD en Live aankondigingen in verschillende kanalen

We beginnen met toestemming geven aan de bot om zowel Live als gepubliceerde content te plaatsen. De commando's hebben een schakelfunctie (aan/uit), het zal op de nieuwe instelling reageren.
Dan gaan we het youtube channel toevoegen door gebruik te maken van het "ChannelID_" en vertellen in welk kanaal het geplaatst moet worden 
en we geven aan of het gaat om **Live** of **VOD**.
Het is ook mogelijk om het leeg te laten zodat ze allebei in hetzelfde kanaal geplaatst worden of door het argument "both" toe te voegen.

.. _ChannelID: https://youtube.com/account_advanced

.. code-block:: none

    !cb allow live
    !cb allow published
    !cb youtube UC123456 #livechannel live
    !cb youtube UC123456 #publishedchannel vod

.. admonition:: Scenario 6

   Owner apart aangekondigd van anderen met benoemen van verschillende groepen en met aangepaste berichten.

Je wilt @everyone laten weten als je live gaat.
Je wilt @Streamer laten weten als anderen live gaan.
Het 3e commando zal het standaard live aankondigingsbericht gebruiken.

.. code-block:: none

    !cb mixer MattTheDev #BigNotification "@everyone CouchBot creator **MattTheDev** is now online!"
    !cb mixer Jaymei #notification "@Streamer Another custom message!"
    !cb mixer EmElle #notification

--------
Berichten
--------

Je wilt misschien wat aangepaste berichten maken met **CouchBot** om je server te laten weten dat je live bent of misschien om een nieuw lid te verwelkomen. 
De onderstaande commando's laten je zien hoe je dat kan doen!

.. admonition:: Scenario 1

   Instellen Hallo en Vaarwel berichten

.. Opmerking:: Je kan de variabelen **%USER%** en **%RANDOMUSER%** gebruiken

.. code-block:: none

    !cb allow greetings
    !cb channel greetings #channel-name
    !cb message greeting "Your Custom Greeting Message"
    
    !cb allow goodbyes
    !cb channel goodbyes #channel-name
    !cb message goodbye "Your Custom Goodbye Message"

.. admonition:: Scenario 2

   Instellen aangepast aankondigingsbericht

Je zou graag een wat meer persoonlijker live bericht willen hebben?
Dan kan je het onderstaande gebruiken;

.. Opmerking:: Je kan de variabelen **%TITLE%, %GAME%, %CHANNEL% of %URL%** gebruiken

.. code-block:: none

    !cb message live "Your Custom Live Message"	
    !cb message published "Your Custom VOD Message"