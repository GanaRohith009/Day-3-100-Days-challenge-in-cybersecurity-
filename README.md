# Day-3-100-Days-challenge-in-cybersecurity-
## 📅 Day 3: Reconnaissance & Basic OSINT (WHOIS)

**Focus:** Investigating suspect domains and understanding the foundations of Open Source Intelligence.

### Summary
On Day 3, I transitioned from passive observation to active reconnaissance by investigating a live threat: a fake crypto investment website promising unrealistic returns (a typical HYIP scam indicator).

The goal was to move beyond assumption and use technical tools to gather hard data on the target.

### Tools Used
* **WHOIS Lookup:** (Terminal command or web-based tools like DomainTools/ICANN).

### The Process & Key Findings

Instead of guessing about the website's legitimacy, I performed a WHOIS query to inspect the domain's registration record.

```bash
# Example command structure
whois suspicious-website-example.com
