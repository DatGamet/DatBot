******
Twitch
******

Informationen
=============
Dies sind alle Befehle, die mit Twitch zu tun haben. Um die Streambenachrichtigungen zu verwalten, benötigst du die Rechte, den Server zu verwalten.

Befehle
=======
``/twitch info [channel_name]``
-------------------------------
Zeigt Informationen über einen Twitchkonto an. 

#* [channel_name]: Dies ist der Kanalname von dem Konto.

``/twitch notification add [channel_name] <channel> <message> <mention>``
-------------------------------------------------------------------------
Sendet eine Benachrichtigung, wenn der Nutzer aus dem [channel_name]-Argument anfängt zu streamen.

#* [channel_name]: Dies ist der Kanalname. Dieser muss valid sein.
#* <channel>: In diesen Kanal wird die Streambenachrichtigung gesendet.
#* <message>: Diese Nachricht wird in den Kanal gesendet
#* <mention>: Diese Rolle wird erwähnt, wenn der Kanal anfängt zu streamen.

``/twitch notification list``
-----------------------------
Gibt eine Liste von allen Kanälen aus, denen DatBot folgt.

``/twitch notification remove [channel_name]``
-------------------------------------------------------------------------
Entfernt die Streambenachrichtigung von dem angegeben Kanal.

#* [channel_name]: Dies ist der Kanalname. Dieser muss valid sein.

``/twitch notification toggle [channel_name]``
-------------------------------------------------------------------------
Aktiviert doer deaktiviert die Streambenachrichtigung für den angegebenen Kanal.

#* [channel_name]: Dies ist der Kanalname. Dieser muss valid sein.
