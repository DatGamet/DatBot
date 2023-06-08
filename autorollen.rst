*******
Autorollen
*******

Informationen
================
Autorollen sind Rollen, die einem Nutzer hinzugefügt wird, wenn dieser einem Server beitritt. Bots werden dabei nicht beachtet. Das Limit liegt zurzeit bei 15. 
Um diese Befehle zu nutzen, benötigt man die Rechte, Rollen zu verwalten.

Befehle
================
``/autorole add``
------------------------
Mit ``/autorole add``fügt man eine Autorolle hin zu. Diese wird ab dann automatisch vergeben. Der Bot muss dafür über der Rolle sein und die Rechte besitzen, Rollen zu verwalten. Dies wird auch schon beim hinzufügen abgefragt. ``@everyone`` und  Rollen, die von Bots oder Integrationen verwaltet werden, kann man nicht hinzufügen.
------------------------
``/autorole list``
------------------------
Mit ``/autorole list``kann man alle Autorollen anzeigen lassen. Rollen, die gelöscht wurden, werden nicht angezeigt. 
------------------------
``/autorole remove``
------------------------
Mit ``/autorole remove`` kann man eine Autorolle entfernen. Diese wird dann nicht mehr automatisch hinzugefügt. 
------------------------
``/autorole test``
------------------------
Da es viele Fehlerquellen geben kann, kann man mit ``/autorole test`` das System testen. Viele Fehlerquellen werden überprüft und an den Nutzer weitergegeben. 
------------------------
``/autorole toggle``
----------------------
Aktiviert oder deaktiviert das System. Wenn das System deaktiviert ist, werden keine Autorollen mehr vergeben. 
------------------------
``/autorole fix``
------------------------
Das System checkt, ob Rollen Autorollen sind, die gelöscht wurden. Wenn es welche gibt, werden diese entfernt.
------------------------
``/autorole deleteall``
------------------------
Dieser Befehl macht es möglich, alle Autorollen zu löschen. Optional kann man auch ``/autorole toggle``verwenden, um das System zu deaktivieren. 
------------------------

Häufige Fehlerquellen
================
Manchmal funktioniert das System nicht. Dies liegt aber oftmals am Server selber und nicht am Bot.
1. Nutze ``/autorole test`` und ``/autorole fix``. Viele Fehlerquellen werden dort beachtet.
2. Checke die Rollenposition. Eine Rolle von DatBot muss über der Rolle sein, die vergeben werden soll
3. Es kann sein, dass das System deaktiviert ist. Nutze dafür ``/autorole toggle``

Wenn alles davon nicht geholfen hat, kann man den Support hier kontaktieren: https://discord.gg/BQumAujuvk
