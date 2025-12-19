# Privacy Policy for spell Bot

**Last Updated:** December 19, 2025

## Introduction

spell ("the Bot") is a Discord bot that provides username rarity checking and username collection browsing services. This Privacy Policy explains how we collect, use, and protect your data when you use the Bot.

## Data We Collect

### Automatically Collected Data

When you use spell, we collect and process the following data:

1. **Server Information**
   - Server ID (Guild ID)
   - Channel IDs where the bot is configured
   - Server member count (for statistics)

2. **User Information (Temporary)**
   - Discord User ID (when using commands)
   - Discord Username (for rarity analysis)
   - User Avatar URL (displayed temporarily during rarity checks)
   - User mentions (when comparing usernames)

3. **Server Settings**
   - DM Rarity toggle preference (enabled/disabled per server)
   - Setup channel configurations

### Message Content

The Bot processes message content **only** for:
- Detecting command prefixes (`;` commands)
- Parsing command arguments (usernames, user mentions)
- Detecting bot mentions (`@spell`)

**Message content is NOT stored, logged, or retained after processing.**

## Data Storage

### What We Store Permanently

We store the following data in our PostgreSQL database:

- **Server ID** and **DM Rarity Setting** (enabled/disabled)
- **Channel IDs** where username browser is configured
- Timestamp of last setting update

### What We DO NOT Store

We **do not** store:
- Message content or message history
- User personal information beyond usernames
- User presence data (online/offline status, activities)
- Direct messages between users
- Voice or video data
- User IP addresses
- User email addresses

## How We Use Your Data

### Primary Use Cases

1. **Command Processing**
   - Reading messages to detect and execute commands
   - Analyzing usernames for rarity scores
   - Generating leaderboards and comparisons

2. **Feature Functionality**
   - Storing server preferences for DM welcome messages
   - Maintaining setup configurations for username browsers
   - Providing username collection browsing

3. **Bot Statistics**
   - Counting total servers and users (aggregate only)
   - Monitoring bot uptime and performance

### What We DON'T Do

We **never**:
- Sell or share your data with third parties
- Use data for advertising or marketing
- Train AI/ML models with your data
- Track user behavior across servers
- Store data longer than necessary

## Data Access and Sharing

### Who Has Access

- **Bot Developer Only**: The bot developer has access to stored server settings for maintenance and support purposes
- **No Third Parties**: We do not share data with any third-party services, advertisers, or data brokers
- **Discord Inc.**: Data flows through Discord's API as required for bot functionality

### When We Share Data

We only share data in these limited circumstances:
- **Legal Requirements**: If required by law, court order, or legal process
- **Safety**: To protect against abuse, fraud, or security threats
- **With Your Consent**: When you explicitly authorize sharing

## Data Security

### Security Measures

We implement industry-standard security practices:

- **Encrypted Database**: PostgreSQL database with SSL/TLS encryption
- **Secure Hosting**: Bot hosted on secure cloud infrastructure
- **Access Controls**: Limited access to production systems
- **No Plain-Text Storage**: Sensitive data is never stored in plain text
- **Regular Updates**: Dependencies and systems regularly updated

### Limitations

While we take security seriously, no system is 100% secure. We cannot guarantee absolute security against unauthorized access, hacking, or data breaches.

## Data Retention

### How Long We Keep Data

- **Server Settings**: Retained while the bot is in your server
- **Setup Configurations**: Retained until removed by server administrators
- **Message Content**: NOT retained (processed in real-time only)
- **Temporary Data**: Cleared immediately after command execution

### Data Deletion

Data is automatically deleted when:
- The bot is removed from a server (all server-specific data deleted)
- A server administrator removes setup configurations
- A user requests data deletion (see Your Rights below)

## Your Rights

### User Rights

You have the right to:

1. **Access Your Data**: Request information about what data we store
2. **Delete Your Data**: Request deletion of your server's data
3. **Opt-Out**: Stop using the bot at any time
4. **Correct Data**: Request correction of inaccurate data
5. **Data Portability**: Request a copy of your server's stored settings

### How to Exercise Your Rights

To exercise any of these rights:
- Contact the bot developer via Discord: `@spaying`
- Email: [Add your email if you want to provide one]
- Submit a request in the support server: [Add link if you have one]

### Opt-Out Options

You can opt-out by:
- Not using the bot's commands
- Disabling DM Rarity feature (`;dmrarity` command)
- Blocking bot DMs in Discord privacy settings
- Removing the bot from your server (full data deletion)

## Children's Privacy

The Bot complies with COPPA (Children's Online Privacy Protection Act):

- We do not knowingly collect data from children under 13
- We do not target content toward children
- If we learn we've collected data from a child under 13, we'll delete it immediately
- Parents/guardians can request deletion of their child's data

## Changes to Privacy Policy

### Policy Updates

We may update this Privacy Policy to:
- Reflect changes in functionality
- Comply with legal requirements
- Improve clarity and transparency

### Notification of Changes

When we make material changes:
- Update the "Last Updated" date at the top
- Post announcement in bot's status/support server
- Users are encouraged to review periodically

### Your Continued Use

Continued use of the Bot after policy changes constitutes acceptance of the updated policy.

## International Data Transfers

The Bot may process data across international borders. By using the Bot:
- You consent to data processing in various jurisdictions
- We ensure appropriate safeguards for international transfers
- Data is protected regardless of processing location

## Third-Party Services

### Discord Platform

The Bot operates on Discord's platform and is subject to:
- [Discord's Privacy Policy](https://discord.com/privacy)
- [Discord's Terms of Service](https://discord.com/terms)
- Discord's Developer Terms

### No Other Third Parties

We do **not** use:
- Analytics services (Google Analytics, etc.)
- Advertising networks
- Data brokers or aggregators
- External logging services

## Contact Information

### Questions or Concerns

For privacy-related questions, concerns, or requests:

- **Discord**: `@spaying`
- **GitHub Issues**: https://github.com/spaying/spell-docs/issues
- **Email**: [Add your email if applicable]

### Response Time

We aim to respond to all privacy inquiries within:
- **Urgent matters**: 24-48 hours
- **General inquiries**: 5-7 business days
- **Data deletion requests**: 30 days maximum

## Legal Information

### Governing Law

This Privacy Policy is governed by the laws of [Your Country/State].

### Compliance

We comply with:
- General Data Protection Regulation (GDPR) - EU users
- California Consumer Privacy Act (CCPA) - California users
- Children's Online Privacy Protection Act (COPPA) - US children
- Discord Developer Terms of Service
- Discord Developer Policy

### Dispute Resolution

Any disputes regarding privacy will be resolved through:
1. Good faith negotiation
2. Mediation if necessary
3. Jurisdiction courts if required

---

## Summary (TL;DR)

**What we collect:**
- Server IDs and channel IDs for setup
- Usernames temporarily for rarity checks
- Server preference settings

**What we DON'T collect:**
- Message history or content (beyond real-time command processing)
- Personal information
- User activity or presence data

**How we use data:**
- Only for bot functionality (commands, settings)
- Never sold or shared with third parties
- Never used for ads or AI training

**Your rights:**
- Request data deletion anytime
- Opt-out by not using commands
- Remove bot to delete all server data

**Questions?** Contact @scrolling @5qw @glamorizing on Discord

---

*This Privacy Policy is effective as of December 19, 2025 and applies to all users of the spell Discord bot.*
