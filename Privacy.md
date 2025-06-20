# Santi Logger Privacy Policy

Last Updated: 19/06/2025
> Age verification has been added to Santi Logger. Policy changes include how 18+ flags are stored and processed, as well as additional information surrounding integration and data processing. 

Santi Logger is a Discord bot designed to assist with moderation and group management for communities using the VRChat platform. It is developed and maintained by an independent UK-based programmer, who also acts as the Data Controller for all personal data collected and processed through the bot under the UK General Data Protection Regulation (UK GDPR).

> ⚠️What is “Personal Data”
> In this policy, personal data refers to any information that can be used to identify an individual, either directly or indirectly. This can include things like Discord User IDS, VRChat User IDS, audit action references, and VRChat Group and Discord Server IDS. This service does not include usernames, profile avatars, IP addresses, or message content unrelated to the bot's commands and audit channels, unless otherwise stated. 

Santi Logger does not collect or store: 
Usernames or display names
Profile Pictures or avatars
Personal messages (DMs)
Any general chat content outside designated moderation channels
Government-issued ID, date of birth or IP addresses. 
## 1. Data Santi Logger Collects

Santi Logger collects only the personal data necessary to deliver our moderation and group management features:


Discord Information:
- Discord Server IDs
- Discord Channel IDs
- Discord User IDs of those who directly interact with the bot commands
- Discord Role IDs assigned within servers that interact with the bot

VRChat Information:
- VRChat User IDs associated with audit actions (kicks, bans, warnings)
- Audit Action IDs linked to specific moderation actions
- VRChat Group IDs for owners who utilise the bot
- Verification status (18+ flag from VRChat for users who opt in)
- Link between VRChat User ID and Discord User ID for users verified as 18+
> ⚠️ While usernames, avatars, profiles, and real-world information are not collected, these unique identifiers may still qualify as personal data under UK GDPR.


## 2. How Santi Logger Uses Your Data
Your data is processed only to enable the bot’s core features:

- Carrying out moderation actions (warnings, kicks, bans)
- Generating audit logs linked to VRChat moderation
- Producing analytics (e.g. group trends, moderator activity)
- Allowing group owners to manage their servers and roles
- Linking Discord and VRChat accounts to confirm verified 18+ status, used to enable access to certain group features or channels if configured by group owners

Analytics Generation
- Weekly and monthly reports (off by default, enabled by group owners)
- On-demand reports via command (by authorized moderators)

Message Content
Santi Logger only processes message content sent to channels explicitly designated for moderation commands. This includes kick, warn, or ban reasons. No Discord DMs, general messages or voice memos are logged, stored or processed. 

Santi Logger does not use your data for profiling, advertising, or automated decision-making.


## 3. Legal Basis for Processing Data

Santi Logger processes data under the following legal bases defined by the UK GDPR:
- Performance of a contract – The processing is necessary to provide group owners and moderators with the features they request, such as executing moderation commands, generating analytics and managing roles or groups. 


- Legitimate interests – The bot developer has a legitimate interest in ensuring the security, integrity and accountability of group moderation and audit functionality. These interests include:
	- Preventing abuse of moderation tools
	- Maintaining accurate group-level records for accountability
	- Supporting group owners with visibility into moderator activity
	- Enforcing group content restrictions (e.g., 18+ access) for safety and compliance
	- Enabling optional role assignments based on verified age status
The bot developer has conducted a Legitimate Interest Assessment  (LIA) to balance these needs against the rights and freedoms of individual users. The LIA concluded that:
The data collected is minimal, non-sensitive and relevant to the group moderation context
Processing does not override user privacy, especially given the transparency and opt-out mechanisms in place
Users are not subject to high-risk processing, profiling, or automated decisions

### Safeguards
To protect your rights when relying on legitimate interest, the bot developer has implemented the following safeguards: 
Data minimisation: Only IDs and action references are stored  – no unnecessary metadata, messages, or personal content
Limited retention: Data is deleted regularly, redactions are honoured and backups are purged
User access and control: Users can request a copy of their data or object to processing at any time
Context-based use: The bot is used in closed Discord server environments, and only for group moderation-related purposes
If future features require your explicit consent (e.g. analytics tied to external tools, or optional reporting features), Santi Logger will request this clearly before use. Consent can be withdrawn at any time by opening a support ticket. 

## 4. Data Storage and Security

All data is currently stored on self-hosted servers located in the UK. Santi Logger does not use third-party cloud providers at this time.
Security measures include:

- Encryption at rest and in transit

- Role-based access control

- Secure logging

- Rate-limiting to prevent scraping or abuse

Linked account records (VRChat to Discord) and verification flags are encrypted and stored securely with role-based access.

If the bot developer adopts third-party subprocessors in the future, they will be vetted for GDPR compliance, and this policy will be updated.

In the event of a data breach, affected users and the UK Information Commissioner's Office (ICO) will be notified within 72 hours, as required by law.


## 5. Data Retention

Santi Logger retains data only as long as necessary:

- Moderation and audit logs: Up to 12 months, unless required for ongoing group management
- Inactive groups: Reviewed and purged after 6 months of inactivity
- Redacted logs: Group owners can request deletion of specific moderation entries
- Deletion requests: Processed within 30 days unless retention is required for legal reasons

Backups are purged as part of the deletion process.
> 🛑 Important: VRChat User IDs are controlled and continually issued by the VRChat platform. If a user wants their data to stop appearing in our system, they would need to delete their VRChat account. We cannot remove or prevent the re-entry of active platform user IDS.

## 6. Data Sharing and Subprocessors

Santi Logger and the bot developer do not sell, rent, or share your data with third parties.

The bot developer may disclose data only:

- To comply with legal obligations
- To protect the safety, rights, or property of others
- At the explicit request of the data subject

The bot developer may use subprocessors (e.g., cloud storage providers) in the future. Any subprocessors will process data under strict confidentiality agreements and GDPR-aligned terms.


## 7. Your Rights Under UK GDPR
You have the right to:

- Access your personal data
- Correct inaccurate or incomplete information
- Request deletion of your data (within limits described above)
- Restrict or object to certain types of processing
- Receive a copy of your data in a portable format

To exercise your rights, open a ticket in our support Discord server. The bot developer may request ID verification and will respond within 30 days.


## 8. Age Restrictions and Verification
Santi Logger is intended for users aged 18 and older.
Santi Logger now supports optional linking of a VRChat account to a Discord account if the VRChat user has successfully passed 18+ age verification via VRChat’s third-party provider. This is used to confirm eligibility for adult-only roles or features within Discord servers.
- The bot developer and Santi Logger do not process or store any government-issued IDS.

- VRChat offers an optional age verification system. If a user passes age verification, Santi Logger may store a simple flag indicating this.

- Linking is only processed if age verification is confirmed via VRChat's third-party. If verification is revoked or missing, Santi Logger does not store the user at all.

- Group owners are still responsible for managing age-restricted access in their communities. Santi Logger offers this feature to support, not enforce, compliance. Santi Logger assumes no liability for age enforcement failures at the group level.



## 9. Shutdown and Data Portability
If the Santi Logger service is discontinued, group owners will be provided a complete CSV export of their data (logs, analytics, group settings). Instructions will be sent via Discord prior to shutdown.


## 10. Changes to This Privacy Policy

The bot developer may revise this Privacy Policy from time to time. Significant updates will be communicated via Discord announcements or direct messages. The bot developer encourages users to review the policy periodically.

## 11. Contact Us

For questions regarding this Privacy Policy or to exercise your data protection rights, please open a ticket through our Discord server https://discord.gg/afterhrs

<br>
By using the Santi Logger bot, you acknowledge and agree to the terms outlined in this Privacy Policy.


# Previous Updates:

> 20/04/2025 - Privacy Policy first published publicly. 
