# ⚙ Moderation

## Commands

### `/moderation ban [user] <notify_about_punishment> <reason> <delete_messages>`

* Permanently bans a user from the server.
* Argument \[user]
  * This user is permanently banned.
* Argument \<notify\_about\_punishment>
  * Decide whether the user should be informed of the ban by private message. There is no mention of who banned the user.
* Argument \<reason>
  * Add a reason that is displayed in the audit log.
* Argument \<delete\_messages>
  * Delete all messages between a certain time period. This must be between 1 second and 7 days. Specify this with s, m, h and d.

### `/moderation banreason [ban] [new_reason]`

* Change the reason for a ban.
* Argument \[ban]
  * Specify the ban here. This option supports autocomplete, so search for the ban by username or enter an ID here.
* Argument \[new\_reason]
  * Enter the new reason here.

### `/moderation clear [number] <user> <channel>`

* Delete a certain number of messages.
* Argument \[number]
  * Enter the number of messages to be deleted here.
  * The number must be between 1 and 100.
* Argument \<user>
  * The messages are only deleted by this user.
* Argument \<channel>
  * The messages are deleted in this channel.

### `/moderation kick [user] <reason> <notify_about_punishment>`

* Kick a user from the server.
* Argument \[user]
  * This user will be kicked.
* Argument \<reason>
  * Add a reason that is displayed in the audit log.
* Argument \<notify\_about\_punishment>
  * Decide whether the user should be informed of the kick by private message. There is no mention of who kicked the user.

### `/moderation lock <reason> <channel> <time>`

* Remove the permissions for the role `@everyone` to send messages in the channel .
* Argument \<reason>
  * Add a reason that is displayed in the audit log.
* Argument \<channel>
  * This channel will be locked.
* Argument \<time>
  * Specify how long the channel should be blocked. Enter the time with s, m, h and d.

### `/moderation mute [user] [time] <reason>`

* Timeout a user with the Discord function
* Argument \[user]
  * This user will be timed out.
* Argument \[time]
  * Specify how long the user should be timed. Specify the time with s, m, h and d.
* Argument \<reason>
  * Add a reason that is displayed in the audit log.

### `/moderation nickname reset [user]`

* Reset the nickname of a user.
* Argument \[user]
  * The nickname of this user is reset.

### `/moderation nickname set [user] [nick]`

* Change the nickname of a user.
* Argument \[user]
  * The nickname is changed for this user.
* Argument \[nick]
  * This is the user's new nickname.

### `/moderation unban [user] <reason>`

* Unban a user with their ID.
* Argument \[user]
  * Specify the user to be unbanned
* Argument \<reason>
  * Add a reason that is displayed in the audit log.

### `/moderation unlock <channel>`

* Give the role `@everyone` the authorization to send messages to a channel.
* Argument \<channel>
  * Specify the Discord channel here.

### `/moderation unmute [user]`

* Remove the timeout of a user.
* Argument \[user]
  * The timeout is removed from this user.
