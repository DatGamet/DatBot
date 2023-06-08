*******
Moderation
*******


Informationen
================
Mit den Moderationsbefehlen kann man einen Server moderieren. Man braucht verschiedenste Rechte, um die Befehle nutzen zu können.

Befehle
================
``/moderation ban [user] <dm> <reason>``
------------------------
Mit ``/moderation ban`` kann man einen Nutzer von dem Server bannen. Man kann auch Nutzer bannen, die nicht auf dem Server sind. Dafür muss man die ID des Nutzers bei dem [user]-Argument angeben. Du und der Bot benötigen die Rechte, Nutzer zu bannen. 

- [user]: Dieser Nutzer wird von dem Server gebannt.
- <dm>: Sendet dem Nutzer eine Direktnachricht (falls möglich) und benachrichtigt diesen über die Bestrafung
- <reason>: Mit diesem Grund wird der Nutzer gebannt.

``/moderation clear [amount] <user> <channel>``
------------------------
Lösche Nachrichten mit ``/moderation clear``. Du und der Bot benötigen die Rechte, Nachrichten zu verwalten.

- [amount] oder [number]: Die Anzahl an Nachrichten, die gelöscht werden soll. Dies kann von 1 bis 100 alles sein.
- <user>: Nur von diesem Nutzer werden die Nachrichten gelöscht
- <channel>: Aus diesem Kanal werden die Nachrichten gelöscht.

``/moderation kick [user] <reason>``
------------------------
Kicke einen Nutzer von deinem Server. Du und Bot benötigen die rechte, Nutzer zu kicken.

- [user]: Dieser Nutzer wird von dem Server gekickt.
- <reason>: Mit diesem Grund wird der Nutzer gekickt.

``/moderation lock <reason> <time> <channel>``
------------------------
Sperre einen Kanal für ``@everyone``. Du und der Bot benötigen die Rechte, Kanäle zu verwalten. Der Bot braucht zusätzlich noch Links einbetten, Nachrichten senden und der Bot muss den Kanal sehen können.

- <reason>: Mit diesem Grund wird der Kanal gesperrt.
- <time>: Für diese Zeit wird der Kanal gesperrt. Dabei kann man h, m und ms nutzen. Als Beispiel 1h 30m, dies wären 1 Stunde und 30 Minuten. "h" steht für Stunden, "m" für Minuten und "ms" für Millisekunden.
- <channel>: Dieser Kanal wird gesperrt. Falls keiner angegeben wird, ist es der Kanal, in dem der Befehl genutzt wird.

``/moderaton mute [user] [time] <reason>``
----------------------
Gibt einem Nutzer einen Timeout mit der eingebauten Funktion von Discord. Der Bot und du benötigen die rechte, Nutzer zu timeouten.

- [user]: Dieser Nutzer wird getimeoutet.
- [time]: Für diese Zeit wird der Nutzer getimeoutet. Man kann dafür d, h, m und ms nutzen. "d" sind die Tage, "h" die Stunden, "m" die Minuten und "ms" die Millisekunden. Man kann Nutzer maximal für 23 Tage timeouten.
- <reason>: Gebe einen Grund an, warum der Nutzer getimoutet wird.

``/mderation nickname set [user] [nickname]``
------------------------
Setzt den Spitznamen eines Nutzers. Du und der Bot benötigen die Rechte, Spitznamen zu verwalten.

- [user]: Von diesem Nutzuer wird der Spitzname verändert.
- [nickname]: Gebe den neuen Spitznamen an.

``/moderation nickname reset [user]``
------------------------
Setze den Spitznamen eines Nutzers zurück. Du und der Bot benötigen die Rechte, Spitznamen zu verwalten.

- [user]: Von diesem Nutzer wird der Spitzname zurückgesetzt


``/moderation unban [user]``
------------------------
Entbanne einen Nutzer mit diesem Befehl. Du und der Bot benötigen die Rechte, Nutzer zu bannen. 

- [user]: Dieser Nutzer wird entbannt. Gebe hier bitte die ID des Nutzers an, der entbannt werden soll.

``/moderation unlock [channel]``
------------------------
Entsperre einen Kanal von deinem Server. Du und der Bot benötigen die Rechte, Kanäle zu verwalten.

- [channel]: Dieser Kanal wird entsperrt.

Fehler
================
Man muss beachten, dass es je nach Befehl viele Fehler geben kann. Es gibt aber für viele Fehler eine eigene Fehlermeldung. Falls du aber Hilfe benötigst, kannst du dem Support Server beitreten: https://discord.gg/BQumAujuvk
