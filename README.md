# BugBuntyDorks: basic-to-pro
🔍 Bug Bounty Discovery Dorks Collection
https://img.shields.io/badge/Bug-Bounty-red
https://img.shields.io/badge/Security-Research-blue
https://img.shields.io/badge/Google-Dorks-green
https://img.shields.io/badge/Updated-January_2024-orange

📖 Overview
A curated collection of Google Dorks specifically designed for security researchers and bug bounty hunters to discover vulnerability disclosure programs, bug bounty programs, and security reporting pages. This repository is regularly updated with the most effective search queries.

⚠️ IMPORTANT DISCLAIMER
READ THIS BEFORE USING ANY DORKS:

plaintext
❌ NEVER test on targets without explicit authorization
❌ ALWAYS review the program's policy before testing
❌ RESPECT all laws and regulations in your jurisdiction
✅ ONLY test on programs with public bug bounty pages
✅ ALWAYS follow responsible disclosure practices
✅ REPORT vulnerabilities ethically and responsibly
The maintainers of this repository are NOT responsible for any misuse of these dorks. Use at your own risk.

🗂️ Dorks Categories
1. General Bug Bounty Programs
google
inurl:/bug-bounty program
inurl:/security "bounty" OR "reward" OR "swag"
"submit vulnerability report" "reward"
"vulnerability disclosure policy" site:.*.*
"responsible disclosure" "hall of fame" OR "leaderboard"
"security vulnerability report" monetary reward
2. Security.txt Discovery
google
inurl:/.well-known/security.txt "bounty"
inurl:security.txt "contact" "bounty"
site:*.* security.txt "reward"
ext:txt "security" "acknowledgment" "bounty"
inurl:security.txt "hackerone" OR "bugcrowd"
3. Geographic-Specific Programs
google
site:.nl "responsible disclosure" bounty
site:.uk "bug bounty" program "reward"
site:.de "Schwachstellenmeldung" "Belohnung"
site:.fr "programme de bug bounty" "récompense"
site:.in "bug bounty" "security researcher"
site:.au "vulnerability disclosure" "payment"
site:.ca "security report" "compensation"
4. Platform-Specific Searches
google
"powered by bugcrowd" -site:bugcrowd.com
"powered by hackerone" "report vulnerability"
"submit report" "hackerone.com"
"synack" "red team" invitation
"intigriti" "researchers" "program"
"yeswehack" "scope" "bounty"
"openbugbounty" "disclosure"
5. Industry-Specific Programs
google
site:*.gov "vulnerability disclosure program"
site:*.mil "security" "report" "reward"
site:*.edu "bug bounty" "university"
site:*.org "responsible disclosure policy"
site:*.bank "security report" "reward"
site:*.finance "bug bounty" "program"
6. Advanced & Niche Dorks
google
intext:"we appreciate your security report" "reward"
"report a security vulnerability" "bitcoin" OR "crypto"
"bounty" "ETH" OR "BTC" "security report"
"private bug bounty" "invite-only"
"bug bounty" "scope" filetype:pdf
"security@*.*" intext:"reward for vulnerabilities"
7. Cloud & Hosting Platforms
google
site:*.github.io "security" "report"
site:*.herokuapp.com "responsible disclosure"
site:*.azurewebsites.net "vulnerability report"
site:*.cloudapp.azure.com "security"
site:*.aws "bug bounty" "program"
site:*.googleapis.com "disclosure"
🚀 How to Use Effectively
Basic Usage:
Copy a dork from the list above

Paste into Google Search

Review results carefully

READ THE PROGRAM POLICY before any testing

Pro Tips:
google
# Combine with site: operator
site:target.com "bug bounty" OR "responsible disclosure"

# Exclude irrelevant results
"bug bounty" -forum -blog -tutorial -job

# Search for specific file types
filetype:pdf "bug bounty program" scope

# Find program updates
"updated bug bounty program" 2024
Automation Tools:
bash
# Using curl with Google (be mindful of rate limits)
curl -A "Mozilla" "https://www.google.com/search?q=inurl:/bug-bounty"

# Using dork scanners
git clone https://github.com/shmilylty/dork-search
📈 Best Practices for Researchers
Do:
✅ Always read and understand the program's scope
✅ Follow the disclosure policy exactly
✅ Document your findings thoroughly
✅ Test only on in-scope targets
✅ Use separate testing accounts

Don't:
❌ Don't test on out-of-scope assets
❌ Don't use automated tools aggressively
❌ Don't violate rate limits
❌ Don't social engineer employees
❌ Don't exfiltrate or modify data

🔧 Contribution Guidelines
We welcome contributions! Please follow these steps:

Fork the repository

Test your dorks to ensure they work

Categorize your dorks appropriately

Submit a pull request with:

The dork

Brief description

Category suggestion

Format for New Dorks:
markdown
### [Category Name]
```google
your_dork_here "with" "operators"
Description: What this dork finds and any special notes.

text

## 🛡️ **Legal & Ethical Considerations**

### **Compliance:**
- Always comply with the Computer Fraud and Abuse Act (CFAA)
- Respect international laws (GDPR, etc.)
- Follow platform-specific terms of service

### **Ethical Framework:**
1. **Permission**: Only test where you have authorization
2. **Proportionality**: Use minimal necessary force
3. **Transparency**: Be clear about your actions
4. **Accountability**: Take responsibility for your testing

## 📊 **Statistics & Maintenance**

- **Last Updated**: January 2024
- **Total Dorks**: 50+ categorized queries
- **Categories**: 7 main categories
- **Update Frequency**: Quarterly reviews

## 🆘 **Support & Resources**

### **Learning Resources:**
- [HackerOne Hacktivity](https://hackerone.com/hacktivity)
- [Bugcrowd University](https://www.bugcrowd.com/hackers/bugcrowd-university/)
- [PortSwigger Web Security Academy](https://portswigger.net/web-security)

### **Community:**
- [Bug Bounty Forum](https://bugbountyforum.com/)
- [Reddit r/bugbounty](https://www.reddit.com/r/bugbounty/)
- [Discord Bug Bounty World](https://discord.gg/bugbounty)

## 📝 **License**

This project is licensed under the **Creative Commons Attribution-NonCommercial 4.0 International License**.

**You are free to:**
- Share — copy and redistribute the material
- Adapt — remix, transform, and build upon the material

**Under the following terms:**
- Attribution — You must give appropriate credit
- NonCommercial — You may not use the material for commercial purposes

For full license details, see [LICENSE](LICENSE) file.

---

## ⭐ **Star History**

[![Star History Chart](https://api.star-history.com/svg?repos=yourusername/bugbounty-dorks&type=Date)](https://star-history.com/#yourusername/bugbounty-dorks&Date)

**Remember:** The best tool is an ethical researcher with patience and persistence. Happy hunting! 🎯

---
*Maintained with ❤️ by the security community*  
*For educational and research purposes only*
