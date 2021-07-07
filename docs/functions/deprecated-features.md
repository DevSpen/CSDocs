# Deprecated Features

Features shown on this page are 'Deprecated'. Meaning, we don't recommend use of it, the feature can be abused/mistreated, or it's simply is unutilized.

> We do not take any responsibility for users/developers who abuse/misuse these functions.

### Deprecated Functions List

#### Mass Functions

Preform several actions at a time.

{% hint style="info" %}
Channel/Role/User IDs should be separated using spaces.

Example: `@massBan[type=ban/unban, 498435934984833 0239493249949494 230234984823833, To cool!]`
{% endhint %}

{% hint style="warning" %}
Use these functions wisely, they could get your bot ratelimited. Be sure to put some limitations in place!
{% endhint %}

* `@massBan[type=ban/unban, userIDs, reason, guildID]`

> Bans multiple users at once. Where 'type' and 'userIDs' are string values, 'reason' and 'guildID' are optional-string values.

* `@massKick[userIDs, reason, guildID]`

> Kicks multiple users at once. Where 'userIDs' is a string value, 'reason' and 'guildID' are optional-string values.

* `@massRole[type=grant/remove, roleID, userIDs, reason, guildID]`

> Grants/removes a role from/to multiple users at once. Where 'type', 'roleID', 'userIDs' are string values, 'reason' and 'guildID' are optional-string values.





