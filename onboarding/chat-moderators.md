# Chat Moderators
_This document will serve as the entry point to chat moderation in The Odin Project's Discord community for any new Core, Maintainers, and Moderators._

## Purpose of Moderator Role

Moderators are representatives of The Odin Project's community who assist with moderating the official Discord server. Moderators help ensure a welcoming, safe, and inclusive community for as many users as possible.

### Admission and Removal of Role

Moderators, and those wishing to be considered for the Moderator role, are expected to have a history of regular and positive contributions to The Odin Project Discord community. Chat moderators are members of the community that illustrate and personify what it means to create a positive impact by abiding by the rules, extending help to others in regards to the community,  having a willingness to hold both themselves and others accountable within the community, and motivating others to create a positive environment.

Removal of the role is subject to the discretion of the Core team members and may occur for any reason, including but not limited to: violation of the rules, abuse of power, etc.

## Chat Responsibilities and Guidelines

### Take notes of any moderation action
- The Discord server uses [Dyno bot](https://dyno.gg/bot) to aid in automation of certain moderation tasks,
- When you moderate a user, you should add a note on the user in the `#chat-mod-actions` channel explaining the rule they broke and what action was taken (e.g. warned, threaded, etc).
- You can include links to messages in another channel within user notes, if you feel the context of the message is relevant to the note.
- You can check out some of the available [Dyno commands](https://dyno.gg/commands), but the ones you will most likely be using most often are `?notes` and `?note`.

### Maintain, follow, and enforce rules

- As a moderator, you will be expected to **adhere to** and **uphold** the rules as detailed and maintained in the `#rules` channel in the Discord at all times. 
- **Change inappropriate nicknames**
    - User nicknames _should_ adhere to our rules.
    - Overtly hateful, racist, or sexual names are not tolerated.
    - If possible, change the user's name to something more appropriate and let the user know of the name change in a private thread
    - Abuse of this permission will not be tolerated.
- **Delete applicable messages from all channels and threads.**
    - Use discretion.
    - Screenshot all messages to be deleted and post them in the `#chat-mod-actions` channel.
    - Immediately delete content that breaks rules regarding hate speech, racism, and pornography. 
    - Use discretion within reason regarding "bad etiquette".
    - Malicious messages should be deleted.
        - e.g. If somebody is attempting to get somebody to run `rm -rf /`.
        - Somebody is looking for help with "phishing" or other illegal activities.
        - Potentially warrants a `loki?` before continuing the user's participation in the community.
- **Create private threads when moderating individuals**
    - Rather than publicly call an individual out, prefer to use a private thread to let them know of a rule they broke and to remind them of the rules/to refrain from breaking the rule again.
    - Private threads can be more advantageous as it allows you to speak one-on-one with the user, and it prevents other users trying to chime in or other conversations from burying your message.
    - You can also use private threads to have a deeper discussion regarding any continuing problematic behavior of theirs or to request the user change their inappropriate profile picture.
    - If you need to speak to several people at once, such as when multiple people are dogpiling or having an off topic conversation, you should send a blanket message reminding users of the rules or asking users to stop (without calling out anyone specific).
- **Temporarily mute users to prevent situations from blowing up**
    - Use Dyno bot to temporarily mute a user, being sure to include a time limit and a reason.
    - Some examples of when you should temporarily mute a user is if they are getting visibily frustrated and taking it out on other users, there is some sort of conflict occurring and you need to shut it down immediately before it gets worse, etc.
- **Give users the `NOBOT` role for spamming of the odin-bot commands**
    - Users with this role will result in the `odin-bot` ignoring any bot commands made by that user.
    - Examples of what constitutes spamming of the bot commands include giving a user multiple points in the span of a few minutes, running random commands in random channels after being told to use the `#bot-spam-playground`, etc. 
- **Give users the `loki?` role for constant rule-breaking and "stern" warnings**
    - The `loki?` role removes a user's permissions such that they can only view the `#please-wait`, `#please-wait-2`, and `#rules` channels.
    - We apply this role to users who we wish to have a private conversation with, as the next step up from private threads, so that they cannot interact with the rest of the server and potentially continue breaking the rules.
    - The `#please-wait` and `#please-wait-2` channels are public to other members of the team for transparency and is where engagements regarding the rules or general chat conduct should occur, as opposed to direct messages.
    - Be mindful that the chat history is not preserved from the user perspective. If a user goes offline, when they return the chat history will be removed from their perspective, potentially requiring us to screenshot prior history.
    - When you have given a user the `loki?` role, it is **your** responsibility to restore their privilages to the chat.
- **Kick users from the discord**
    - Primarily, due to the inability to adhere to the rules despite being given the `loki?` role and given multiple warnings.
    - Users within the community should be met with a warning before kicking is even considered, to give them a chance to correct their behavior.
    - Exercise 'common sense' discretion when deciding whether to exercise this power.
    - Kick clear phishers and spammers immediately, with the exception of Nitro or similar spam (see the Banning section further below).
    - Rules are meant to be relaxed, with the exception of **overt** usage of hate speech, racism, or pornography. 

### Banning
- Members that are Nitro spammers (or similarly malicious spammers) should have the message screenshotted and posted in the `#chat-mod-actions` channel before banning.
- Unless it is for Nitro spam or another egregious act (hate speech, racism, pornography, etc), you should consult with Maintainers and Core before banning a user.
- Always ban users with Dyno bot's ban commands, as this keeps a history of who was banned, who initiated the ban, and what the reason of the ban was for.
- Dyno bot offers the ability to temporary ban a user for a set period of time, at which point they will automatically be unbanned. Similar to a permanent ban, do not abuse this or temporary ban anyone without consulting with Maintainers and Core.
