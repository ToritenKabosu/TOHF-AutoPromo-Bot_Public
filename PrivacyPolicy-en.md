# Privacy Policy
This Privacy Policy explains how **TOHF-AutoPromo-Bot** ("Bot"), which operates in conjunction with the Among Us mod [**TownOfHost-Fun**](https://github.com/ToritenKabosu/TownOfHost-Fun) ("TOH-F"), collects, manages, and uses user information.

## 1. Information Collected, Purpose of Use, and Collection Method

To provide its services, the Bot automatically collects or stores the following information, either from user input or during normal operation.

### Discord-related Information

- **Discord server IDs where the Bot is installed:** Used to send messages.
- **Configured room promotion channel IDs:** Used to send room promotion messages.
- **Promotion message IDs:** Used to edit or delete promotion messages.
- **User IDs of users requesting end-of-game mentions:** Used to send mentions when a game ends.

### Among Us-related Information

- **Friend Code:** Used to identify players and associate game accounts with the Bot.
- **Room Code (Room ID) and Host Name:** Used to identify active rooms and display their status on Discord.
- **Current player count, maximum player count, game status, and enabled role counts:** Used to synchronize and display room information on Discord.

### Authentication and Bot Configuration Information

- **API keys and temporary tokens (including timestamps):** Used for secure communication and authentication between the game and the Bot.
- **Language settings:** Used to display messages in the appropriate language for each Discord server.

### Other Information That May Be Collected

- **Anonymized IP addresses:** When an unauthorized request is received, the IP address is anonymized using HMAC before being recorded in logs so that the original IP address cannot be readily identified.

## 2. Data Retention and Deletion

- Temporary tokens and other time-limited data are automatically updated or deleted based on their timestamps.
- When the Bot is removed from a Discord server (including being kicked or banned), Discord-related data associated with that server is automatically deleted from the database.
- If operation of the Bot is discontinued or stored data is no longer required, the developer will make reasonable efforts to delete the stored data.

Users may delete their own API key by using the designated Bot command. *(Currently, API keys are the only user-managed data that can be deleted manually.)*

A list of available commands can be viewed using the `/help` command.

## 3. Disclosure to Third Parties
Personal data collected by the Bot will not be disclosed or provided to third parties except in the following circumstances:

- When the user has given consent.
- When disclosure is required by applicable laws or legal procedures.
- When handling by cloud service providers or other service providers is necessary to the extent required for operating and maintaining the Bot.

## 4. Contact
If you have any questions regarding this Privacy Policy, please contact us through the support server or via Discord DM (`toritenkabosu`).
