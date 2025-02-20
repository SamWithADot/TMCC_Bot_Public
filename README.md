# Currently the bot can do the following thigs:
- Automatically reply to people asking for farms. This is still a WIP
- Automatically replies to videos from certain channel. It needs more prompts and the prompts need better formating
- Replies in the thread if a tag is added  
- Sends and pins a checklist in a new thread (Advisors+ to edit it)
- Backs up the archive. This is still a WIP

# The bot has the following commands:
  - /Prompt: This lets you pick from a list of prompts and it will send it in the channel
  - /Edit_checklist: Brings up a button pannel to edit the checklist created in submission channel. (Advisor+)
  - /Sync: syncs commands with discord (Owner only)
  - /Backup: Creates a backup of the archive (Owner only)
  - /Youtube: Lets you search youtube, sends back a list of the top 5 filtered results for you to select from
  - /Tag_info: Returns some statistics about the channel (Advisor+)

# Rough to do list:
- Bot posts all the archival messages so any of the archivers can edit them. Makes it easier to move posts around too.
- A website which has all of the archived posts from the discord server. 
- Have a LLM check posts against the guideline when a new submission is created
- Simple querry recognition for #ask-for-help (eg: why is my tnt not duping, is litematica updated)
- Add an options to configure aliases, variables, copy pastes etc. Basically some commands to interface with the DB.
- Better tag managment system
  - Adding a command to set the tag (eg /tag accept removes all tags except the accept tag)
  - Automatically remove the old tag when a new one is added. (eg remove pending when accepted is added)

# Other Potential Projects:
- Using a pre trained LLM to transalte videos

### Any suggestions or ideas are welcome, but keep in mind that it might take some time. Report bugs here instead of pings.
