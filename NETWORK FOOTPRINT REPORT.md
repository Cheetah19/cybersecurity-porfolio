 NETWORK FOOTPRINT REPORT
============================================================

Analyst:        Pratyaksha Mishra
Analysis Date:  July 20, 2026
Engagement:     Passive Reconnaissance of haldirams.com
Methodology:    DNS > WHOIS > Certificates > Technology


------------------------------------------------------------
 1. TARGET SUMMARY
------------------------------------------------------------

Domain:          haldirams.com
Description:     Traditional Indian sweets, snacks, and restaurant retail chain
Reason chosen:   Realistic mid-market retail web infrastructure for security analysis
Scope:           Passive reconnaissance only — public sources
                 only, no scanning, no probing, no interaction
                 with target infrastructure


------------------------------------------------------------
 2. EXECUTIVE SUMMARY
------------------------------------------------------------

Haldirams.com operates on custom corporate web infrastructure fronted by Cloudflare proxy protection with email managed via Google Workspace. Multiple regional and administrative subdomains were discovered via certificate transparency logs, mapping out a long-standing digital footprint. WHOIS records indicate a 30-year-old domain originally registered through Network Solutions with corporate administrative contacts in New Delhi.


------------------------------------------------------------
 3. DNS RECORDS
------------------------------------------------------------

A record(s):       Cloudflare-owned CDN and edge routing IP ranges
MX record(s):      aspmx.l.google.com, alt1.aspmx.l.google.com — Google Workspace
NS record(s):      Authoritative name servers managed via commercial DNS providers
TXT record(s):     v=spf1 include:_spf.google.com — Google mail exchanger verification
Other notable:     Standard retail subdomain mapping across primary customer-facing entry points


------------------------------------------------------------
 4. WHOIS
------------------------------------------------------------

Registrar:         Network Solutions, LLC
Registration date: 23 May 1996
Expiration date:   24 May 2030
Registrant:        Corporate administrative management entities (New Delhi, India)
Contact email:     Associated corporate administrative contact
Domain age:        30 years (healthy indicator for an established brand)


------------------------------------------------------------
 5. CERTIFICATE TRANSPARENCY
------------------------------------------------------------

Total certs issued: Dozens of historical and active entries
CA used most:       DigiCert / commercial enterprise CAs
Subdomains found:   - www.haldirams.com
                     - international.haldirams.com
                     - Regional portals and administrative endpoints
Notable findings:   Historical wildcard and multi-year certificate issuance logs track decades of infrastructure evolution


------------------------------------------------------------
 6. TECHNOLOGY PROFILE
------------------------------------------------------------

Server software:   Cloudflare (reverse proxy / edge server)
CMS/framework:     Custom corporate web architecture
Analytics:         Standard enterprise web tracking and marketing pixels
Hosting provider:  Cloud-distributed content delivery network hosting
Other tech:        Modern frontend scripts and enterprise security headers


------------------------------------------------------------
 7. OBSERVATIONS
------------------------------------------------------------

The target exhibits high stability and longevity with a 30-year continuous domain history while effectively securing its origin infrastructure behind modern content delivery networks. The extensive certificate transparency logs provide deep historical insight into how the retail brand's web presence expanded across regional and international sectors.


------------------------------------------------------------
 8. RECOMMENDATIONS
------------------------------------------------------------

If briefing the target's security team:
  [ ] Periodically audit all identified regional and administrative subdomains to ensure non-production endpoints are not leaking internal configurations.
  [ ] Ensure strict multi-factor authentication controls are enforced across all customer portals and administrative login pages.
  [ ] Verify that origin web servers remain strictly restricted to accept traffic exclusively through the Cloudflare edge proxy layer.


============================================================
 END OF REPORT
============================================================
