# Breach List Database
A meta-database collecting resources that compile lists of (security) incidents

## Thematic Breach Lists

* AI
  * [When Your AI Becomes a Target: AI Security Incidents and Best Practices](https://ojs.aaai.org/index.php/AAAI/article/view/30347)
  * [OWASP Top 10 for Agentic Apps - ASI Agentic Exploits & Incidents Master List](https://github.com/almogbhl/www-project-top-10-for-large-language-model-applications/blob/b2ab40aebc9d9cac5601775cbffd69ac462a6bd9/initiatives/agent_security_initiative/ASI%20Agentic%20Exploits%20%26%20Incidents/ASI_Agentic_Exploits_Incidents.md)
* Caching - Scott Piper's [Security Incidents From Caching](https://github.com/0xdabbad00/security_incidents_from_caching)
* Cloud
    * [Chris Farris' breaches.cloud](https://breaches.cloud)
    * Cloud Service Providers - [CloudVulnDB](https://cloudvulndb.org)
    * [ramimac's AWS Customer Security Incidents](https://github.com/ramimac/aws-customer-security-incidents)
    * S3 Bucket Leaks - [nagwww's s3-leaks](https://github.com/nagwww/s3-leaks)
* Cryptocurrency 
    * [magoo's Blockchain Graveyard](https://magoo.github.io/Blockchain-Graveyard/), [blocksec-incidents](https://github.com/m4xx101/blocksec-incidents)
    * [Defi Llama](https://defillama.com/hacks)
* Destroyed by Breach - [Adrian Sanabria's Destroyed by Breach](https://docs.google.com/spreadsheets/d/15CTPcgZQenWKDLDTQ2ibveUM4i7Of_n20TzdTi23xcg/edit#gid=0) [tweet](https://twitter.com/sawaba/status/1553938672667566082)
* Identity based attacks - [Push Security](https://pushsecurity.com/blog/identity-attacks-in-the-wild/)
* Ransomware 
    * [RansomLook](https://www.ransomlook.io/recent)
    * [Ransomware.live](https://ransomware.live/#/)
* Stegonography - [lucacav/steg-in-the-wild](https://github.com/lucacav/steg-in-the-wild)
* Supply Chain
    * [CNCF's Supply Chain Security Compromises](https://github.com/cncf/tag-security/tree/main/community/catalog/compromises)
    * [OpenSSF's Catalog of Supply Chain Compromises ](https://docs.google.com/spreadsheets/d/1DhIl2Khh4ugZWX3M9zJgJoO-M2w42aKQzKjD7_-R8q8/edit?gid=0#gid=0)
    * [tstromberg's OSS Supply Chain Attack Compendium](https://github.com/tstromberg/supplychain-attack-data)
* Machine Learning - [MITRE Adversarial ML Threat Matrix Case Studies](https://github.com/mitre/advmlthreatmatrix)
* -2015 [Repository of Industrial Security Incidents](https://www.risidata.com/Database)
* -2010 [Web Hacking Incident Database](http://projects.webappsec.org/w/page/13246995/Web-Hacking-Incident-Database)

## Geographic Breach Lists

These lists are scoped to a specific country or region. They differ from generic lists above in their geographic filter, and vary widely in selectivity—from comprehensive aggregators of every disclosed incident to highly curated national-impact lists.

| List | Geography | Style | Notes |
|------|-----------|-------|-------|
| [VSec.dk / Incidents](https://vsec.dk/incidents/) | 🇩🇰 Denmark | Curated, open-source | ~37 incidents since 2012. Includes DDoS, ICS/OT, supply chain. High threshold—national impact or critical infrastructure. Backed by [GitHub repo](https://github.com/VSecDK/VSec-CTI-League). |
| [RecentBreaches.com / US](https://recentbreaches.com/us) | 🇺🇸 USA | Filing + claim aggregator | 14,119+ incidents. Separates **confirmed filings** (state AG, SEC 8-K, CISA) from **ransomware claims** (leak-site allegations). Very low threshold. Strong epistemic transparency. |
| [AusDataBreach.org](https://ausdatabreach.org/) | 🇦🇺 Australia | Breach tracker | Hundreds of incidents. Three-tier severity (MINOR/SERIOUS/SEVERE). Very low threshold—includes 3-record breaches. Broad sector coverage. |
| [FrenchBreaches.com](https://frenchbreaches.com/) | 🇫🇷 France | Leak + breach tracker | Labels incidents **Confirmée** (victim-confirmed) vs **Revendiquée (credible)** (threat-actor claimed). Lists exposed data types per incident. Uniquely includes attempted attacks. |
| [IndianBreaches.com](https://indianbreaches.com/) | 🇮🇳 India | Transparency initiative | Indexes publicly visible threat-actor posts. Legal disclaimer: does not acquire or host stolen data. |
| [CanadaBreaches.ca](https://canadabreaches.ca/) | 🇨🇦 Canada | Breach tracker | JS-rendered; details could not be retrieved. |
| [EURepoC.eu / Database](https://eurepoc.eu/database/) | 🇪🇺 EU | Academic/policy dataset | Research-grade. Tracks EU Cyber Diplomacy Toolbox application. High selectivity (policy-significant incidents only). Static dataset versions for reproducibility. Not a real-time consumer tracker. |

For a detailed analysis of inclusion criteria and a framework for building new geographic lists, see [geographic-breach-lists-analysis.md](geographic-breach-lists-analysis.md).

## Generic Breach Lists

* [Wikipedia List of Data Breaches](https://en.wikipedia.org/wiki/List_of_data_breaches)
* [Wikipedia List of Security Hacking Incidents](https://en.wikipedia.org/wiki/List_of_security_hacking_incidents)
* [Have I Been Pwned's Pwned Websites](https://haveibeenpwned.com/PwnedWebsites)
* [Foobarsec](https://foobarsec.com/)
* [Data Breach DB](https://databreachdb.com/) [paper](https://dl.acm.org/doi/pdf/10.1145/3439873)
* [Privacy Right Clearinghouse](https://privacyrights.org/data-breaches)
* [CSIS's Significant Cyber Incidents](https://www.csis.org/programs/strategic-technologies-program/significant-cyber-incidents)
* [CSIDB](https://www.csidb.net/)
* [Board Cybersecurity Incident Tracker (8-Ks)](https://www.board-cybersecurity.com/incidents/tracker/)

## Misc

* [magoo's analysis of every CA breach notification in 2017](https://medium.com/starting-up-security/learning-from-californias-data-breaches-f63920820626)
* [magoo's collection of breach blog posts](https://scrty.io/breach-blog-posts)

h/t [Shellsharks](https://shellsharks.com/infosec-tools#breaches-incidents--leaks), which I've aggregated in 
