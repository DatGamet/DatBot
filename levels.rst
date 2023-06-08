*****
Level
*****

Informationen
====================
Das Levelsystem ist so ausgelegt, dass in 60 Sekunden je eine Nachricht gezählt wird. Somit zählt Spam nicht. Man kann die XP / Levels nicht verändern. Mit jedem Level-Up muss man 1.2 mal mehr XP sammeln, als davor. Um die Rollenbelohnungen zu verwenden muss eine meiner Rollen muss über der Rolle aus der Rollenbelohnung sein und ich benötige die Rechte, Rollen zu verwalten.

Befehle
=======
``/level channel [channel]``
------------------------
In diesem Kanal werden die Levels-Ups gesendet. Du benötigst die Rechte, den Server zu verwalten, um diesen Befehl zu nutzen. Ich muss in diesen Kanal sehen können, dort Nachrichten senden und Links einbetten können.

#. [channel]: In diesem Kanal werden die Levels-Ups gesendet

``/level leaderboard``
------------------------
Zeigt die Bestenliste an. Es wird je nach Level sortiert. Mit den Buttons unten kann man zwischen den Seiten wechseln. Pro Seite werden 10 Datensätze angezeigt. Der Button ganz links bringt dich auf die erste Seite. Der Button rechts zeigt eine Seite weiter links. Der Button in der Mitte stoppt das Menu. Der zweite Button von rechts zeigt eine Seite weiter rechts und der Button ganz rechts zeigt die letzte Seite.

``/level message [message]``
------------------------
Konfiguriere die Level-Up Nachricht. Du benötigst dafür die Rechte, den Server zu verwalten. Dort gibt es auch folgende Variablen:

#. {guild.id} -> The Guild ID
#. {guild.name} -> The guild name
#. {user.name} -> The username
#. {user.id} -> The user ID
#. {user.tag} -> The username & tag
#. {level} -> The new level

#. [message]: Dies ist die Nachrticht, die gesendet wird, wenn jemand ein Level-Up erreicht.

``/level rank [user]``
------------------------
Zeigt den Rang eines Nutzers an. 

#. [user]: Von diesem Nutzer wird der Rang angezeigt

``/level test``
------------------------
Teste, ob alles funktioniert. Typische Fehlerquellen werden dort überprüft.

*****
Level
*****

Informationen
====================
Das Levelsystem ist so ausgelegt, dass in 60 Sekunden je eine Nachricht gezählt wird. Somit zählt Spam nicht. Man kann die XP / Levels nicht verändern. Mit jedem Level-Up muss man 1.2 mal mehr XP sammeln, als davor.

Befehle
=======
``/level channel [channel]``
------------------------
In diesem Kanal werden die Levels-Ups gesendet. Du benötigst die Rechte, den Server zu verwalten, um diesen Befehl zu nutzen. Ich muss in diesen Kanal sehen können, dort Nachrichten senden und Links einbetten können.

#. [channel]: In diesem Kanal werden die Levels-Ups gesendet

``/level leaderboard``
------------------------
Zeigt die Bestenliste an. Es wird je nach Level sortiert. Mit den Buttons unten kann man zwischen den Seiten wechseln. Pro Seite werden 10 Datensätze angezeigt. Der Button ganz links bringt dich auf die erste Seite. Der Button rechts zeigt eine Seite weiter links. Der Button in der Mitte stoppt das Menu. Der zweite Button von rechts zeigt eine Seite weiter rechts und der Button ganz rechts zeigt die letzte Seite.

``/level message [message]``
------------------------
Konfiguriere die Level-Up Nachricht. Du benötigst dafür die Rechte, den Server zu verwalten. Dort gibt es auch folgende Variablen:

#. {guild.id} -> The Guild ID
#. {guild.name} -> The guild name
#. {user.name} -> The username
#. {user.id} -> The user ID
#. {user.tag} -> The username & tag
#. {level} -> The new level

#. [message]: Dies ist die Nachrticht, die gesendet wird, wenn jemand ein Level-Up erreicht.

``/level rank [user]``
------------------------
Zeigt den Rang eines Nutzers an. 

#. [user]: Von diesem Nutzer wird der Rang angezeigt

``/level toggle``
------------------------
Aktiviert oder deaktiviert das Level-System. 

``/level roles add [role] [level]``
------------------------
Fügt eine Rollen-Belohnung hinzu. Du benötigst dafür die Rechte, den Server zu verwalten, um diesen Befehl zu nutzen. 

#. [role]: Diese Rolle ist die Rolle, die vergeben wird, wenn das Level aus dem [level]-Argument erreicht wird.
#. [level]: Bei diesem Level wird die Rolle vergeben

``/level roles list``
------------------------
Zeigt alle Rollenbelohnungen mit dem dazugehörigen Level an. Rollen, die gelöscht sind, werden nicht angezeigt.

``/level roles remove [role] [level]``
------------------------
Entfernt eine Rollen-Belohnung. Du benötigst dafür die Rechte, den Server zu verwalten, um diesen Befehl zu nutzen. 

#. [role]: Die Rolle, die entfernt werden soll.
#. [level]: Bei diesem Level wird die Rolle vergeben

``/level roles deleteall``
------------------------
Löscht alle Rollenbelohnungen. Alternativ kann man auch ``/leves roles toggle`` nutzen. Du benötigst dafür die Rechte, den Server zu verwalten, um diesen Befehl zu nutzen. 

``/level roles toggle``
------------------------
Aktiviert oder deaktiviert die Rollenbelohnungen.  Du benötigst dafür die Rechte, den Server zu verwalten, um diesen Befehl zu nutzen. 

Fehler
==========
Level-Ups & Benachrichtigungen
------------------------
Die Level-Up Benachrichtigungen werden immer gesendet, wenn ein Nutzer ein Level mehr erreicht.

#. Es kann sein, dass der Bot keine Rechte hat, Links einzubetten, Nachrichten zu senden oder den Kanal zu sehen.
#. Es kann sein, dass das Levelsystem deaktiviert ist. Dies kann man mit ``/level toggle`` aktivieren.
#. Es kann sein, dass eine weitere nachricht gesendet werden muss, damit die Nachricht kommt.

Falls nichts geholfen hat kannst du dem Support Server beitreten: https://discord.gg/BQumAujuvk

XP
---------

#. Es kann sein, dass das Levelsystem deaktiviert ist. Dies kann man mit ``/level toggle`` aktivieren.
#. Es kann sein, dass der Bot den Kanal nicht sieht.

Falls nichts geholfen hat kannst du dem Support Server beitreten: https://discord.gg/BQumAujuvk

Rollenbelohnungen
-----------------
Diese werden vergeben, wenn ein Level erreicht wurde.

#. Es kann sein, dass der Bot keine Rechte hat, die Rollen zu verwalten.
#. Es kann sein, dass die Rollenbelohnungen deaktiviert sind. Diese kann man mit ``/level roles toggle`` aktivieren.
#. Es kann sein, dass die Rolle über den Rollen von DatBot steht.
#. Es kann sein, dass DatBot den Nutzer nicht verwalten kann

Falls nichts geholfen hat kannst du dem Support Server beitreten: https://discord.gg/BQumAujuvk
