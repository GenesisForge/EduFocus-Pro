# Privacy Policy - EduFocus Pro

**Last Updated:** October 5, 2025  
**Version:** 3.0.0  
**Effective Date:** October 1, 2025

---

## Our Privacy Commitment

EduFocus Pro is designed with **privacy-first principles**. We believe students deserve tools that respect their data and their right to learn without surveillance.

This policy uses clear language because privacy shouldn't require a law degree to understand.

**Our core promise: Your data stays on your device. Period.**

---

## Table of Contents

1. [What Data We Collect](#what-data-we-collect)
2. [Where Your Data Lives](#where-your-data-lives)
3. [What We DON'T Do](#what-we-dont-do)
4. [Browser Permissions](#browser-permissions)
5. [Internet Connections](#internet-connections)
6. [GDPR Compliance](#gdpr-compliance-european-union)
7. [Children's Privacy](#childrens-privacy-coppa--gdpr-k)
8. [Managing Your Data](#managing-your-data)
9. [Data Security](#data-security)
10. [Third-Party Services](#third-party-services)
11. [Changes to This Policy](#changes-to-this-policy)
12. [Contact & Verification](#contact--verification)

---

## What Data We Collect

**None.**

EduFocus Pro collects **zero personal data**. We don't track you, we don't profile you, and we don't know who you are.

**No analytics. No telemetry. No tracking. Nothing.**

We don't know:
- ❌ Who you are (name, email, age, location)
- ❌ What you study or how you perform
- ❌ When or how long you use the extension
- ❌ What device or browser you're using
- ❌ Any usage statistics or patterns
- ❌ Literally anything about you

---

## Where Your Data Lives

All data created in EduFocus Pro is stored **locally on your device** using Chrome's encrypted local storage API (`chrome.storage.local`).

### What Gets Stored Locally

Your device stores:

- ⏱️ **Timer settings and history** - Pomodoro configurations, completed sessions
- 🎯 **Focus statistics** - Study time, streaks, productivity metrics
- 📝 **Notes** - All text, formatting, tags, and organization
- 🧠 **Quizzes** - Custom quizzes, questions, answers, results
- 🗂️ **Flashcards** - Decks, cards, study progress, spaced repetition data
- 📅 **Tasks** - To-dos, deadlines, priorities
- ⚙️ **Settings** - Language, theme, accessibility options

### How It's Stored

- **Format:** JSON (JavaScript Object Notation) - readable, standard format
- **Encryption:** Protected by Chrome's built-in storage encryption
- **Location:** Your browser's profile folder on your hard drive
- **Access:** Only you and the EduFocus Pro extension can access this data

### What This Means

**This data never leaves your computer.** It is not:
- ❌ Uploaded to servers
- ❌ Sent to cloud services
- ❌ Shared with third parties
- ❌ Accessible to Genesis Forge
- ❌ Transmitted over the internet

**Think of it like a notebook:** When you write in a physical notebook, the notes stay in that notebook. Same concept, but digital.

### Chrome Sync (Optional)

If you have Chrome sync enabled in your browser settings:
- Chrome may sync your EduFocus Pro data to your Google account
- This is a **Chrome feature**, not an EduFocus Pro feature
- We have no control over or visibility into Chrome sync
- Data synced through Chrome is encrypted by Google

**To disable extension sync:**
1. Go to `chrome://settings/syncSetup`
2. Click "Manage sync"
3. Disable "Extensions" sync
4. Your EduFocus Pro data will remain local-only

---

## What We DON'T Do

### Data Collection
- ❌ Collect personal information
- ❌ Track browsing history
- ❌ Use analytics or telemetry
- ❌ Install cookies or tracking pixels
- ❌ Monitor activities
- ❌ Profile or fingerprint users
- ❌ Log IP addresses
- ❌ Record keystrokes
- ❌ Collect usage statistics

### Data Sharing
- ❌ Share data with third parties
- ❌ Sell or monetize your data
- ❌ Provide data to advertisers
- ❌ Send data to external services
- ❌ Report to schools or parents

### Advertising & Marketing
- ❌ Display advertisements
- ❌ Use advertising networks
- ❌ Market to children
- ❌ Send promotional emails
- ❌ Build targeting profiles

### Accounts & Authentication
- ❌ Require account creation or login
- ❌ Request passwords
- ❌ Store credentials
- ❌ Authenticate users

### Device Access
- ❌ Access your camera (ever)
- ❌ Access your microphone (except voice notes - see below)
- ❌ Access your location
- ❌ Read your files
- ❌ Access your contacts
- ❌ Monitor clipboard (except when you paste)

---

## Browser Permissions

EduFocus Pro requests minimal Chrome permissions. Here's exactly what we ask for and why:

### ✅ Storage (Required)
**Permission:** `storage`

**Why we need it:**
- To save your notes, timers, settings, and study materials locally
- Without this, nothing would be saved when you close the extension

**What we can access:**
- Only our own storage space (isolated from other extensions and websites)
- Cannot read data from other extensions
- Cannot access cookies or browsing history

**Security:**
- Data encrypted by Chrome automatically
- No network transmission of this data

### 🎤 Microphone (Optional - Only When Requested)
**Permission:** `microphone` (optional)

**Why we need it:**
- For the voice dictation feature in the Notes tab
- Allows voice-to-text note-taking

**When it's used:**
- **Only** when you click the microphone button in Notes
- Never runs in the background
- Permission request appears first time you use the feature

**How to control it:**
- Deny the permission prompt when it appears
- Revoke anytime: `chrome://settings/content/microphone`
- Or: `chrome://extensions` → EduFocus Pro → Remove permissions

**What we do with audio:**
- Audio is processed locally by Chrome's Web Speech API
- No audio is recorded, stored, or transmitted
- No audio files are created
- Processing happens entirely on your device

### ❌ Permissions We DON'T Request

We do **not** request:
- `tabs` - Can't see what websites you visit
- `history` - Can't access browsing history
- `cookies` - Can't read cookies
- `webRequest` - Can't intercept network traffic
- `geolocation` - Can't access location
- `camera` - Can't access webcam
- `downloads` - Can't access downloads
- `bookmarks` - Can't read bookmarks

### How to Verify Permissions

1. Go to `chrome://extensions/`
2. Find EduFocus Pro
3. Click "Details"
4. Scroll to "Permissions"
5. Review all requested permissions

You should see only Storage (and Microphone if you enabled voice notes).

---

## Internet Connections

EduFocus Pro operates **100% offline** after initial installation.

### 1. External Resource Links (Optional)

The Resources tab provides links to educational websites. These are standard hyperlinks that open in your browser.

**Danish Educational Resources:**
- 📚 **Undervisningsministeriet** (uvm.dk) - Danish Ministry of Education
- 🎓 **Khan Academy** (da.khanacademy.org) - Free educational videos
- 🔬 **Videnskab.dk** - Science news and articles
- 📖 **Den Store Danske** (lex.dk) - Danish encyclopedia
- 📺 **DR Skole** (dr.dk/skole) - Danish Broadcasting educational content

**What we do:**
- ✅ Provide convenient links to educational resources
- ✅ Open links in new tabs (standard browser behavior)

**What we DON'T do:**
- ❌ Track which links you click
- ❌ Receive reports about your activity
- ❌ Pass your data to these websites
- ❌ Add tracking parameters to URLs
- ❌ Receive referral commissions (not affiliate links)

**Important:** When you click these links, you're visiting external websites with their own privacy policies. We're not responsible for their data practices.

### 2. Chrome Web Store Updates (Automatic)

**What happens:**
- Chrome automatically checks for extension updates
- Managed by Google, not by us

**What we don't do:**
- ❌ Control when updates are checked
- ❌ Know when you update
- ❌ Receive reports about installations
- ❌ Track update activity

### 3. No Other Network Activity

**Verification methods:**

**Method 1: Browser DevTools**
1. Open EduFocus Pro
2. Press F12 to open DevTools
3. Go to Network tab
4. Use all features
5. Observe: Zero network requests

**Method 2: Offline Test**
1. Disconnect from internet
2. Use all features
3. Observe: Everything works perfectly

---

## GDPR Compliance (European Union)

EduFocus Pro fully complies with the General Data Protection Regulation (GDPR - Regulation 2016/679).

### Your GDPR Rights

Since we don't collect any personal data, most GDPR requirements don't apply, but here's how we address each right:

#### Right to Access (Article 15)
**What it means:** Right to access your data.

**How we comply:**
- All your data is on your device and accessible anytime
- Export your data: Settings → Export All Data
- No data for us to provide - you have full access

#### Right to Rectification (Article 16)
**What it means:** Right to correct inaccurate data.

**How we comply:**
- You control all data locally
- Edit notes, flashcards, quizzes directly
- No need to contact us

#### Right to Erasure (Article 17)
**What it means:** Right to have your data deleted.

**How we comply:**
- Settings → Clear All Data (permanent deletion)
- Or uninstall the extension
- We have no copies because we never collected it

#### Right to Data Portability (Article 20)
**What it means:** Right to receive your data in a portable format.

**How we comply:**
- Settings → Export All Data
- Creates standard JSON file
- Transfer to other tools or devices

#### Right to Object (Article 21)
**What it means:** Right to object to processing.

**How we comply:**
- Not applicable - no external processing
- You can stop using the extension anytime

### Legal Basis for Processing

We process local data based on:

**Article 6(1)(a) - Consent:**
- You install and use voluntarily
- You can uninstall anytime

**Article 6(1)(f) - Legitimate Interest:**
- Local storage is necessary for the extension to function
- Minimal processing, maximum privacy

**Important:** Since data never leaves your device, this is like writing in a physical notebook - no data "processing" in the GDPR sense occurs on our end.

### Data Controller Information

**Data Controller:** Genesis Forge  
**Location:** Denmark  
**Contact:** edufocusbusiness@gmail.com

### Supervisory Authority

**Datatilsynet** (Danish Data Protection Agency)  
**Website:** datatilsynet.dk  
**Email:** dt@datatilsynet.dk  
**Phone:** +45 33 19 32 00

You have the right to lodge complaints with Datatilsynet or your local data protection authority.

---

## Children's Privacy (COPPA & GDPR-K)

EduFocus Pro is designed for students of all ages, including children. We take children's privacy extremely seriously.

### COPPA Compliance (United States - Under 13)

**How we comply:**

✅ **No Data Collection**
- COPPA-compliant by design
- No personal information collected from anyone, including children

✅ **No Parental Consent Required**
- Not needed because we collect no data
- No registration or accounts

✅ **No Advertising**
- No advertisements displayed
- No behavioral advertising
- No marketing to children

✅ **No Tracking**
- No persistent identifiers
- No user profiling
- No monitoring

✅ **Parental Rights**
- Parents can review all data (it's on the device)
- Parents can delete all data (uninstall or clear)
- Parents can refuse collection (there is none)

### GDPR-K Compliance (European Union - Children)

**How we comply:**

✅ **No Parental Consent Required**
- Not needed because we collect no data
- Children can use without authorization

✅ **Age-Appropriate**
- Clear, simple interface
- Educational focus
- No commercial pressure

✅ **No Profiling**
- No algorithmic decisions
- No targeting
- No behavioral analysis

### For Parents & Teachers

**How to inspect stored data:**

**Method 1: Export**
1. Open EduFocus Pro
2. Settings → Export All Data
3. Review the JSON file in text editor

**Method 2: DevTools**
1. Open EduFocus Pro
2. Press F12 → Application → Local Storage
3. Find EduFocus Pro entry
4. Review all data (plain JSON)

**What you'll see:**
- Notes, flashcards, quizzes (readable text)
- Study statistics (numbers, dates)
- Settings (language, theme, etc.)

**What you WON'T see:**
- No tracking IDs
- No user identifiers
- No analytics
- No hidden data

---

## Managing Your Data

### Export Your Data

**Purpose:** Backup or transfer to another device.

**How to export:**
1. Open EduFocus Pro
2. Settings → Export All Data
3. Choose save location
4. JSON file is downloaded

**What's included:**
- All notes, flashcards, quizzes
- Study statistics and history
- Settings and preferences

**File format:** Standard JSON (readable in text editor)

**Use cases:**
- 💾 Regular backups (recommended!)
- 📱 Transfer between devices
- 🔍 See exactly what's stored

### Import Your Data

**How to import:**
1. Settings → Import Data
2. Select JSON backup file
3. Confirm (overwrites existing data)
4. Data restored immediately

⚠️ **Warning:** Importing replaces ALL current data. Export first if you want to keep it.

### Delete Your Data

**Option 1: Clear All Data**
- Settings → Clear All Data
- Confirms twice (prevents accidents)
- All data permanently deleted
- Extension remains installed

**Option 2: Uninstall**
- `chrome://extensions/` → Remove
- Complete removal
- All data deleted

**Option 3: Selective Deletion**
- Delete individual notes, decks, or quizzes
- Keeps other data intact

⚠️ **Deletion is permanent.** Export first if you might want the data later.

---

## Data Security

Since data is stored locally, security depends on your device security.

### What Protects Your Data

✅ **Chrome's Encrypted Storage**
- Automatic encryption by Chrome
- OS-level protection (DPAPI on Windows, Keychain on Mac)

✅ **Device Security**
- Your device password/PIN
- Full-disk encryption (BitLocker, FileVault)
- Antivirus software

✅ **Browser Security**
- Chrome's sandboxing
- Extension isolation
- Regular security updates

### Security Best Practices

**For Personal Devices:**
1. Use strong device password
2. Enable full-disk encryption
3. Keep Chrome updated
4. Lock computer when away
5. Export backups regularly
6. Use antivirus software

**For Shared Computers (School, Library):**
1. Use separate Chrome profile
2. Enable Chrome profile locking
3. Export backups to personal USB/cloud
4. Clear data before logging out
5. Never leave computer unlocked
6. Don't store sensitive info in notes

### What We Can't Protect Against

Since data is local, we cannot protect against:

❌ **Physical Device Access**
- Someone with access to your unlocked device can see your data
- **Mitigation:** Lock device, strong passwords

❌ **Malware**
- Malware could access local data
- **Mitigation:** Antivirus, careful downloads

❌ **Lost/Stolen Devices**
- Data accessible if device not encrypted
- **Mitigation:** Full-disk encryption, remote wipe

### Data Breach Response

**Can EduFocus Pro be breached remotely?**

No. Because there's no central database:
- No servers to hack
- No data transmission to intercept
- No "EduFocus Pro database" exists

Your data security depends entirely on your device security.

**If your device is compromised:**
- Standard security practices apply (malware scan, password changes)
- We cannot remotely access or wipe your data
- You're responsible for device security

**Report security vulnerabilities:**
Email: edufocusbusiness@gmail.com  
Subject: **SECURITY VULNERABILITY**

We take security reports seriously and respond within 24 hours.

---

## Third-Party Services

EduFocus Pro does not integrate with any third-party services for core functionality.

### External Links

The Resources tab links to educational websites. These are standard hyperlinks - no tracking, no data sharing.

**Linked websites:**
- Undervisningsministeriet (uvm.dk)
- Khan Academy (da.khanacademy.org)
- Videnskab.dk
- Den Store Danske (lex.dk)
- DR Skole (dr.dk/skole)

These websites have their own privacy policies. We're not responsible for their practices.

### No Other Integrations

We do **not** use:
- ❌ Analytics services (Google Analytics, etc.)
- ❌ Crash reporting (Sentry, etc.)
- ❌ Advertising networks
- ❌ Cloud storage
- ❌ Authentication providers
- ❌ Any external APIs

**Everything runs locally.**

---

## Changes to This Policy

If we update this policy:

1. ✅ Update "Last Updated" date
2. ✅ Increment version number
3. ✅ Include details in release notes
4. ✅ Display notice in extension (for major changes)

**Our core commitment will NEVER change: Your data stays on your device.**

### Version History

**v3.0.0 (October 2025)** - Current version
- Balanced detail and readability
- Enhanced clarity

**v2.0.0 (October 2025)**
- Expanded GDPR/COPPA sections
- Added permissions details

**v1.0.0 (Initial release)**
- Original privacy policy

---

## Contact & Verification

### Contact Us

**Privacy questions or concerns:**

📧 **Email:** edufocusbusiness@gmail.com  
🕐 **Response time:** Within 7 business days  
🗣️ **Languages:** Danish, English

**For security issues:** Use subject "SECURITY VULNERABILITY"

### Verify Our Claims

Don't just trust us - verify:

**✅ Check Network Activity**
1. Open EduFocus Pro + DevTools (F12)
2. Network tab → Use all features
3. See: Zero requests

**✅ Check Permissions**
1. `chrome://extensions/` → EduFocus Pro → Details
2. See: Only Storage (+ optional Microphone)

**✅ Check Stored Data**
1. Settings → Export All Data
2. Open JSON in text editor
3. See: Only your content

**✅ Test Offline**
1. Disconnect internet
2. Use all features
3. See: Everything works

---

## Jurisdiction & Governing Law

**Developed in:** Denmark 🇩🇰  
**Governed by:** GDPR (Regulation 2016/679) and Danish law  
**Supervisory Authority:** Datatilsynet (datatilsynet.dk)

For legal questions specific to your region, consult local authorities.

---

## Available Languages

This privacy policy is available in:
- 🇬🇧 English (privacy_en.md)
- 🇩🇰 Danish (privacy_da.md)
- 🇩🇪 German (privacy_de.md)
- 🇺🇦 Ukrainian (privacy_uk.md)

Need another format? Email us for large print, screen-reader-optimized, or simplified versions.

---

## Why We Built It This Way

**Students deserve privacy while learning.**

Too many educational tools track students, collect data, and prioritize engagement over education. We built EduFocus Pro differently:

- 📚 **Education-focused** - Learning, not surveillance
- 🔒 **Privacy-first** - Built with privacy from day one
- 🆓 **Truly free** - No hidden costs or data harvesting
- 💪 **User-controlled** - Your data, your device, your choice

**This is education software built the way it should be: Private, secure, and focused on learning.**

---

## Simple Summary

**Your data = Your business**

Everything stays on your computer. We can't see it, don't want to see it, and designed the system so we couldn't see it even if we wanted to.

### Core Promise

- **Collect:** Nothing
- **Track:** Nothing
- **Share:** Nothing
- **Store remotely:** Nothing

### For Everyone

**Students:** Study privately without surveillance  
**Parents:** Your child's data stays safe  
**Teachers:** Recommend with confidence  
**Everyone:** Privacy without compromise

---

**Questions? Email us: edufocusbusiness@gmail.com**

**This policy is effective as of October 2025 and applies to EduFocus Pro v3.5.0 and later.**

© 2025 Genesis Forge. Licensed under PROPRIETARY License.

---

**Privacy is a right, not a privilege.**