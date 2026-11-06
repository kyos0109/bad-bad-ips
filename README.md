# BonkList

Daily IPv4 and IPv6 blocklists. Overlapping entries are deduplicated and adjacent addresses are merged only when the resulting CIDR covers exactly the same addresses.

| Profile | Downloads |
| --- | --- |
| Small | [IPv4](https://raw.githubusercontent.com/kyos0109/bad-bad-ips/data/small/ipv4.txt) / [IPv6](https://raw.githubusercontent.com/kyos0109/bad-bad-ips/data/small/ipv6.txt) |
| Light | [IPv4](https://raw.githubusercontent.com/kyos0109/bad-bad-ips/data/light/ipv4.txt) / [IPv6](https://raw.githubusercontent.com/kyos0109/bad-bad-ips/data/light/ipv6.txt) |
| Full | [IPv4](https://raw.githubusercontent.com/kyos0109/bad-bad-ips/data/full/ipv4.txt) / [IPv6](https://raw.githubusercontent.com/kyos0109/bad-bad-ips/data/full/ipv6.txt) |

Updated 2026-11-06 (UTC) · [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)

## Sources

<details><summary>C2IntelFeeds</summary>

drb-ra / C2IntelFeeds; raw data courtesy of Modat · [Feed](https://raw.githubusercontent.com/drb-ra/C2IntelFeeds/master/feeds/IPC2s-30day.csv) · [CC BY-NC-SA 4.0](https://github.com/drb-ra/C2IntelFeeds#-license)

Provided as-is for defensive and research purposes; no guarantee of accuracy or completeness. Infrastructure may be compromised, misattributed or reused. Validate before taking action.

</details>

<details><summary>DShield</summary>

DShield.org / SANS Internet Storm Center · [Feed](https://www.dshield.org/block.txt) · [CC BY-NC-SA 2.5](https://creativecommons.org/licenses/by-nc-sa/2.5/)

(c) $year DShield.org
some rights reserved. Details http://creativecommons.org/licenses/by-nc-sa/2.5/
use on your own risk. No warranties implied.
DShield.org Recommended Block List; some rights reserved. Use at your own risk. No warranties implied.

</details>

<details><summary>IPsum Level 3</summary>

stamparm / IPsum and its upstream contributors · [Feed](https://raw.githubusercontent.com/stamparm/ipsum/master/levels/3.txt) · [Unlicense (maintainer explicitly permits data redistribution)](https://github.com/stamparm/ipsum/blob/master/LICENSE)

Provided AS IS, without warranty of any kind; see the original Unlicense for the warranty and liability disclaimer.

</details>

<details><summary>Turris Sentinel</summary>

CZ.NIC Association / Turris Sentinel · [Feed](https://view.sentinel.turris.cz/greylist-data/greylist-latest.csv) · [CC BY-NC-SA 4.0](https://view.sentinel.turris.cz/greylist-data/LICENSE.txt)

For the terms of use see https://view.sentinel.turris.cz/greylist-data/LICENSE.txt
Provided as is, without warranty; completeness, absence of legitimate traffic and protection from attacks are not guaranteed. CZ.NIC disclaims liability to the maximum extent permitted by applicable law.

</details>

<details><summary>AbuseTrack</summary>

AbuseTrack (https://abusetrack.io), CC BY 4.0 · [Feed](https://abusetrack.io/api/v1/blocklist.txt?comments=0) · [CC BY 4.0](https://abusetrack.io/legal/feed-license)

Provided as is, without warranty. Community reports may contain false positives, including shared or reassigned addresses.

</details>

<details><summary>Carpathian</summary>

Carpathian, LLC (https://carpathian.ai/threat-intelligence) · [Feed](https://api.carpathian.ai/public/threat-intel/blocklist.txt) · [CC BY 4.0](https://carpathian.ai/threat-intelligence)

License: CC BY 4.0. Attribution: Carpathian, LLC
CC BY 4.0: https://creativecommons.org/licenses/by/4.0/. Normalized, deduplicated and merged into exact CIDRs; no upstream endorsement implied.

</details>

<details><summary>ReportedIP</summary>

ReportedIP / Patrick Schlesinger (https://reportedip.com) · [Feed](https://raw.githubusercontent.com/reportedip/reportedip-blacklist/main/blacklist-all.txt) · [CC BY 4.0](https://github.com/reportedip/reportedip-blacklist#license)

Copyright (c) 2026 ReportedIP / Patrick Schlesinger
Licensed under CC BY 4.0 - https://creativecommons.org/licenses/by/4.0/
CC BY 4.0: https://creativecommons.org/licenses/by/4.0/. Provided as-is, without warranty; use at your own risk. The author is not liable for damages arising from use.

</details>

<details><summary>ShadowWhisperer</summary>

ShadowWhisperer / IPs (https://github.com/ShadowWhisperer/IPs) · [Feed](https://raw.githubusercontent.com/ShadowWhisperer/IPs/master/Lists/Threats) · [Unlicense](https://github.com/ShadowWhisperer/IPs/blob/master/LICENSE)

Public-domain dedication under the Unlicense; provided AS IS without warranty or liability. Only the classified Threats feed is included.

</details>

<details><summary>Spamhaus DROP</summary>

The Spamhaus Project · [Feed](https://www.spamhaus.org/drop/drop_v4.json) · [Spamhaus DROP terms](https://www.spamhaus.org/blocklists/drop-fair-use-policy/)

(c) 2026 The Spamhaus Project SLU (source timestamp: 1793897042). https://www.spamhaus.org/drop/terms/
Original DROP data remains subject to Spamhaus terms; see upstream copyright and timestamp above.

</details>

<details><summary>Spamhaus DROPv6</summary>

The Spamhaus Project · [Feed](https://www.spamhaus.org/drop/drop_v6.json) · [Spamhaus DROP terms](https://www.spamhaus.org/blocklists/drop-fair-use-policy/)

(c) 2026 The Spamhaus Project SLU (source timestamp: 1793871842). https://www.spamhaus.org/drop/terms/
Original DROP data remains subject to Spamhaus terms; see upstream copyright and timestamp above.

</details>

<details><summary>FFraud</summary>

ffraud / IP Fraud Database · [Feed](https://raw.githubusercontent.com/FFraud-com/ip-fraud-database/main/threat-ips/confirmed-abusive.csv) · [MIT (data)](https://github.com/FFraud-com/ip-fraud-database/blob/main/LICENSE)

MIT License Copyright (c) 2026 ffraud Permission is hereby granted, free of charge, to any person obtaining a copy of this data and associated documentation files (the "Data"), to deal in the Data without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Data, and to permit persons to whom the Data is furnished to do so, subject to the following conditions: The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Data. THE DATA IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE DATA OR THE USE OR OTHER DEALINGS IN THE DATA.

</details>

<details><summary>Honeypot64</summary>

IPv64.net / Honeypot64 · [Feed](https://ipv64.net/blocklists/ipv64_blocklist_v4_v64.txt) · [CC BY 4.0](https://ipv64.net/docs/blocklists/)

Daily IPv4 list. https://creativecommons.org/licenses/by/4.0/ Provided without warranty.

</details>

<details><summary>Jacobrakai Honeypot</summary>

Jacobrakai Foundation / jacobyoby · [Feed](https://raw.githubusercontent.com/jacobyoby/honeypot-blocklist/main/blocklist.txt) · [CC0 1.0](https://github.com/jacobyoby/honeypot-blocklist#license)

License     : CC0 1.0 Universal (public domain) — use freely
Warranty    : none; provided as-is. Entries may involve dynamic or
https://creativecommons.org/publicdomain/zero/1.0/ Provided as-is, without warranty.

</details>

