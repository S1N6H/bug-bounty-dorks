# 🚨 BugBountyDork – Google Dorks List (2025 Edition)

**Website:** [hackwithsingh.com](https://www.hackwithsingh.com)  
**Instagram:** [@hackwithsingh](https://instagram.com/hackwithsingh)



## ✅ What’s Inside

**`dorks.txt`** – a single file containing curated Google dork strings aimed at revealing security policies, program disclosures, reward pages, and more.



## 🛠 Usage Instructions

1. Open `dorks.txt`.  
2. Copy any query and paste it into Google (or your recon tool).  
3. Review results to identify security pages, bounty programs, policy docs, and contact channels.  
4. Refine searches as needed to surface hidden assets.



## 📜 The Dorks

inurl:/security-policy "bounty" ext:pdf
intext:"vulnerability disclosure program" site:gov.*
inurl:/.well-known/security ext:txt "contact" -hackerone -bugcrowd
site:*.*.* inurl:/responsible-disclosure "swag"
"security@example.com" inurl:security ext:txt -github
site:*.uk intext:"security reward" "£"
site:*.in "responsible disclosure" ("₹" | "INR")
site:*.br /seguranca recompensa
site:*.de "bug-bounty-programm" euro
site:*.au "security vulnerability" AUD
"powered by hackerone" -site:hackerone.com
inurl:bug-bounty-platform "submit report"
"private program" inurl:security researcher
site:*.edu "vulnerability disclosure" hall-of-fame
site:*.bank intext:"security report" compensation
"cryptocurrency" inurl:bug-bounty "BTC"
intext:"minimum reward" vulnerability -site:responsibledisclosure.*
inurl:bounty intext:("€500+" | "$1000+")
intext:"gift card" "security researcher"
"we value security researchers" inurl:acknowledgements
intext:"thank you for your report" bounty
inurl:/security ext:aspx "report a vulnerability"
intitle:"vulnerability management" intext:reward
filetype:md "disclosure policy" swag
inurl:coordinated-vulnerability-disclosure "compensation"
"submit flaw report" inurl:trust
intext:"responsible disclosure" -inurl:legal -inurl:contact
site:*.*.nl "beloning" -site:government.nl


## 🤝 Contributing

Have a dork that performs well? Improve accuracy? Feel free to:

1. **Fork** the repo  
2. Add your lines to `dorks.txt`  
3. **Submit a Pull Request**  


## 📄 License & Contact

**License:** MIT © 2025 Harinder Singh ([@hackwithsingh](https://instagram.com/hackwithsingh))  
**Contact & Tutorials:** Visit [hackwithsingh.com](https://www.hackwithsingh.com)  



