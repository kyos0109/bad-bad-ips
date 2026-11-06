# BonkList

Daily IPv4 and IPv6 blocklists. Overlapping entries are deduplicated and adjacent addresses are merged only when the resulting CIDR covers exactly the same addresses.

| Profile | Downloads |
| --- | --- |
| Small | [IPv4](https://raw.githubusercontent.com/kyos0109/bad-bad-ips/data/small/ipv4.txt) / [IPv6](https://raw.githubusercontent.com/kyos0109/bad-bad-ips/data/small/ipv6.txt) |
| Light | [IPv4](https://raw.githubusercontent.com/kyos0109/bad-bad-ips/data/light/ipv4.txt) / [IPv6](https://raw.githubusercontent.com/kyos0109/bad-bad-ips/data/light/ipv6.txt) |
| Full | [IPv4](https://raw.githubusercontent.com/kyos0109/bad-bad-ips/data/full/ipv4.txt) / [IPv6](https://raw.githubusercontent.com/kyos0109/bad-bad-ips/data/full/ipv6.txt) |

Data version (UTC): 2026-11-06T02:07:10.820743Z

Aggregate license: [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Original source terms apply.

## Sources

- [drb-ra / C2IntelFeeds; raw data courtesy of Modat](https://raw.githubusercontent.com/drb-ra/C2IntelFeeds/master/feeds/IPC2s-30day.csv)

  <details><summary>Terms</summary>

  [CC BY-NC-SA 4.0](https://github.com/drb-ra/C2IntelFeeds#-license)

  Provided as-is for defensive and research purposes; no guarantee of accuracy or completeness. Infrastructure may be compromised, misattributed or reused. Validate before taking action.

  </details>

- [DShield.org / SANS Internet Storm Center](https://www.dshield.org/block.txt)

  <details><summary>Terms</summary>

  [CC BY-NC-SA 2.5](https://creativecommons.org/licenses/by-nc-sa/2.5/)

  (c) $year DShield.org
  some rights reserved. Details http://creativecommons.org/licenses/by-nc-sa/2.5/
  use on your own risk. No warranties implied.
  DShield.org Recommended Block List; some rights reserved. Use at your own risk. No warranties implied.

  </details>

- [stamparm / IPsum and its upstream contributors](https://raw.githubusercontent.com/stamparm/ipsum/master/levels/3.txt)

  <details><summary>Terms</summary>

  [Unlicense (maintainer explicitly permits data redistribution)](https://github.com/stamparm/ipsum/blob/master/LICENSE)

  Provided AS IS, without warranty of any kind; see the original Unlicense for the warranty and liability disclaimer.

  </details>

- [CZ.NIC Association / Turris Sentinel](https://view.sentinel.turris.cz/greylist-data/greylist-latest.csv)

  <details><summary>Terms</summary>

  [CC BY-NC-SA 4.0](https://view.sentinel.turris.cz/greylist-data/LICENSE.txt)

  For the terms of use see https://view.sentinel.turris.cz/greylist-data/LICENSE.txt
  Provided as is, without warranty; completeness, absence of legitimate traffic and protection from attacks are not guaranteed. CZ.NIC disclaims liability to the maximum extent permitted by applicable law.

  </details>

- [AbuseTrack (https://abusetrack.io), CC BY 4.0](https://abusetrack.io/api/v1/blocklist.txt?comments=0)

  <details><summary>Terms</summary>

  [CC BY 4.0](https://abusetrack.io/legal/feed-license)

  Provided as is, without warranty. Community reports may contain false positives, including shared or reassigned addresses.

  </details>

- [Carpathian, LLC (https://carpathian.ai/threat-intelligence)](https://api.carpathian.ai/public/threat-intel/blocklist.txt)

  <details><summary>Terms</summary>

  [CC BY 4.0](https://carpathian.ai/threat-intelligence)

  License: CC BY 4.0. Attribution: Carpathian, LLC
  CC BY 4.0: https://creativecommons.org/licenses/by/4.0/. Normalized, deduplicated and merged into exact CIDRs; no upstream endorsement implied.

  </details>

- [ReportedIP / Patrick Schlesinger (https://reportedip.com)](https://raw.githubusercontent.com/reportedip/reportedip-blacklist/main/blacklist-all.txt)

  <details><summary>Terms</summary>

  [CC BY 4.0](https://github.com/reportedip/reportedip-blacklist#license)

  Copyright (c) 2026 ReportedIP / Patrick Schlesinger
  Licensed under CC BY 4.0 - https://creativecommons.org/licenses/by/4.0/
  CC BY 4.0: https://creativecommons.org/licenses/by/4.0/. Provided as-is, without warranty; use at your own risk. The author is not liable for damages arising from use.

  </details>

- [ShadowWhisperer / IPs (https://github.com/ShadowWhisperer/IPs)](https://raw.githubusercontent.com/ShadowWhisperer/IPs/master/Lists/Threats)

  <details><summary>Terms</summary>

  [Unlicense](https://github.com/ShadowWhisperer/IPs/blob/master/LICENSE)

  Public-domain dedication under the Unlicense; provided AS IS without warranty or liability. Only the classified Threats feed is included.

  </details>

- [The Spamhaus Project / DROP](https://www.spamhaus.org/drop/drop_v4.json)

  <details><summary>Terms</summary>

  [Spamhaus DROP terms](https://www.spamhaus.org/blocklists/drop-fair-use-policy/)

  (c) 2026 The Spamhaus Project SLU (source timestamp: 1793929442). https://www.spamhaus.org/drop/terms/
  Original DROP data remains subject to Spamhaus terms; see upstream copyright and timestamp above.

  </details>

- [The Spamhaus Project / DROPv6](https://www.spamhaus.org/drop/drop_v6.json)

  <details><summary>Terms</summary>

  [Spamhaus DROP terms](https://www.spamhaus.org/blocklists/drop-fair-use-policy/)

  (c) 2026 The Spamhaus Project SLU (source timestamp: 1793870042). https://www.spamhaus.org/drop/terms/
  Original DROP data remains subject to Spamhaus terms; see upstream copyright and timestamp above.

  </details>

- [ffraud / IP Fraud Database](https://raw.githubusercontent.com/FFraud-com/ip-fraud-database/main/threat-ips/confirmed-abusive.csv)

  <details><summary>Terms</summary>

  [MIT (data)](https://github.com/FFraud-com/ip-fraud-database/blob/main/LICENSE)

  MIT License Copyright (c) 2026 ffraud Permission is hereby granted, free of charge, to any person obtaining a copy of this data and associated documentation files (the "Data"), to deal in the Data without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Data, and to permit persons to whom the Data is furnished to do so, subject to the following conditions: The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Data. THE DATA IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE DATA OR THE USE OR OTHER DEALINGS IN THE DATA.

  </details>

- [IPv64.net / Honeypot64](https://ipv64.net/blocklists/ipv64_blocklist_v4_v64.txt)

  <details><summary>Terms</summary>

  [CC BY 4.0](https://ipv64.net/docs/blocklists/)

  Daily IPv4 list. https://creativecommons.org/licenses/by/4.0/ Provided without warranty.

  </details>

- [Jacobrakai Foundation / jacobyoby](https://raw.githubusercontent.com/jacobyoby/honeypot-blocklist/main/blocklist.txt)

  <details><summary>Terms</summary>

  [CC0 1.0](https://github.com/jacobyoby/honeypot-blocklist#license)

  License     : CC0 1.0 Universal (public domain) — use freely
  Warranty    : none; provided as-is. Entries may involve dynamic or
  https://creativecommons.org/publicdomain/zero/1.0/ Provided as-is, without warranty.

  </details>

