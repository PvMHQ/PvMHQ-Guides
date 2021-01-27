# PVM Style Guide
This document details many stylistic aspects that all PvM guides should follow.

If submitting a write up, please follow the guidelines in this channel.

These guidelines do not cover every situation, and will be amended as necessary.
Please bring up any concerns that are not covered by these guidelines.  
- [General](#general)
- [Bot Specific Formatting](#bot-specific-formatting)
- [Presets](#presets)
- [Table of Contents](#table-of-contents)
​
## General
[general]: #general
- Utilise UK spelling and style (armour over armor).
- Dates will be written in the format: YYYY/MM/DD.
- Every channel should have it's channel topic containing the correctly captialised title ("cox" channel would have "Chambers of Xeric" as it's topic).
- It is preferred that videos are hosted on the PvMHQ Youtube Channel.
- Images should be attached to messages, no links to images in guides. Imgur is the preferred hosting platform.
- Video links with embeds should be placed in their own message. This is not necessary if the embed is disabled.
- If a empty line is required to split sections at a message boundary, place the empty line at the end of the first message.
  - If the first message ends with an attachment or video embed, place an entirely empty message between the messages.
- Links should be formatted as such: `Link text - <https://...>`
  - Example: Oldschool RuneScape Wiki - https://oldschool.runescape.wiki/
  - Surround links with `<` and `>` to prevent embeds from appearing.
- Where possible, the first message of a guide should be an image that best represents the guide.
​
Utilise block quotes (> text) for sections
- Utilise ⬥ for subsections 
  - Utilise four spaces, followed by • for subsubsections titles.
    - Utilise eight spaces, followed by • for sublists.
  - Always use spaces, and avoid tabs for indentation.
  - Bold and underline subsections and subsubsection when they act as titles

## Bot Specific Formatting
[bot-specific-formatting]: #bot-specific-formatting
​Seperate messages using a `.`  
```
Message 1 
.
Message 2
```

A tag (for use in message linking) can be added using `.tag:tag_name`.  
```
Tagged Message
.tag:taggedmessage
```

To link to a previous message use `$linkmsg_tagname$`.  
Example to link to the message in the previous block:
```
A message link: $linkmsg_taggedmessage$
```

## Presets
[presets]: #presets
- Rune Pouches in presets should match colours of pouches in `#armour-and-weapons`.
- Switch weapons should use the same switches in `#perks` (e.g. cywir represents planted feet).
​
​
## Table of Contents
[table-of-contents]: #table-of-contents
- The table of contents should be at the end of the guide.
- The table of contents should be in a section titled "Table of Contents".
- The table of contents should be pinned in the channel.
- The messages linked in the table of contents should only link to the title of the section, not the entire message.  
```
> **Presets**
.tag:presets
/* Rest of the section */
```
Not 
```
> **Presets**
/* Rest of the section */
.tag:presets
```

A fully created table of contents would look like this in source:
```
> __**Table of Contents**__
⬥ **Introduction** - $linkmsg_introduction$
⬥ **General** - $linkmsg_general$
⬥ **Sections** - $linkmsg_sections$
⬥ **Table of Contents (formatting)** - $linkmsg_tableofcontents$
```
