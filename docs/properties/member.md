---
description: Available member data.
---

# Member

* `bannable` - Whether the member is bannable by the bot or not. | boolean
* `boostingSinceTimestamp` - How long this member has been boosting. | integer
* `displayColor` - The member's display color \(the color-hex of the user's top-most role\). | string 
* `displayName` - The member's display name. Returns their nickname, or username if no nickname is set. | string
* `isBanned` - Whether the user has been banned from the guild. | boolean
* `isBoosting` - Whether this member is boosting or not. | ?boolean
* `isDeafened` - Whether this member is deafened or not. Applies to both self and server deafened.  | ?boolean
* `isMuted` - Whether this member is muted or not. Applies to both self and server mutes. | ?boolean 
* `isPartial` - Whether this member is partial or not. | boolean
* `isPending` - Whether this member is pending membership screening or not. | boolean
* `isSelfDeafened` - Whether this member is self-defeaned or not. | ?boolean
* `isSelfMuted` - Whether this member is self muted or not. | ?boolean
* `isServerDeafened` - Whether this member is server-defeaned or not. | ?boolean
* `isServerMuted` - Whether this member is server-muted or not. | ?boolean
* `isStreaming` - Whether this member is streaming via GoLive or not. | ?boolean
* `joinedTimestamp` - The timestamp when this member joined the guild. | integer
* `joinPosition` - The member's join position. | ?integer 
* `kickable` - Whether this member is kickable by the bot or not. | boolean
* `manageable` - Whether this member is manageable by the bot or not. | boolean
* `nickname` - The member's nickname. | ?string
* `permissions(permissionFilter)` - The user's permissions. | ?any
* `roles(roleProperty)` - The member's roles. | ?any 
* `voiceChannelID` - The ID of the voice channel this member is in. | ?string
