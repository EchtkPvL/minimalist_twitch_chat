# Minimalist Twitch chat
Very simple twitch chat is read only. It displays time, username in colour and the message. The latest message is on top allways. The number of messages displayed is limited to 200 messages. The chat also supports emotes (currently only from Twitch).

## Settings
This chat can be configured through URL parameters.

### Channel
`channel=<NAME>`

| Parameter | `channel` |
| --- | --- |
| Expectation | Username of Twitch channel |
| Default | `jvpeek` |
| Warning | Programm will **not** throw an error on wrong input |

### Max messages
`maxlines=<NUMBER>`

| Parameter | `maxlines` |
| --- | --- |
| Expectation | Max messages to be shown |
| Default  | `200` |

### Time difference
`addhours=<NUMBER>`

| Parameter | `addhours` |
| --- | --- |
| Expectation | Hours |
| Default | `0` |
| Note | Use this for timezone correction. |

### Example
`https://echtkpvl.github.io/minimalist_twitch_chat/?channel=echtkpvl`

---
## Credits
[ProjektionTV](https://twitch.tv/projektiontv)

https://github.com/ProjektionTV-Codequatsch/minimalist_twitch_chat
