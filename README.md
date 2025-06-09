# Suspicious-Browser-Extensions

![Brave Shield Logo](https://brave.com/wp-content/uploads/2020/11/brave-shields-logo.png)

## 🔍 Audit Summary
Conducted a security review of installed Brave extensions to:
- Remove unnecessary/redundant extensions
- Identify potential security risks
- Document performance impact

## 🛠️ Actions Taken
1. **Removed Extensions**:
   - `Ad Block` (Built-in Brave Shields provide equivalent functionality)
   - `Scribble` (Unused extension with unverified developer)

2. **Verified Native Protections**:
   - Confirmed Brave Shields (`brave://settings/shields`) are active
   - Tested ad/tracker blocking on multiple sites

3. **Performance Check**:
   - No noticeable impact on browsing speed
   - No unexpected pop-ups or redirects observed

## 📝 Full Audit Details
[View Complete Audit Log](./extension_audit_log.md)

## 🔒 Security Recommendations
- **Monthly Audits**: Review extensions regularly
- **Minimal Extensions**: Only keep essential, vetted add-ons
- **Permission Checks**: Verify extension access requirements
- **Developer Verification**: Prefer extensions from known developers

## ℹ️ About Brave's Security
Brave provides built-in protections including:
- Ad/tracker blocking
- Fingerprinting prevention
- HTTPS Everywhere
- Cookie blocking

No additional extensions needed for basic privacy protection.
