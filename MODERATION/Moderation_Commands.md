# Moderation Commands

## `?warn`
[Docs](https://wiki.dyno.gg/en/commands/warn)

This is the primary command that will be used to enforce the [Moderation Matrix](https://github.com/TheOdinProject/top-meta/blob/main/Moderation_Matrix.md). This command is both user facing and internally facing. The user will receive a DM with the warning, and we will be able to access a list of warnings a user has received through the [?warnings](https://wiki.dyno.gg/en/commands/warnings) command. Use the below format to warn users. Always include a link to the private thread because while a user may not be able to see it if the thread is in `please-wait`, it is important for us to quickly access these threads.

```
?warn  [user] [reason] [link to private thread] Zaps received: [zaps] Total Zaps: [total zaps]
```

## `?warnings`
[Docs](https://wiki.dyno.gg/en/commands/warning)

This command should be used prior to warning any user so we may check their running total of zaps. Be sure to tally up their total number of zaps and be mindful of the 1 zap per week decay. 

## `?note`
[Docs](https://wiki.dyno.gg/en/commands/note)

This is used to retain notes about particular users, generally for things to look out for that may not be rule breaking, such as general disruption or off-color comments. 

```
?note  [user] [reason]
```

## `?notes`
[Docs](https://wiki.dyno.gg/en/commands/notes)

This command lists all of the running notes about an individual. This should be checked as well prior to privately threading an individual or issuing a warning so we may have clearer context of an individual's participation in the server. 

## `?ban`
[Docs](https://wiki.dyno.gg/en/commands/ban)

This is the most critical moderation command **and must be done CAREFULLY!** We almost always want to preserve chat history for posterity so you must use the `save` option in order to retain it. Timed bans are issued for 10 days and should only be issued when a user has not made severe 10 zap infractions or garnered 10 zaps, but instead is exhibiting minor infractions repeatedly such as help vampirism, mild toxicity (rudeness/frustration let out on helpers, too many off color comments, mild unprofessionalism for a sustained amount of time etc). Otherwise, bans are permanent by default.


```
?ban save [user] (limit) (reason)
```

