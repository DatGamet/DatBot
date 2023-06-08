*******
Sicherheit
*******

Informationen
================
DatBot kann deinen Server sicherer machen. Mit einer Joingate wirst du vor Konten gewarnt, die gefährlich sein könnten. Die Joingate scannt Accounts, die dem Server beitreten und checkt diese. Wenn etwas auffällig ist, wird man benachrichtigt.

Befehle
================
``/security suspicious_accounts``
------------------------
Mit diesem Befehl kannst du deinen Server auf Konten überprüfen, die gefährlich sein könnten. Bedenke aber, dass die Konten nicht immer gefährlich sein müssen. Du benötigst die Rechte, den Server zu verwalten, um diesen Befehl zu nutzen.

``/security joingate channel [channel]``
------------------------
In diesen Kanal werden die Joingate-Benachrichtigungen gesendet. Du benötigst die Rechte, den Server zu verwalten, um diesen Befehl zu nutzen. DatBot muss in diesem Kanal Webhooks verwalten können.

#. [channel}: In diesen Kanal werden die Joingate-Benachrichtigungen gesendet

``/security joingate minage [days]``
------------------------
Setze ein Mindestalter eines Kontos fest. Wenn dieses Mindestalter über dem Kontoalter ist, quasi das Konto zu jung ist, wird eine Benachrichtigung gesendet. 

#. Die Anzahl an Tagen, wie alt das Konto sein soll.

``/security joingate toggle``
------------------------
Aktiviere oder deaktiviere das System. Wenn es deaktiviert ist, wird man nicht benachrichtigt.

Fehler
================
Auch hier können Fehler passieren:

#.  Es kann sein, dass das System deaktiviert ist. Nutze dafür ``/security joingate toggle``.
#. Wenn der Bot keine Webhooks verwalten kann, funktioniert das System auch nicht.

Wenn alles davon nicht geholfen hat, kann man den Support hier kontaktieren: https://discord.gg/BQumAujuvk
