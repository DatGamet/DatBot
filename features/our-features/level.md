# 🆙 Level

### How does it work?

* A message is evaluated every 60 seconds. This message receives between 1 and 25 XP.
* You cannot change ranks or XP.
* You can add rewards (level roles

### Commands

* `/level channel <channel`
  * The level-up message is sent in this channel.
  * Argument \<channel>
    * If no channel is specified, the level-up channel is reset. In this case, the level-up message is sent in the channel in which the user's message is sent.
    * If a channel is specified, the level-up messages are sent in this channel.
* `/level ignore channel [channel]`
  * Messages will not get XP in these channels.
  * Argument \[channel]
    * No more XP will be awarded in this channel.
* `/level ignore list`
  * This command returns a list of ignored channels.
* `/level ignore remove [channel]`
  * Remove an ignored channel.
  * Argument \[channel]
    * Users can collect XP again in this channel.
* `/level leaderboard`
  * See the users with the most XP on the server. 10 users are displayed per page, but you can switch between the pages.
* `/level message`
  * Customize the level-up message.
* `/level noxprole <role>`
  * Wenn ein Nutzer diese Rolle besitzt, wird er kein XP bekommen. Setze die Rolle mit diesem Befehl.
  * Argument \<role>
    * If a role has been specified, the No-XP role is set for this role.
    * If no role has been specified, the No-XP role is reset.
* `/level rank <user>`
  * See the rank of a user with this command.
  * Argument \<user>
    * The rank is viewed by this user.
    * If no user has been specified, your statistics will be displayed.
* `/level roles add [role] [level]`
  * Add a roll as a reward. When level \[level] is reached, the role \[role] is awarded.
  * Argument \[role]
    * This role is assigned when level \[level] is reached.
  * Argument \[level]
    * When someone reaches this level, the role \[role] is assigned.
* `/level roles deleteall`
  * Remove all level roles. This cannot be undone.
* `/level roles list`
  * This shows you all level roles.
* `/level roles remove [role] [level]`
  * Remove the level role that is assigned at level \[level].
  * Argument \[role]
    * This role is to be removed.
  * Argument \[level]
    * The role is assigned at this level.
* `/level test`
  * If there are problems, use this command. Frequent sources of problems are checked here.
* `/level toggle`
  * Deactivate the level system on the server on which the command is executed.
