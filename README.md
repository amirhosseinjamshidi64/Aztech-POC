# Description
- So far, I have worked on the Aztech modem router model DSL5005EN, and if I have the opportunity in the future, I will work on other models as well. 
# Aztech routers Vulns (POC)
- In the mentioned version, I was able to find a 0DAY hardware-level bug and write a proof of concept (POC).
- Which I initially published on the [exploit-db](https://www.exploit-db.com/exploits/52093) website.
## How to use
You can just Run it with this single command:
```bash
python Exploit.py --ip TARGET_IP --password PASSWORD
```
! Replace TARGET_IP and PASSWORD

# CVE-2025-56241
[NVD](https://nvd.nist.gov/vuln/detail/CVE-2025-56241)
[Advisory](https://gist.github.com/amirhosseinjamshidi64/cca123a0dda5a17f3708ffc2dd2a7a45)
