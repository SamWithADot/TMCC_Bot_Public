# Currently the bot can do the following thigs:
- Automatically reply to people asking for farms. This is still a WIP
- Auto replies to videos from certain channel. It needs more prompts and the prompts need better formating.
- Replies in the thread if a tag is added  
- Sends and pins a checklist in a new thread (Advisors+)
- Bot backs up archive to a DB. This is still a WIP

# The following commands:
  - /Prompt <name>: This lets you pick from a few prompts and it will send it in the channel
  - /sync: syncs commands with discord (Owner only)
  - /edit_checklist: Brings up a button pannel to edit the checlist creates in submission channel. (Advisor+)      

# Rough to do list:
- Bot posts all the archival messages so any of the archivers can edit them.
- A website which has all of the archived posts from TMCC. 
- Having a LLM check posts against the guideline when a new submission is created
- Simple querry recognition for #ask-for-help (eg: why is my tnt not duping, is litematica updated)
- Add an options to configure aliases, variables, copy pastes etc. Basically some commands to interface with the DB.
- Possibly translating videos. It would still need people to look over it but it should help cut down some of the work atleast. (If it does happen, it will likely be a seperate project)
- A command to count the number of posts that have each tags in submission.
- Better tag managment system
  - Adding a command to set the tag (eg /tag accept removes all tags except the accept tag)
  - Automatically remove the old tag when a new one is added. (eg remove pending when accepted is added)

### Any suggestions or ideas are welcome, but keep in mind that it might take some time.
