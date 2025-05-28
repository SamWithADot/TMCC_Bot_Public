# Currently the bot can do the following thigs:
- Automatically reply to people asking for farms
- Automatically replies to videos from certain channel. It needs more prompts and the prompts need better formating
- Replies in the thread if a tag is added  
- Sends and pins a checklist in a new thread (Advisors+ to edit it)
- Backs up the archive. This is still a WIP

# The bot has the following commands:
  - /Prompt <prompt_name>: This lets you pick from a list of prompts and it will send it in the channel
  - /Edit_checklist: Brings up a button pannel to edit the checklist created in submission channel. (Advisor+)
  - /Sync: syncs commands with discord (Owner)
  - /Backup: Creates a backup of the archive (Owner)
  - /Youtube <querry>: Lets you search youtube, sends back a list of the top 5 filtered results for you to select from
  - /Tag_info <channel_id>: Returns some statistics about the channel (Advisor+)
  - /Output_log <n>: Outputs the last n values from the log file (Moderators)
  - /Restart <update = True>: Updates the bot and restarts it (Owner)
  - /Ping: Outputs the bot's latency alongside other useful statistics (Owner)
  - ?Get_name: Outputs the name of the channel as it would appear in the embed data, only really useful for setting up the auto reply prompt (Owner)
  - /Set_tag: Lets you set the tag of the thread from all of the tags in the forum (Archiver+)
  - /Joke: Sends a joke from the "icanhazdadjoke" api
  - /Reload_config: Reloads config from the database (Owner)
  - /Restart: Restarts the bot (Owner)
  - /Tic_Tac_Toe <opponent>: Play tic tac toe. You can optinally specify a user to challenge them or the bot to play against the computer.

### Any suggestions or ideas are welcome, but keep in mind that it might take some time. Report bugs here instead of pings.
