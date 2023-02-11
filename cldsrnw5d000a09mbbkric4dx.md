# New Stealthy Backdoor Saitama: The Latest Weapon in Iranian Cyber Espionage Campaign

Researchers from Malwarebytes and Fortinet FortiGuard Labs have [**discovered**](https://www.malwarebytes.com/blog/threat-intelligence/2022/05/apt34-targets-jordan-government-using-new-saitama-backdoor) a new spear-phishing campaign that has targeted Jordan's foreign ministry, deploying a stealthy backdoor named Saitama. The campaign has been attributed to Iranian cyber espionage threat actor APT34, also known as OilRig, Helix Kitten, and Cobalt Gypsy. The group is known for its targeted phishing attacks against the telecom, government, defense, oil, and financial sectors in the Middle East and North Africa.

The phishing message contained a weaponized Microsoft Excel document, which upon opening prompted victims to enable macros and execute a malicious Visual Basic Application (VBA) macro. This macro then dropped the malware payload, establishing persistence by adding a scheduled task that repeated every four hours. Saitama leverages the DNS protocol for its command-and-control (C2) communications to disguise its traffic and employs a "[**finite-state machine**](https://en.wikipedia.org/wiki/Finite-state_machine)" approach to executing commands received from the C2 server.

In the final stage, the results of the command execution are sent back to the C2 server in the form of a DNS request, with the exfiltrated data built into the request. According to Fred Gutierrez, a researcher at Fortinet, this malware does not delete itself and relies on the Excel macro to create persistence.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1675684964693/ac877948-d3bd-4fe0-a776-793761a79206.jpeg align="center")

This latest discovery highlights the growing threat of Iranian cyber espionage and the sophisticated tactics being employed by APT34. Earlier this February, ESET [**tied**](https://cyberhub.hashnode.dev/the-evolution-of-iranian-apt-threats-uncovering-the-marlin-malware-backdoor) the group's long-run intelligence-gathering operation against diplomatic organizations, technology companies, and medical organizations in Israel, Tunisia, and the United Arab Emirates as a testament to their persistence and determination.

Thank you for reading our blog today. We hope you found the information helpful and informative. If you enjoyed this blog, be sure to follow us on [**Twitter**](https://twitter.com/areyysharma), [**Instagram**](https://www.instagram.com/official_cyber_hub/), [**Linkedin**](https://www.linkedin.com/in/technical-human/), [**GitHub**](https://github.com/pushkarsharma23), [**Website**](https://officialcyberhub.wixsite.com/cyberhub), and [**Youtube**](https://www.youtube.com/@OfficialCyberHub) for more interesting content and updates. If you have any questions or comments, please feel free to reach out to us. We would love to hear from you. Don't forget to share this with your friends and family who may also find this information useful. Thank you for your support and stay tuned for more!