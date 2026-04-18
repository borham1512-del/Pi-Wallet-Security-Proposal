# [Proposal] Hybrid Application Layer Security (ALS) for Pi Network Wallets

### Overview
This proposal introduces a secondary security layer (ALS) to protect Pi Wallets from unauthorized access and "Passphrase Phishing," ensuring that assets remain secure even if the primary passphrase is compromised.

### Proposed Security Features:
1. **Time-Locked Transactions:** Ability to set a mandatory delay (e.g., 24 hours) for large transfers.
2. **Device-Binding:** Linking the wallet to a specific hardware ID (MAC/IMEI) to prevent access from unknown devices.
3. **Emergency "Freeze" Protocol:** A one-time recovery key to lock the account immediately if suspicious activity is detected.
4. **Multi-Factor Authentication (MFA):** Integrating biometric or SMS verification as a secondary gateway for outgoing transactions.
5. **ALS Shield:** A persistent encryption layer that protects the passphrase during entry.

**Submitted by:** Khaled Borham
**Status:** Open for Discussion
