# Chat Reports
Chat reports are a new addition added to Minecraft since 1.19.1, intended in mind for users and servers of all kinds. Chat Reports are optional for dedicated server owners (SMP runners, anarchy servers, etc) and **always on** for Realms.

## What are chat reports?

Chat reports is a message reporting system added by Mojang upon one of the pre-release snapshots of 1.19.1. In the version prior (1.19.0), Mojang added message signatures to messages, which had to be signed in order to chat.

In 1.19, this system was further expanded, requiring users to sign messages that could be reported.

## Why is this bad?
<!-- TODO: rework this? -->
Upon the release of 1.19.1, an exploit called Gaslight came out. The exploit manipulated how messages can be reported and resulted in complications, such as false bans for answering questions that were manipulated on report.

For example, if you said yes to "Do you like fruit?", the user of the exploit could make it sound like you answered a more sinister question.

The exploit seems to not be present on 1.20+, but by the time it came out, the exploit was already publicized and the damage was done. Since then, some players have taken a very solid stance on their feelings about this feature, and various mods made to make Reporting impossible have been created, including No Chat Reports and [FreedomChat](https://modrinth.com/plugin/freedomchat).

## What should I do?
If you don't really care, nothing will probably change; assuming you do not swear, do not call people names, you play on 1.20 and higher & not actively breaking Mojang's Community Standards, you should be okay. Keep in mind that some users are very strong about this topic, especially since it's a feature that locks some out of playing a game online that they paid for.

If you do care and might be worrying, what you do here will depend. If you play with friends over a dedicated server (i.e: Aternos, a paid dedicated server, self-hosted server), you can install [FreedomChat](https://modrinth.com/plugin/freedomchat) (Bukkit and forks) or [No Chat Reports](https://modrinth.com/mod/no-chat-reports) (Forge, Fabric, Quilt & NeoForge).

If you do not have have access to the server being hosted, all you can do is install [No Chat Reports](https://modrinth.com/mod/no-chat-reports) and hope for the best. If you are still worried and want to stay extra safe, either you'll have to avoid servers that enforce Chat Reports or you will have to kind whoever manages the server to install either mod on the server.

**If you are on 1.19.0 and below**, you are unaffected. If you're on 1.19.1 - 1.19.4 and are willing to be a little malicious, [Guardian](https://github.com/nodusclient/guardian) can prevent you from being reported, although it is against the server's will and may not be allowed by some servers.  
Additionally, some may not recommend you use Guardian, due to its sheer forceful implementation.

## How can I tell if Chat Reports are on?
There are a couple of ways. If you have No Chat Reports on and enabled and you have sent a message, there is a status indicator in the bottom right you can hover over. It might look like a shield for Fabulously Optimized users, or it might just be a little icon for most users.

If you have NCR installed, you will also usually get warnings if the server enforces signing, this is usually a popup asking you to allow signing. That is your last warning before you send messages that can potentially be reported.

**Note that the allow signing prompt is not always a sign that chat reports are possible**. On some servers, such as FishOnMC, they convert all messages to system messages anyway.


## Further Reading
<!-- TODO: find more neutral resources -->

- [Chat Reporting Helper](https://modrinth.com/resourcepack/chat-reporting-helper) (A resource pack for 1.19.4+ that replaces No Chat Reports icons and some in-game text with more clearer information on how Chat Reporting works. Good if you are unsure what the harms are, or why this all matters to people.)