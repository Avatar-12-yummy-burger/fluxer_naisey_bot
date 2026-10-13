# NaiseyBot Privacy Policy

*Last updated: Oct 13, 2026*

NaiseyBot is a Fluxer bot with commands like hugging, cuddling, petting and some Deltarune related commands. This policy explains what little data it does collect, why, and how long it sticks around.

## Data We Collect

NaiseyBot stores a small amount of data in a database to make a couple of features work:

- **Server ID and custom prefix** — if a server admin sets a custom command prefix, we store that server's ID alongside the prefix they chose.
- **Hug-tracking records** — to detect when a hug is returned, we temporarily store the server ID, the target user's ID, the hugger's user ID, and the timestamp of the most recent hug between that pair in that server.

Server IDs and user IDs are just numbers Fluxer assigns to every server and account — they are not usernames, display names, or any part of your profile.

## Why We Collect It

- **Prefixes** let each server customize the character used to trigger commands, instead of everyone being stuck with the default.
- **Hug-tracking** lets the bot notice when you hug someone back, so it can send a special "mutual hug" message instead of the usual random one.

## Data Retention

- **Prefix data** is kept until a server admin changes it again, or until the bot is removed from that server.
- **Hug-tracking data** automatically expires — if a hug isn't returned within 1 day, the record is deleted the next time anyone in that server uses the hug command. It never accumulates indefinitely.

## Data We Do Not Collect

NaiseyBot does **not** store:

- Message content
- Usernames or display names
- Avatars or profile pictures (fetched live each time a command needs one, never saved)
- Direct messages
- Voice data
- Any personal information beyond the numeric IDs described above

## Third-Party Sharing

Your data is never sold, shared, or handed off to third parties. It's used only internally, to run the features described above.

## Your Rights

- A server admin can reset the server's prefix at any time with the prefix-set command.
- Removing the bot from a server stops all further data collection for that server.
- You can contact the developer (see Contact below) to request your hug-tracking data be deleted early, before it expires on its own.

## Hosting and Security

NaiseyBot and its database run on third-party hosting providers. Reasonable security practices are used to protect stored data, though as with any online service, no method of storage is 100% guaranteed secure.

## Changes to This Policy

This policy may be updated as the bot's features change. The "last updated" date at the top will always reflect the most recent revision.

## Contact

Questions or data deletion requests can be sent via the bot's GitHub repository: [github.com/BNaise/fluxer\_naisey\_bot](https://github.com/BNaise/fluxer_naisey_bot).
