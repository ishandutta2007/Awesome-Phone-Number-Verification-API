# Awesome Phone Number Verification API 📱⚡

[![Awesome](https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github)](https://github.com/ishandutta2007/Awesome-Awesome-Awesome)
<a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/ishandutta2007/Awesome-Phone-Number-Verification-API/pulls)
<a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>

> **A curated developer ecosystem guide to top SaaS platforms, HLR lookup APIs, fraud identity signals, and open-source libraries for Phone Number Verification, Carrier Identification & Validation.**

![Phone Number Verification API Banner](assets/banner.svg)

---

## 💡 Overview & Category Highlights

This repository tracks notable **SaaS/API platforms** and **open-source projects** for **Phone Number Verification**. These services validate phone numbers, determine line type (mobile, landline, VoIP), identify carriers via live HLR lookups, check reachability, and provide fraud prevention and identity signals for modern onboarding workflows.

- 🏢 **SaaS Leaders**: Twilio Lookup, Telesign, Sinch, Vonage Number Insight, Infobip, Abstract API, NumVerify, Loqate, Bird, and Truecaller.
- 🔓 **Open-Source Standard**: Google’s `libphonenumber` remains the gold standard for offline parsing, formatting, E.164 normalization, and metadata validation across Java, C++, Python, JavaScript, Swift, and Go.

---

## 📑 Table of Contents

- [📊 Sector Market Intelligence](#-sector-market-intelligence)
- [🏢 SaaS / Hosted Platforms](#-saas--hosted-platforms)
- [🔓 Open-Source GitHub Projects](#-open-source-github-projects)
- [🤝 How to Contribute](#-how-to-contribute)
- [🔒 Disclaimer & Compliance](#-disclaimer--compliance)
- [📈 Star History](#-star-history)

---

## 📊 Sector Market Intelligence

> **Market Size & Structure**: The global Phone Number Verification & Identity API market is estimated at **~$3.8 Billion (2026)** and is projected to expand at a CAGR of **~14.5%** over the next decade, driven by rising SMS fraud, SIM-swap attacks, and mandatory Multi-Factor Authentication (MFA). 
>
> **Market Fragmentation**: The market is **moderately fragmented with strong enterprise consolidation tendencies**. Category giants like Twilio, Sinch, Infobip, and Vonage dominate global enterprise telecom infrastructure ("winner-takes-most" tier), while specialized API providers (NumVerify, Abstract API, Telesign) capture high-margin developer and niche verification segments.

---

## 🏢 SaaS / Hosted Platforms

Below is a comparative lookup matrix of commercial SaaS phone number validation APIs, sorted by **Company Size / Valuation (Descending)**:

| Product Name | Description | Pricing (Starting Tier) | Free Tier Limits | Company Size / Valuation (Est.) |
| :--- | :--- | :--- | :--- | :--- |
| 🔴 **[Twilio Lookup](https://www.twilio.com/docs/lookup)** | Comprehensive phone number intelligence API providing line type, carrier, caller name, and risk signals. | Basic format free; Data packages start at $0.007–$0.008/req (Pay-as-you-go). | Free trial account with ~$15.00 test credit allowance. | **~$12.5 Billion** (Public Market Cap: TWLO) |
| 🟠 **[Vonage Number Insight](https://www.vonage.com/communications-apis/number-insight/)** | Real-time carrier lookup, reachability, and fraud score API powered by Vonage network suite. | Pay-as-you-go starting at $0.0011 per lookup request. | Free trial with €2.00 / $2.00 initial credit upon registration. | **~$6.2 Billion** (Acquired by Ericsson) |
| 🟣 **[Truecaller Verify](https://www.truecaller.com/)** | Identity verification leveraging Truecaller’s global phone identity graph & spam reputation signals. | Commercial paid plans based on successful verification volume. | Sandbox access available upon contacting developer support. | **~$1.5 Billion** (Public Market Cap: TRUE-B) |
| 🔵 **[Sinch Number Verify / Lookup](https://www.sinch.com/)** | Carrier identification, network status, and verification APIs inside Sinch CPaaS ecosystem. | Pay-as-you-go starting at $0.008 per lookup request. | Developer trial with $2.00 test credit & 5 verified number cap. | **~$1.2 Billion** (Public Market Cap: SINCH) |
| 🟢 **[Infobip Number Lookup](https://www.infobip.com/)** | Global HLR lookup and mobile operator validation for enterprise deliverability and security. | Pay-as-you-go custom volume quotes (~$0.005–$0.01 per lookup). | 60-day platform free trial with sandbox evaluation credits. | **~$1.0 Billion+** (Private Unicorn Valuation) |
| 🟡 **[Telesign](https://www.telesign.com/)** | Enterprise phone identity & digital identity platform focused on fraud risk scoring & global HLR. | Pay-as-you-go per-request pricing (destination dependent). | Free trial account with $5.00 in test credit. | **~$800 Million** (Enterprise Business Valuation) |
| 🟤 **[Loqate Phone Validation](https://www.loqate.com/)** | Global address and phone data quality validation APIs from Loqate (GBG group). | Pay-as-you-go credit bundle starting at £50 (~$65) min purchase. | 45-day free trial with complimentary evaluation credits. | **~$750 Million** (Part of GBG Group) |
| ⚪ **[MessageBird / Bird Lookup](https://www.bird.com/)** | Carrier, line type, and number portability lookup tools within the Bird communications platform. | Pay-as-you-go per lookup; volume contract tiers for enterprises. | Free developer account with test credits (e.g. 10 free lookup credits). | **~$600 Million** (Private Tech Valuation) |
| 🟦 **[Abstract API](https://www.abstractapi.com/phone-validation-api)** | Simple REST API for international phone formatting, country detection, line type, and carrier data. | Starter plan starts at $17.00/month (billed annually) for 10k req. | Free plan includes 100 requests per month for non-commercial use. | **~$15 Million** (Bootstrapped / Early Stage) |
| 🟧 **[NumVerify](https://numverify.com/)** | High-volume RESTful phone validation API for basic carrier and line type checks. | Basic paid plan starts at $9.99/month for 5,000 requests. | Free lifetime plan includes 100 requests per month. | **~$10 Million** (APILayer Product Line) |

---

## 🔓 Open-Source GitHub Projects

Open-source phone validation relies heavily on Google's `libphonenumber` metadata rules engine for client-side and server-side validation. Commercial HLR lookups are combined with these open libraries for cost optimization.

The list below is sorted by **GitHub Star Count (Descending)**:

1. 🌟 **[Google libphonenumber](https://github.com/google/libphonenumber)**  
   [![GitHub_Stars](https://img.shields.io/github/stars/google/libphonenumber?style=social&color=white)](https://github.com/google/libphonenumber/stargazers)  
   The industry-standard library for parsing, formatting, and validating international phone numbers (Java, C++, JavaScript).

2. 🌟 **[marmelroy / PhoneNumberKit](https://github.com/marmelroy/PhoneNumberKit)**  
   [![GitHub_Stars](https://img.shields.io/github/stars/marmelroy/PhoneNumberKit?style=social&color=white)](https://github.com/marmelroy/PhoneNumberKit/stargazers)  
   Swift framework for parsing, formatting, and validating international phone numbers inspired by Google's `libphonenumber`.

3. 🌟 **[daviddrysdale / python-phonenumbers](https://github.com/daviddrysdale/python-phonenumbers)**  
   [![GitHub_Stars](https://img.shields.io/github/stars/daviddrysdale/python-phonenumbers?style=social&color=white)](https://github.com/daviddrysdale/python-phonenumbers/stargazers)  
   Popular Python port of Google's `libphonenumber` library supporting Python 3.x with server-side validation capabilities.

4. 🌟 **[catamphetamine / libphonenumber-js](https://github.com/catamphetamine/libphonenumber-js)**  
   [![GitHub_Stars](https://img.shields.io/github/stars/catamphetamine/libphonenumber-js?style=social&color=white)](https://github.com/catamphetamine/libphonenumber-js/stargazers)  
   Lightweight JavaScript phone number parser & formatter for browser and Node.js environments.

5. 🌟 **[gookit / validate](https://github.com/gookit/validate)**  
   [![GitHub_Stars](https://img.shields.io/github/stars/gookit/validate?style=social&color=white)](https://github.com/gookit/validate/stargazers)  
   Go data validation library with full support for international phone number regex, format verification, and E.164 sanitization.

6. 🌟 **[twcclegg / libphonenumber-csharp](https://github.com/twcclegg/libphonenumber-csharp)**  
   [![GitHub_Stars](https://img.shields.io/github/stars/twcclegg/libphonenumber-csharp?style=social&color=white)](https://github.com/twcclegg/libphonenumber-csharp/stargazers)  
   C# .NET port of Google's `libphonenumber` for backend ASP.NET Core applications.

7. 🌟 **[grantila / awesome-phonenumber](https://github.com/grantila/awesome-phonenumber)**  
   [![GitHub_Stars](https://img.shields.io/github/stars/grantila/awesome-phonenumber?style=social&color=white)](https://github.com/grantila/awesome-phonenumber/stargazers)  
   Zero-dependency TypeScript/JavaScript phone number library wrapping Google's libphonenumber metadata.

8. 🌟 **[ttacon / libphonenumber (Go)](https://github.com/ttacon/libphonenumber)**  
   [![GitHub_Stars](https://img.shields.io/github/stars/ttacon/libphonenumber?style=social&color=white)](https://github.com/ttacon/libphonenumber/stargazers)  
   Go port of Google's `libphonenumber` providing parsing and validation primitives for Golang services.

---

## 🤝 How to Contribute

We welcome community contributions! Please follow these guidelines:

1. 🍴 Fork the repository.
2. 📝 Add or edit entries in `README.md` following the tabular or starred list format.
3. 🔗 Ensure all SaaS pricing and GitHub_Stars_Badges link to valid pages.
4. 🚀 Submit a Pull Request (PR) with a brief summary of additions.

---

## 🔒 Disclaimer & Compliance

- **Community Curated**: This list is maintained for educational and architectural reference only and does not constitute endorsement.
- **Telecom Compliance**: Commercial HLR, carrier lookup, and identity APIs process sensitive subscriber data. Developers must ensure compliance with global data privacy regulations (**GDPR, TCPA, CCPA**) and adhere to telecom provider policies.

---

## 📈 Star History

[![Star History Chart](https://star-history.dera.page/svg?repos=ishandutta2007/Awesome-Phone-Number-Verification-API&type=date&legend=top-left)](https://star-history.dera.page/#ishandutta2007/Awesome-Phone-Number-Verification-API&type=date&legend=top-left)

---

**Made with ❤️ for developers building fraud-resistant phone authentication workflows.**
