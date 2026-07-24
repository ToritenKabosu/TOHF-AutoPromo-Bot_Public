# Privacy Policy

This Privacy Policy establishes how user information is acquired, managed, and utilized in the Discord Bot (hereinafter "the Bot") that operates in conjunction with the Among Us Mod "[TownOfHost-Fun](https://github.com/ToritenKabosu/TownOfHost-Fun)" (hereinafter "TOH-F").

## 1. Information Acquired and Purpose of Use
The Bot acquires and stores the following information automatically or through user input to provide and operate the service.

### Discord-Related Information
- **ID of the server the Bot has joined**: To send messages.
- **ID of the channel designated for posting room codes**: To send messages.
- **ID of the promotional message**: To edit and delete messages.
- **User ID of those requesting mentions**: To mention users.

### Among Us-Related Information
- **Friend Code**: To link the Bot with game accounts, identify registrants, and handle fraudulent/spam activities in the in-game reporting feature (e.g., blacklisting).
- **Room Code (Room ID), Host Name**: To identify running rooms and **post/display their status in designated channels on each Discord server where the Bot is configured**.
- **Current players, max players, game status, and active roles count**: To synchronize and reflect room recruitment status and game settings on Discord.

### In-Game Reporting Feature Information
- **Report category, title, body**: To respond to bug reports, answer questions, improve features, and handle other inquiries.
- **Game version, Mod version**: To investigate bugs and identify operating environments.
*Note: Sent report contents and sender account information are sent to and stored in a dedicated channel on a Discord server managed by the Bot operator, and are used for development and support purposes.*

### Authentication and Restriction Management Information
- **API key and temporary tokens (including timestamps)**: For secure data linkage between the game and the Bot, authentication, and transmission limit (rate limit per API key) management for the in-game reporting feature.
- **Registrant's Discord User ID**: For API key issuance/management and identifying/responding to report data senders.
- **Language settings**: To appropriately switch the display language for each server.

### Handling of IP Addresses
- **IP Address**: Temporarily used in processing memory for access restriction (rate limiting) of room update requests.
- **HMAC-hashed IP Address**: Only when an unauthorized or rejected request occurs, the IP address irreversibly converted via HMAC may be recorded in the operation log (Discord).

## 2. Data Storage and Deletion
- **Data subject to automatic deletion**: Data with expiration dates, such as temporary tokens, are automatically deleted or updated starting from the oldest data based on timestamps.
- **Upon Discord server deletion**: If the Bot is removed from a Discord server (kicked, banned, etc.), configuration data related to that server is sequentially deleted from the database.
- **Retention of report data, etc.**: Data sent via the in-game reporting feature (Friend Code, report content, etc.) is generally not automatically deleted to improve services and prevent fraud.
- **Data deletion requests**: If a user wishes to delete their data, please contact the developer's Discord account (`toritenkabosu`) via DM. When requesting the deletion of report data, you must provide either the **Friend Code used at the time of submission** or **your Discord account**.
- **Upon termination of service**: In the event of the Bot's termination or when storage is no longer necessary, we will strive to appropriately delete the stored data.

## 3. Prohibition of Disclosure and Provision to Third Parties
The acquired information will not be disclosed or provided to third parties as a general rule, except in the following cases:
- With the user's consent.
- When a disclosure request is made based on laws and regulations.
- When handled within the necessary scope by cloud services or other service providers required for the provision and operation of the Bot, to the extent essential for maintaining the Bot's services.

## 4. Inquiries
For inquiries regarding this policy and data deletion requests, please contact the support server or the developer's Discord via DM (`toritenkabosu`).<br/>
*Note: The contents of this policy are subject to change without notice due to the addition of features or changes in operational rules.*

---

# Terms of Service

These Terms of Service (hereinafter "these Terms") define the terms and conditions of use for the Discord Bot provided by the developer (hereinafter "the Bot").<br/>
By adding the Bot to their Discord server or by using the Bot, users are deemed to have agreed to these Terms.<br/>

## 1. Definition of Terms
- **TOH-F**: Refers to the Among Us Mod, "[TownOfHost-Fun](https://github.com/ToritenKabosu/TownOfHost-Fun)".

## 2. Scope of Application
These Terms apply to all users (including server administrators and general users) who use the Bot.

## 3. Terms of Use and Prohibited Acts
Users shall not engage in the following acts when using the Bot:
- Acts that place an excessive load on the Bot's API access, tokens, or systems (such as spamming or DoS attacks).
- Submitting false reports, inappropriate expressions, spam, or excessively repeated submissions in the in-game reporting feature.
- Acts that intentionally exploit vulnerabilities in the Bot's program or attempt unauthorized data manipulation.
- Acts that violate the terms of service of Among Us, TOH-F, and Discord.
- Acts of managing API keys or temporary tokens in a way that may result in their disclosure, lending, transferring, sharing, or leakage to a third party.
- Acts of using the Bot by utilizing another person's API key or temporary token.
- Acts that interfere with the operation of the Bot or the use by other users.
- Other acts that the developer reasonably determines to have a significant adverse effect on the operation of the Bot or other users.

If the developer confirms any use in violation of these Terms, the developer may, without prior notice, invalidate the user's API key, restrict transmissions, suspend the use of the Bot, or take any other necessary measures. In addition, we may not provide individual responses or replies regarding submitted report contents, etc.

## 4. Suspension and Modification of Services
The developer may suspend, modify, or terminate the provision of all or part of the Bot without prior notice to users if the developer determines that any of the following apply:
- When performing maintenance, inspection, or updates of the Bot or linked systems.
- When the provision of the Bot becomes difficult due to force majeure such as power outages, server failures, or communication line accidents.
- When continuous operation of the Bot becomes impossible or difficult due to specification changes in Discord, or specification changes/updates in Among Us/TOH-F.
- Other cases where the developer deems suspension or modification necessary.

## 5. User's Responsibility
Users shall use the Bot at their own responsibility and shall appropriately prepare the necessary environment for using the Bot and manage API keys and other authentication information.

## 6. Disclaimer
**No Warranty**: The Bot is provided "as is," and the developer makes no warranties, express or implied, regarding the completeness, accuracy, certainty, usefulness, or fitness for a particular purpose of the Bot.<br/>
**Disclaimer for Damages**: The developer shall not be liable for any damages (such as Discord server malfunctions, game data inconsistencies, loss of data, mental distress, or other financial losses) incurred by users or third parties arising from the use (or inability to use) the Bot.<br/>
**Impact of Specification Changes**: Even if malfunctions or service suspensions of the Bot occur due to specification changes in Among Us, TOH-F, or Discord, the developer bears no obligation to respond or assume responsibility.

## 7. Revision of Terms
The developer may change these Terms at any time without prior notice to users if deemed necessary.<br/>
The revised Terms shall become effective at the time they are published on a platform where the Bot is available (such as the support server).<br/>

## 8. Governing Law
These Terms shall be interpreted in accordance with the laws of Japan.
