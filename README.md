# 👨‍💻 Prashant Kumar Sharma – Ethical Hacker & Bug Bounty Hunter

🎯 **Focused on Web Application Security | CVE Learnings | Bug Hunting Logs**

---

## 🧠 About Me

Hi, I'm Prashant – an ethical hacker passionate about securing the web. I focus on:

- ✅ Web App Vulnerabilities (XSS, IDOR, SSRF, RCE)
- ✅ Bug bounty on platforms like hackthebox.com
- ✅ CVE Research & Exploit Development

I'm continuously learning, building tools, and writing redacted reports to help others grow in the infosec space.

---

## 📚 CVE Learnings

- **CVE-2021-26084** – Atlassian Confluence OGNL Injection
  - Learned exploiting OGNL expressions in templates.
  - Focus: CVE structure, patch diffing, writing PoCs.

---

## 📝 Redacted Bug Report

```txt
🔍 Target: [REDACTED].com
Issue: IDOR in user profile update
Severity: High
Steps to Reproduce:
1. Login as user A
2. Capture PUT /api/user/123
3. Change user ID to 124 and update
Impact: Full account takeover
