# osu!preach

osu!preach is a script that allows you to perform fast preaching to the chat.

## How to use

- Have `osupreach.txt` exists on your AdiIRC/mIRC data folder. (Hint: Use `$mircdir` or $adiircdir` to get this path)
- Use the following format (specified below) for the `osupreach.txt` content.

## Commands

### /osupreach

*Aliases: `/osup`*

```
USAGE: /osupreach <keyword>[<number>]

- keyword, any single word
- number, 1-index
```

Quickly send your chat snippet to the respective channel.

**NOTE:** Only usable on Channel/Query (Private Message) window, you can use it somewhere else to test your result.

### /osupreachrefresh

Refreshes the preach table.

**NOTE:** This requires the `osupreach.txt` file first!

## About osupreach.txt

This is an important file where you put the preach lists.

Here's the following format of the `osupreach.txt`

`<word>:<content>`
Each line only and only consists of a word, that is followed directly by a colon (that acts as separator).

### File Example
```
score:You can gain a proper score by practicing the same spot or different songs!
combo:Try to make a lot of perfect runs, so you can practice your nervous control.
```

## Disclaimer

I have tested, but I'm just using that on moderation. I'm just trying to help the community after all.