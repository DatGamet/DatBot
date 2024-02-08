# 🌍 Emoji quiz & Flag quiz

{% hint style="info" %}
The emoji quiz and flag quiz work very similarly. Many functions and commands will have a very similar structure.
{% endhint %}

### Information

* Skips: If you don't know the flag or the term, you can skip. At the beginning you have 10 skips and you get three per vote.
* Reply: If the answer is incorrect, the message is responded to with a "❌".

### Commands

* `/emojiquiz fix | /flaqquiz fix`
  * If the quiz is currently not working, you can use this command. Common sources of error are examined here.
* `/emojiquiz help | /flaqquiz help`
  * It works like a FAQ, frequently asked questions are answered there.
* `/emojiquiz settings | /flaqquiz settings`
  * Displays the settings of the quiz.
* `/emojiquiz toggle | /flaqquiz toggle`
  * Activates or deactivates the quiz. If the quiz is deactivated, it will not work.
* `/emojiquiz setup [channel] | /flaqquiz setup [channel]`
  * Set up the quiz.
  * Argument \[channel]
    * The quiz is started in this channel.
    * The bot requires the Send Messages, Embed Links and View Channel permissions in this channel
    * When the system is set up for the first time, the system is also activated automatically. If the system is deactivated during setup, this will be mentioned in the interaction response.
* `/emojiquiz vote | /flaqquiz vote`
  * Receive a link (Top.gg) where you can vote.



