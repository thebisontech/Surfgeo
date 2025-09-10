### SSO Setup

**Single Sign-On (SSO)** integration streamlines access management while enhancing security through **centralized authentication**.

### Google Workspace Integration

- Connect Surfgeo with **Google Workspace** for seamless authentication.
- Setup requires Google Workspace **admin privileges** to:
    - Configure OAuth 2.0 credentials
    - Add Surfgeo as a trusted application
    - Configure attribute mapping for user provisioning
- Once configured, users:
    - Sign in with Google accounts
    - Are automatically provisioned on first login (based on email domain)
    - Inherit group-based permissions
    - Are automatically deprovisioned when removed from Google
- Supports both **individual** and **bulk provisioning** through Google groups.

---

### 2FA Options

**Two-factor authentication (2FA)** adds an essential layer of security for protecting **sensitive competitive intelligence**.

### Email Verification link

- Sends a verification link to the registered email.
- link valid for **10 minutes**, with rate limiting to prevent abuse.

### Enforcement Policies

- Configure 2FA requirements based on security needs:
    - Mandatory for all users
    - Required for owners and admins only
    - Optional but encouraged (with dashboard reminders)
    - Grace periods for new users to configure 2FA
- The platform tracks **2FA adoption rates** and can generate **compliance reports** for audits.

---

### Session Timeout Policy

Automatic **session management** balances security with user convenience.

### Default Configuration

- Sessions timeout after **30 minutes of inactivity**.
- Active sessions extend automatically with user activity.
- Warning notification appears **5 minutes before timeout**, allowing users to extend with one click.