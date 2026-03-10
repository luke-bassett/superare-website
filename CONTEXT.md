# Site Context Notes

## Xfinity Blocking Issue (March 2026)

Several Xfinity users reported being unable to access superare.cc unless they disabled "Advanced Security" in their router settings.

### Root cause
- VirusTotal showed 1/95 vendors flagging the site as malicious: **Forcepoint ThreatSeeker**
- Cisco Talos showed the domain as "Unknown" reputation with no established content category
- The `.cc` TLD (Cocos Islands) is inherently less trusted by some filters than `.com`
- GitHub Pages config was fine: HTTPS enforced, custom domain set correctly

### Actions taken
- Submitted a **website unblocking request** to Xfinity/Comcast Service Policy Assurance (spa-noreply@spa.xfinity.com). Expected resolution: up to 3 business days.
- Forcepoint's own Site Lookup Tool was broken (rejected even google.com), so a direct false positive report was not possible.

### Remaining actions
- Submit a **Cisco Talos content categorization ticket** to establish the domain as Sports/Recreation, which will improve long-term reputation with other filters.
