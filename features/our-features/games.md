---
description: >-
  Dat Bot supports some games: Fortnite, Clash of Clans, Brawl Stars and
  VALORANT. You can also play TicTacToe with this command.
---

# 🎮 Games

### Possibilities

* Brawl Stars: View information about a player or a club.
* Clash of Clans: View information about a player or a clan. You are also able to link your Clash of Clans account and use the commands more easily: `/link clashofclans`
* Fortnite: View your statistics, get the latest news, take a look at the map or get information about a store item or a creator code.
* VALORANT: View information about an agent, the current version or a map. You can also log in with `/link valorant` to view your match history and competitive rank.



### Connections

* You can find out how to connect your account under [links-connections.md](links-connections.md "mention")



## Commands

### Brawl Stars

* `/games brawlstars club [tag]`
  * See information about a club.
  * Argument \[tag]
    * This is the clan's tag. For example: #2Q0UQ8G0V or 2Q0UQ8G0V.
* `/games brawlstars profile [tag]`
  * See information about a player.
  * Argument \[tag]
    * This is the player's tag. For example: 8VVJYCLUG or #8VVJYCLUG.



### Clash of Clans

* `/games clashofclans clan [tag]`
  * See information about a club.
  * Argument \[tag]
    * This is the clan's tag. For example: #2PVCJULLJ or 2PVCJULLJ.
    * This option supports autocomplete. You can enter the name of the clan and the bot will make suggestions.
* `/games clashofclans profile <tag>`
  * See information about a player.
  * Argument \<tag>
    * If you have linked your account, you do not need to enter this.
    * If you have linked your non-account, you must provide this argument.
    * This is the player's tag. For example: #2LPGL299 or 2LPGL299.



### Fortnite

* `/games fortnite creatorcode [creatorcode]`
  * Receive information about a Creator Code.
  * Argument \[creatorcode]
    * This is the code of the Creator. For example: heystani
* `/games fortnite map [type]`
  * Receive the current map as an image.
  * Argument \[type]:
    * Blank: Does not contain POI names.
    * POI's: Displays the names of the POIs.
* `/games fortnite news`
  * Get the latest Fortnite news.
* `/games fortnite shopitem [search_language] [item]`
  * See information about a cosmetic item.
  * Argument \[search\_language]
    * The item is searched for in this language.&#x20;
    * As of February 10th, 2024, German and English are supported.
  * Argument \[item]
    * Enter the name of the store item here.
    * This option supports autocomplete. You will also receive suggestions here.
* `/games fortnite stats [username]`
  * Get the statistics of a player. This player must have public match statistics activated.
  * Argument \[username]
    * The name of the player. For example: D\_Gamet.



### Tic Tac Toe

* `/games tictactoe [difficulty] <opponent>`
  * Play Tic Tac Toe against an opponent or the AI.
  * Argument \[difficulty]
    * When you play against the AI, you can choose your difficulty level: Easy, Medium, Hard and Unbeatable.
  * Argument \<opponent>
    * Choose an opponent to play Tic Tac Toe against.
    * If you do not select an opponent, you play against the AI.



### Valorant

* `/games valorant agent [agent]`
  * Get information about a specific agent.
  * Argument \[agent]
    * This is the name of the agent.&#x20;
    * This option supports autocomplete. Suggestions are made to you.
* `/games valorant map [map]`
  * Get information about a specific map.
  * Argument \[map]
    * This is the name of the map.
    * &#x20;This option supports autocomplete. Suggestions are made to you.
* \[NEW] `/games valorant matchhistory`
  * The matches in your match history are displayed here. You can select one and get information about this match.
* \[NEW] `/games valorant rank <riot_name>`
  * Get the all-time rank and the current rank of a player.
  * Argument \<riot\_name>
    * If you have linked your account, you do not have to enter this argument.
    * If you have not linked your account, you must provide this argument. For example: DGamet#1687.
* `/games valorant version`
  * See information about the current version of the game.

