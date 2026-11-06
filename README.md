# BonkList

Daily IPv4 and IPv6 blocklists. Overlapping entries are deduplicated and adjacent addresses are merged only when the resulting CIDR covers exactly the same addresses.

| Profile | What the list contains | Downloads |
| --- | --- | --- |
| Small | Spamhaus DROP networks and IP addresses from the C2IntelFeeds 30-day feed. | [IPv4](small/ipv4.txt) / [IPv6](small/ipv6.txt) |
| Light | Small plus addresses from the Turris Sentinel greylist and IPsum Level 3. | [IPv4](light/ipv4.txt) / [IPv6](light/ipv6.txt) |
| Full | All enabled feeds, including the Light list, honeypot reports and filtered FFraud records. | [IPv4](full/ipv4.txt) / [IPv6](full/ipv6.txt) |

Data version (UTC): 2026-11-06T01:55:49.776471Z

Aggregate license: [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Original source terms apply.

<details><summary>License notices</summary>

- drb-ra / C2IntelFeeds; raw data courtesy of Modat (c2intel_30day): Provided as-is for defensive and research purposes; no guarantee of accuracy or completeness. Infrastructure may be compromised, misattributed or reused. Validate before taking action.
- DShield.org / SANS Internet Storm Center (dshield): (c) $year DShield.org some rights reserved. Details http://creativecommons.org/licenses/by-nc-sa/2.5/ use on your own risk. No warranties implied. DShield.org Recommended Block List; some rights reserved. Use at your own risk. No warranties implied.
- stamparm / IPsum and its upstream contributors (ipsum_3): Provided AS IS, without warranty of any kind; see the original Unlicense for the warranty and liability disclaimer.
- CZ.NIC Association / Turris Sentinel (turris): For the terms of use see https://view.sentinel.turris.cz/greylist-data/LICENSE.txt Provided as is, without warranty; completeness, absence of legitimate traffic and protection from attacks are not guaranteed. CZ.NIC disclaims liability to the maximum extent permitted by applicable law.
- AbuseTrack (https://abusetrack.io), CC BY 4.0 (abusetrack): Provided as is, without warranty. Community reports may contain false positives, including shared or reassigned addresses.
- Carpathian, LLC (https://carpathian.ai/threat-intelligence) (carpathian): License: CC BY 4.0. Attribution: Carpathian, LLC CC BY 4.0: https://creativecommons.org/licenses/by/4.0/. Normalized, deduplicated and merged into exact CIDRs; no upstream endorsement implied.
- ReportedIP / Patrick Schlesinger (https://reportedip.com) (reportedip): Copyright (c) 2026 ReportedIP / Patrick Schlesinger Licensed under CC BY 4.0 - https://creativecommons.org/licenses/by/4.0/ CC BY 4.0: https://creativecommons.org/licenses/by/4.0/. Provided as-is, without warranty; use at your own risk. The author is not liable for damages arising from use.
- ShadowWhisperer / IPs (https://github.com/ShadowWhisperer/IPs) (shadowwhisperer): Public-domain dedication under the Unlicense; provided AS IS without warranty or liability. Only the classified Threats feed is included.
- The Spamhaus Project (spamhaus_v4): (c) 2026 The Spamhaus Project SLU (source timestamp: 1793927642). https://www.spamhaus.org/drop/terms/ Original DROP data remains subject to Spamhaus terms; see upstream copyright and timestamp above.
- The Spamhaus Project (spamhaus_v6): (c) 2026 The Spamhaus Project SLU (source timestamp: 1793870042). https://www.spamhaus.org/drop/terms/ Original DROP data remains subject to Spamhaus terms; see upstream copyright and timestamp above.
- ffraud / IP Fraud Database (ffraud): MIT License Copyright (c) 2026 ffraud Permission is hereby granted, free of charge, to any person obtaining a copy of this data and associated documentation files (the "Data"), to deal in the Data without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Data, and to permit persons to whom the Data is furnished to do so, subject to the following conditions: The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Data. THE DATA IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE DATA OR THE USE OR OTHER DEALINGS IN THE DATA.
- IPv64.net / Honeypot64 (honeypot64_v4): Daily IPv4 list. https://creativecommons.org/licenses/by/4.0/ Provided without warranty.
- Jacobrakai Foundation / jacobyoby (jacobrakai): License     : CC0 1.0 Universal (public domain) — use freely Warranty    : none; provided as-is. Entries may involve dynamic or https://creativecommons.org/publicdomain/zero/1.0/ Provided as-is, without warranty.

</details>

## Sources

- [drb-ra / C2IntelFeeds; raw data courtesy of Modat](https://raw.githubusercontent.com/drb-ra/C2IntelFeeds/master/feeds/IPC2s-30day.csv) ([CC BY-NC-SA 4.0](https://github.com/drb-ra/C2IntelFeeds#-license))
- [DShield.org / SANS Internet Storm Center](https://www.dshield.org/block.txt) ([CC BY-NC-SA 2.5](https://creativecommons.org/licenses/by-nc-sa/2.5/))
- [stamparm / IPsum and its upstream contributors](https://raw.githubusercontent.com/stamparm/ipsum/master/levels/3.txt) ([Unlicense (maintainer explicitly permits data redistribution)](https://github.com/stamparm/ipsum/blob/master/LICENSE))
- [CZ.NIC Association / Turris Sentinel](https://view.sentinel.turris.cz/greylist-data/greylist-latest.csv) ([CC BY-NC-SA 4.0](https://view.sentinel.turris.cz/greylist-data/LICENSE.txt))
- [AbuseTrack (https://abusetrack.io), CC BY 4.0](https://abusetrack.io/api/v1/blocklist.txt?comments=0) ([CC BY 4.0](https://abusetrack.io/legal/feed-license))
- [Carpathian, LLC (https://carpathian.ai/threat-intelligence)](https://api.carpathian.ai/public/threat-intel/blocklist.txt) ([CC BY 4.0](https://carpathian.ai/threat-intelligence))
- [ReportedIP / Patrick Schlesinger (https://reportedip.com)](https://raw.githubusercontent.com/reportedip/reportedip-blacklist/main/blacklist-all.txt) ([CC BY 4.0](https://github.com/reportedip/reportedip-blacklist#license))
- [ShadowWhisperer / IPs (https://github.com/ShadowWhisperer/IPs)](https://raw.githubusercontent.com/ShadowWhisperer/IPs/master/Lists/Threats) ([Unlicense](https://github.com/ShadowWhisperer/IPs/blob/master/LICENSE))
- [The Spamhaus Project](https://www.spamhaus.org/drop/drop_v4.json) ([Spamhaus DROP terms](https://www.spamhaus.org/blocklists/drop-fair-use-policy/))
- [The Spamhaus Project](https://www.spamhaus.org/drop/drop_v6.json) ([Spamhaus DROP terms](https://www.spamhaus.org/blocklists/drop-fair-use-policy/))
- [ffraud / IP Fraud Database](https://raw.githubusercontent.com/FFraud-com/ip-fraud-database/main/threat-ips/confirmed-abusive.csv) ([MIT (data)](https://github.com/FFraud-com/ip-fraud-database/blob/main/LICENSE))
- [IPv64.net / Honeypot64](https://ipv64.net/blocklists/ipv64_blocklist_v4_v64.txt) ([CC BY 4.0](https://ipv64.net/docs/blocklists/))
- [Jacobrakai Foundation / jacobyoby](https://raw.githubusercontent.com/jacobyoby/honeypot-blocklist/main/blocklist.txt) ([CC0 1.0](https://github.com/jacobyoby/honeypot-blocklist#license))
