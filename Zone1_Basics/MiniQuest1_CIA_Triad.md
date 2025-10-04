# 🏰 MiniQuest 1: The Village of Infocyte – CIA Triad

Welcome, Apprentice Guardian! 🌟  
Before you can defend the digital realm, you must master the **CIA Triad** — the foundation of all cybersecurity.

---

### 🛡️ Step 1: Learn the Basics (What & Why)

**Confidentiality (C)**  
- **What:** Keeping information secret — only authorised people can read it.  
- **Why:** If attackers read private data (passwords, bank details, health records), people can be harmed financially or personally.

**Integrity (I)**  
- **What:** Ensuring information is correct and hasn't been changed without permission.  
- **Why:** If data is altered (bank balances, grades, firmware), it can cause wrong decisions or dangerous results.

**Availability (A)**  
- **What:** Making sure systems and data are accessible when authorised users need them.  
- **Why:** If services are down (banking, hospitals, websites), people can’t perform critical tasks.

---

### 🧰 Step 2: Common Tools (What they are & why they’re used)

**For Confidentiality**
- **Encryption (AES for data at rest; TLS for data in transit)** — Scrambles data so only holders of the key can read it. Used to protect files, emails, web traffic, and backups.
- **Passwords + Multi-Factor Authentication (MFA)** — Passwords identify users; MFA (authenticator apps, hardware tokens) adds extra proof so accounts are harder to steal. (Avoid relying only on SMS-based codes.)
- **Access Controls (Role-Based Access Control, Least Privilege)** — Limits who can view or access specific data (e.g., HR can view salaries, others cannot).

**For Integrity**
- **Cryptographic Hashing (SHA-256)** — Produces a fixed “fingerprint” of data; if data changes, the hash changes. Used to verify file downloads, verify logs, and detect tampering.
- **Digital Signatures (public-key crypto)** — Signs data with a private key so anyone with the public key can verify both the author and that the data hasn’t changed.
- **Checksums (CRC etc.)** — Simple error-check tools for detecting accidental corruption during transfer (not secure against attackers unless combined with signing).

**For Availability**
- **Backups (regular, tested, and isolated/offline copies)** — Restore data after loss or ransomware. Offline/air-gapped or immutable backups resist deletion or encryption by attackers.
- **Redundancy & Failover (multiple servers, data replicas)** — Keeps services running if one server fails.
- **DDoS Mitigation (CDNs, load balancers, rate limiting)** — Stops or absorbs fake traffic so real users can still access services.

---

### 🧠 Step 3: Reflect with Simple Examples

- **Confidentiality:** WhatsApp end-to-end encryption — only sender and receiver can read messages.  
- **Integrity:** When you download software, the developer provides a SHA-256 hash or a signed checksum so you can verify the file was not altered.  
- **Availability:** Google Search stays available because of many redundant servers and CDNs.

---

### ⚠️ Quick notes to avoid confusion (short & important)
- Use **SHA-256** (or stronger) — avoid relying on MD5 for security (it’s broken for cryptographic integrity).  
- **Checksums** detect accidental errors; **cryptographic hashes + signatures** detect malicious tampering.  
- **MFA**: Authenticator apps or hardware tokens are stronger than SMS.  
- **Backups** must be tested and stored so attackers can’t easily delete or encrypt them (immutable or offline is best).

---

### 🎯 Mission & Reward
- **Your Mission:** Be able to explain C, I, A in simple words and give one real-world example for each.  
- **XP Earned:** +50  
- **Shade Unlocked:** 💠 *Shade of Confidentiality*

> “Knowledge is your shield, logic your sword. Keep learning, Guardian.”
