# Chat Moderators
_This document will serve as the entry point to chat moderation in The Odin Project's (TOP) Discord community for any new Core, Maintainers, and Moderators._

## Purpose of Moderator Role

Moderators are representatives of TOP's community who assist with moderating the official Discord server. Moderators help ensure a welcoming, safe, and inclusive community for as many users as possible.

Moderators of the TOP community are *not* maintainers, and should not act as such. Moderators should not attempt to speak on the behalf of the maintainer team regarding plans for the curriculum or the platform outside of Discord. This does not mean moderators cannot provide their own ideas, suggestions, etc, in our `#contribution-suggestions-bugs-discussions` channel or leave general comments/questions on open issues in our repos. There is a fine line between "Would this approach also work?" and "You should update this to follow this approach instead", for example.

### Admission and Removal of Role

Moderators, and those wishing to be considered for the Moderator role, are expected to have a history of regular and positive contributions to The Odin Project Discord community. Chat moderators are members of the community that illustrate and personify what it means to create a positive impact by abiding by the rules, extending help to others in regards to the community,  having a willingness to hold both themselves and others accountable within the community, and motivating others to create a positive environment.

Removal of the role is subject to the discretion of the Core team members and may occur for any reason, including but not limited to: violation of the rules, abuse of power, etc.

## Chat Responsibilities and Guidelines

### Take notes of any moderation action
- The Discord server uses [Dyno bot](https://dyno.gg/bot) to aid in automation of certain moderation tasks. You can check out some of the available [Dyno commands](https://dyno.gg/commands) and what parameters are required/available when using them.
- Before moderating a user, check whether they have any prior notes with Dyno's `?notes` command in the `#chat-mod-actions` channel.
- When you moderate a user, you should add a note on the user with Dyno's `?note` command in the `#chat-mod-actions` channel explaining the rule they broke and what action was taken (e.g. warned, threaded, etc).
- You can include links to messages in another channel within user notes, if you feel the context of the message is relevant to the note.

### Maintain, follow, and enforce rules

- As a moderator, you will be expected to **adhere to** and **uphold** the rules as detailed and maintained in the `#rules` channel in the Discord at all times. 
- **Change inappropriate nicknames**
    - User nicknames must adhere to our rules and cannot be hateful, racist, sexual, etc. in nature, either overtly or vaguely.
    - If possible, change the user's name to something more appropriate and let the user know of the name change in a private thread.
    - Abuse of this permission will not be tolerated.
- **Emphasize intent vs impact for disparaging comments**
    - Users should be reminded that we are an inclusive community, and that their messages will be read by many different types of users.
    - Users should also be reminded that even if their intent wasn't malicious, other users reading their message may be impacted negatively.
        - An example of intent vs impact could be someone using a phrase that is either explicitly or implicitly hateful in nature towards a group of individuals, with the intent of just making a simple joke, but with the impact of that group being targeted by a hateful comment.
- **Delete applicable messages from all channels and threads.**
    - Use discretion whenever deleting a message, and especially regarding "bad etiquette".
    - Screenshot all messages to be deleted and post them in the `#chat-mod-actions` channel **before** deleting them.
    - Immediately delete messages that break rules regarding hate speech, racism, and pornography.
    - Immediately delete messages that require users to download a file, e.g. if a user uploads a JavaScript file instead of a code snippet.
    - Immediately delete messages that are malicious in nature:
        - If somebody is attempting to get somebody to run `rm -rf /`.
        - Somebody is looking for help with "phishing" or other illegal activities.
        - Potentially warrants a `loki?` before continuing the user's participation in the community.
- **Create private threads to avoid arguments**
    - If you moderate someone publicly and it becomes a back and forth discussion/argument, or if you feel it could turn into one, you should immediately create a private thread with the user. 
        - An example of when it's better to use a private thread rather than publicly calling a user out is when instances of individual dogpiling occur.
    - Be sure to mention the user in your initial message when creating the private thread so that they will be able to view and participate in it.
    - Private threads can also be used to just speak one-on-one with the user without bringing attention to them from other users, to prevent other users from trying to chime in, and to avoid other conversations from burying your message.
        - Some examples include having deeper discussion regarding any continuing problematic behavior of theirs, to request the user change their inappropriate profile picture, or to inform a user of the evolved and problematic/toxic meaning of popular phrases/memes they might be using.
    - If you need to speak to several people at once, such as when multiple people are dogpiling or having an off topic conversation, you should send a blanket message reminding users of the rules or asking users to stop (without calling anyone out by name).
        - For example, "This sounds like an interesting discussion, but let's take it to `#odin-offtopic` instead."
        - In cases where multiple users are dogpiling, it can be helpful to afterwards create a separate private thread for each user that was dogpiling to explain why their interaction was considered dogpiling.
- **Temporarily mute users to prevent situations from blowing up**
    - Use Dyno's `mute` command to temporarily mute a user, being sure to include a time limit and a reason in the command.
        - A couple of examples for when you should temporarily mute a user is if they are getting visibily frustrated and taking it out on other users, or there is some sort of conflict occurring and you need to shut it down immediately before it gets worse.
- **Give users the `NOBOT` role for spamming odin-bot commands**
    - Users with this role will result in `odin-bot` ignoring any bot commands made by that user.
        - A couple of examples of what constitutes spamming of the bot commands include giving a user multiple points in the span of a few minutes, or running random commands in random channels after being told to use the `#bot-spam-playground` channel. 
- **Give users the `loki?` role for constant rule-breaking and "stern" warnings**
    - The `loki?` role removes a user's permissions such that they can only view the `#please-wait`, `#please-wait-2`, and `#rules` channels.
    - We apply this role to users who we wish to have a private conversation with, as the next step up from private threads, so that they cannot interact with the rest of the server and potentially continue breaking the rules.
    - The `#please-wait` and `#please-wait-2` channels are public to other members of the team for transparency.
    - `#please-wait-2` should be used moving forward in order to have engagements regarding the rules or general chat conduct. When `loki?`ing a user, you must create a private thread inside this channel like you would any other channel.
    - Be mindful that the chat history is not preserved from the user perspective **in the `#please-wait` channel only**; if a user goes offline, when they return the chat history will be removed from their perspective. The `please-wait-2` channel currently preserves history, which is another reason it should be used moving forward.
    - When you have given a user the `loki?` role, it is **your** responsibility to restore their privilages to the chat.
- **Kick users from the discord**
    - Use Dyno's `kick` command to kick uses who show an inability to adhere to the rules despite being given the `loki?` role and multiple warnings, being sure to include a reason in the command.
    - Users within the community should be met with a warning before kicking is even considered, to give them a chance to correct their behavior.
    - Exercise "common sense" discretion when deciding whether to exercise this power, but do not abuse it.
    - Immediately kick clear phishers and spammers immediately, with the exception of Nitro or similar mass-spam (see the Banning section further below).
    - Rules are meant to be relaxed, with the exception of **overt** usage of hate speech, racism, or pornography. 

### Banning
- Use Dyno's `ban` command to immediately ban Nitro spammers or similar malicious, mass-spammers, **after taking a screenshot** and posting it in the `#chat-mod-actions` channel.
    - For these "mass-spam" users, we don't want their message history to remain intact.
- Unless it is for Nitro spam or another egregious act (hate speech, racism, pornography, etc), you should consult with Maintainers and Core before banning a user.
- Use Dyno's `ban save` command when banning non-Nitro spam users, being sure to include a reason in the command.
    - This command keeps the user's message history intact, and provides a history of who was banned, who initiated the ban, and what the reason of the ban was for.
    - This command can also be used to temporarily ban a user, as a step up from simply kicking them. The default length of temporary bans should be 10 days.
