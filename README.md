# Currently the bot can do the following thigs:
- Automatically reply to people asking for farms. This is still a WIP
- Auto replies to videos from certain channel. It needs more prompts and the prompts need better formating.
- Replies in the thread if a tag is added  
- Sends and pins a checklist in a new thread (Advisors+)
- Bot backs up archive to a DB

# The following commands:
  - /Prompt <name> This lets you pick from a few prompts and it will send it in the channel
  - /ask_for_help Sends a prompt about how to ask for help, includes a message to move to #ask-for-help if triggered in another channel
  - /sync syncs commands with discord (Owner only)
  - /edit_checklist Brings up a button pannel to edit the checlist creates in submission channel. (Advisor+)      


# Rough to do list:
- Bot posts all the archival messages so any of the archivers can edit them.
- Back up db to mega
- A website which has all of the archived posts from TMCC. The bot will backup any changes to the DB and to the website. The backup to mega will be done at a set time (eg, every week on monday)
- Having a LLM check posts against the guideline when a new submission is created
- Simple querry recognition for #ask-for-help (eg: why is my tnt not duping, is litematica updated)
- Upload notification for certain youtuber (maybe)
- Better formating on mesages, planing to shift most of the bots messages to embeds
- Add an options to configure aliases, variables, copy pastes etc. Basically some commands to interface with the DB.
- Possibly looking into translating videos. It would likely need people to look over it but it should help cut down some of the work atleast.
- A command to count the number of posts that have each tags in submission.
- (possibly) Make ephemeral messages from the bot timeout after a certain time 
- Better tag managment system
  - Adding a command to set the tag (eg /tag accept removes all tags except the accept tag)
  - Automatically remove the old tag when a new one is added. (eg remove pending when accepted is added)

### Any suggestions and ideas are welcome, just keep in mind that it might take time.
