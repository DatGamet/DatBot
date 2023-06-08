*******
Logging
*******

Informationen
===========
Logging ist zurzeit für Sprachkanäle, Bots, Emojis, Stickers und Kanäle verfügbar. Mehr wird in der Zukunft hinzugefügt. Du benötigst die Rechte, den Server zu verwalten, um die Logs zu verwalten.
Wenn eine Änderung geschieht, loggt DatBot diese mit einem Webhook in einen Kanal.
Leave Logs sind Logs für Nutzer, die den Server verlassen.
Welcome Logs sind Logs für Nutzer, die dem Server beitreten.
Voicelogs sind Logs, die tracken, wenn jemand einem Sprachkanal beitritt, ändert oder verlässt.

Befehle
=======


``/leave channel [channel]``
------------------------
Setze den Kanal für die Leave-Logs. DatBot muss den Kanal sehen können, dort Nachricht senden und Links einbetten können.

- [channel]: In diesem Kanal werden die Logs gesendet. 

``/leave message [message]``
------------------------
Diese Nachricht wird angezeigt, wenn ein Nutzer verlässt.

- [message]: Gebe eine Nachricht an, die gesendet wird, wenn ein Nutzer verlässt.


``/leave test``
------------------------
Testet das System und checkt, ob alles funktioniert. Häufige Fehler kann man damit finden.

``/leave settings``
------------------------
Zeigt die aktuellen Einstellungen der Leave Logs an.

``/leave toggle``
------------------------
Aktiviert oder deaktiviert die Leave-Logs. 

``/leave mention [type] <role>``
------------------------
Setzt einen Ping, der gesendet wird, wenn jemand verlässt. Dieser Ping wird mit der Nachricht gesendet. 

- Die 1. Option erwähnt den Nutzer, der verlassen hat.
- Die 2. Option erwähnt eine Rolle. Die Rolle muss aber auch angegeben werden. Dies kann man machen, indem man eine Rolle im <role>-Argument angibt.
- Mit der 2. Option wird niemand erwähnt.

``/logs channel [channel]``
------------------------
Setzt den Kanal für Emoji, Sticker, Kanal und Bot Logs. Der Bot benötigt die Rechte, in diesem Kanal Webhooks zu verwalten.

- [channel]: In diesem Kanal werden die Logs gesendet.

``/logs toggle``
------------------------
Aktiviert oder deaktiviert die Logs.

``/voicelog channel [channel]``
------------------------
Setze den Kanal für die Voicelogs. DatBot muss den Kanal sehen können, dort Nachricht senden und Links einbetten können.

- [channel]: In diesem Kanal werden die Logs gesendet. 

``/voicelog test``
------------------------
Testet das System und checkt, ob alles funktioniert. Häufige Fehler kann man damit finden.

``/voicelog settings``
------------------------
Zeigt die aktuellen Einstellungen der Voicelogs an.

``/voicelog toggle``
------------------------
Aktiviert oder deaktiviert die Voicelogs. 

``/welcome channel [channel]``
------------------------
Setze den Kanal für die Welcome-Logs. DatBot muss den Kanal sehen können, dort Nachricht senden und Links einbetten können.

- [channel]: In diesem Kanal werden die Logs gesendet. 

``/welcome message [message]``
------------------------
Diese Nachricht wird angezeigt, wenn ein Nutzer beitritt.

- [message]: Gebe eine Nachricht an, die gesendet wird, wenn ein Nutzer beitritt.


``/welcome test``
------------------------
Testet das System und checkt, ob alles funktioniert. Häufige Fehler kann man damit finden.

``/welcome settings``
------------------------
Zeigt die aktuellen Einstellungen der Welcome Logs an.

``/welcome toggle``
------------------------
Aktiviert oder deaktiviert die Welcome-Logs. 

``/welcome mention [type] <role>``
------------------------
Setzt einen Ping, der gesendet wird, wenn jemand beitritt. Dieser Ping wird mit der Nachricht gesendet. 

- Die 1. Option erwähnt den Nutzer, der beigetreten ist.
- Die 2. Option erwähnt eine Rolle. Die Rolle muss aber auch angegeben werden. Dies kann man machen, indem man eine Rolle im <role>-Argument angibt.
- Mit der 2. Option wird niemand erwähnt.

Fehler
=========

- Der Bot benötigt für die Logs die Rechte, Webhooks zu verwalten, den Kanal zu sehen, Links einzubetten und Nachrichten zu senden.
- Die Logs könnten deaktiviert sein. Aktiviere diese mit dem jeweiligen ``toggle`` Befehl.

Falls nichts geholfen hat kannst du dem Support Server beitreten: https://discord.gg/BQumAujuvk
