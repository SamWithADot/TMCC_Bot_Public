# Currently the bot can do the following thigs:
- Automatically reply to people asking for farms. This is still a WIP
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

# Rough to do list:
- Bot posts all the archival messages so any of the archivers can edit them. Makes it easier to move posts around too.
- A website which has all of the archived posts from the discord server. 
- Have a LLM check posts against the guideline when a new submission is created
- Simple querry recognition for #ask-for-help (eg: why is my tnt not duping, is litematica updated)
- Add an options to configure aliases, variables, copy pastes etc. Basically some commands to interface with the DB.
- Add a command to set the tag (eg /tag accept removes all tags except the accept tag)
- Have /prompt reply whatever the user running the command was replying to

# Other Potential Projects:
- Using a pre trained LLM to transalte videos

### Any suggestions or ideas are welcome, but keep in mind that it might take some time. Report bugs here instead of pings.
