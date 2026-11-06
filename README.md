# BonkList | IP外面站

壞 IP，外面站。

Daily IPv4 and IPv6 blocklists. Adjacent addresses are merged only when the CIDR covers exactly the same addresses.

| Profile | Coverage | Lists |
| --- | --- | --- |
| Small | Spamhaus DROP and C2IntelFeeds | [IPv4](small/ipv4.txt) · [IPv6](small/ipv6.txt) |
| Light | Small plus Turris and IPsum | [IPv4](light/ipv4.txt) · [IPv6](light/ipv6.txt) |
| Full | All enabled sources | [IPv4](full/ipv4.txt) · [IPv6](full/ipv6.txt) |

Data version (UTC): 2026-11-06T01:45:10.038527Z

## Sources

- drb-ra / C2IntelFeeds; raw data courtesy of Modat
- DShield.org / SANS Internet Storm Center
- stamparm / IPsum and its upstream contributors
- CZ.NIC Association / Turris Sentinel
- AbuseTrack (https://abusetrack.io), CC BY 4.0
- Carpathian, LLC (https://carpathian.ai/threat-intelligence)
- ReportedIP / Patrick Schlesinger (https://reportedip.com)
- ShadowWhisperer / IPs (https://github.com/ShadowWhisperer/IPs)
- The Spamhaus Project
- ffraud / IP Fraud Database
- IPv64.net / Honeypot64
- Jacobrakai Foundation / jacobyoby

## Sources and terms

https://creativecommons.org/licenses/by-nc-sa/4.0/
CC BY-NC-SA 4.0 for the aggregate adaptation; original source terms and notices retained

Processing: normalize CIDRs, union, remove duplicates/contained networks and exactly merge adjacency.
No independent corroboration or maliciousness score is inferred from source overlap.

## c2intel_30day

- Source: https://raw.githubusercontent.com/drb-ra/C2IntelFeeds/master/feeds/IPC2s-30day.csv
- Attribution: drb-ra / C2IntelFeeds; raw data courtesy of Modat
- Original terms: CC BY-NC-SA 4.0 (https://github.com/drb-ra/C2IntelFeeds#-license)
- Fetched: 2026-11-06T01:44:59.161786Z
- Last-Modified: unknown
- Upstream metadata (JSON): {}

- Source notice: Provided as-is for defensive and research purposes; no guarantee of accuracy or completeness. Infrastructure may be compromised, misattributed or reused. Validate before taking action.

## dshield

- Source: https://www.dshield.org/block.txt
- Attribution: DShield.org / SANS Internet Storm Center
- Original terms: CC BY-NC-SA 2.5 (https://creativecommons.org/licenses/by-nc-sa/2.5/)
- Fetched: 2026-11-06T01:44:59.292543Z
- Last-Modified: Fri, 06 Nov 2026 01:29:34 GMT
- Upstream metadata (JSON): {"comments": ["#", "#   DShield.org Recommended Block List", "#    (c) $year DShield.org", "#   some rights reserved. Details http://creativecommons.org/licenses/by-nc-sa/2.5/", "#   use on your own risk. No warranties implied.", "#   primary URL: https://feeds.dshield.org/block.txt", "#     PGP Sign.: https://feeds.dshield.org/block.txt.asc", "#", "#   comments: systems@isc.sans.edu", "#    updated: 2026-11-06T01:30:34.708553", "#", "#    This list summarizes the top 20 attacking class C (/24) subnets", "#   over the last three days. The number of 'attacks' indicates the", "#   number of targets reporting scans from this subnet.", "#", "#", "#    Columns (tab delimited):", "#", "#    (1) start of netblock", "#    (2) end of netblock", "#    (3) subnet (/24 for class C)", "#    (4) number of targets scanned", "#    (5) name of Network", "#    (6) Country", "#    (7) contact email address", "#", "#    If a range is assigned to multiple users, the first one is listed.", "#"], "upstream_updated": "2026-11-06T01:30:34.708553"}

- Source notice: DShield.org Recommended Block List; some rights reserved. Use at your own risk. No warranties implied.

## ipsum_3

- Source: https://raw.githubusercontent.com/stamparm/ipsum/master/levels/3.txt
- Attribution: stamparm / IPsum and its upstream contributors
- Original terms: Unlicense (maintainer explicitly permits data redistribution) (https://github.com/stamparm/ipsum/blob/master/LICENSE)
- Fetched: 2026-11-06T01:44:59.446344Z
- Last-Modified: unknown
- Upstream metadata (JSON): {}

- Source notice: Provided AS IS, without warranty of any kind; see the original Unlicense for the warranty and liability disclaimer.

## turris

- Source: https://view.sentinel.turris.cz/greylist-data/greylist-latest.csv
- Attribution: CZ.NIC Association / Turris Sentinel
- Original terms: CC BY-NC-SA 4.0 (https://view.sentinel.turris.cz/greylist-data/LICENSE.txt)
- Fetched: 2026-11-06T01:44:59.534207Z
- Last-Modified: Thu, 05 Nov 2026 23:07:02 GMT
- Upstream metadata (JSON): {"comments": ["# For the terms of use see https://view.sentinel.turris.cz/greylist-data/LICENSE.txt"]}

- Source notice: Provided as is, without warranty; completeness, absence of legitimate traffic and protection from attacks are not guaranteed. CZ.NIC disclaims liability to the maximum extent permitted by applicable law.

## abusetrack

- Source: https://abusetrack.io/api/v1/blocklist.txt?comments=0
- Attribution: AbuseTrack (https://abusetrack.io), CC BY 4.0
- Original terms: CC BY 4.0 (https://abusetrack.io/legal/feed-license)
- Fetched: 2026-11-06T01:45:00.567415Z
- Last-Modified: unknown
- Upstream metadata (JSON): {}

- Source notice: Provided as is, without warranty. Community reports may contain false positives, including shared or reassigned addresses.

## carpathian

- Source: https://api.carpathian.ai/public/threat-intel/blocklist.txt
- Attribution: Carpathian, LLC (https://carpathian.ai/threat-intelligence)
- Original terms: CC BY 4.0 (https://carpathian.ai/threat-intelligence)
- Fetched: 2026-11-06T01:45:01.044274Z
- Last-Modified: Fri, 06 Nov 2026 01:06:01 GMT
- Upstream metadata (JSON): {"comments": ["# Carpathian Threat Intelligence blocklist", "# Source: https://carpathian.ai/threat-intelligence", "# License: CC BY 4.0. Attribution: Carpathian, LLC", "# Generated: 2026-11-06T01:06:00", "# Entries: 1835", "# Plain list format: Palo Alto EDL, FortiGate external threat feed, pfBlockerNG, CrowdSec.", "#"]}

- Source notice: CC BY 4.0: https://creativecommons.org/licenses/by/4.0/. Normalized, deduplicated and merged into exact CIDRs; no upstream endorsement implied.

## reportedip

- Source: https://raw.githubusercontent.com/reportedip/reportedip-blacklist/main/blacklist-all.txt
- Attribution: ReportedIP / Patrick Schlesinger (https://reportedip.com)
- Original terms: CC BY 4.0 (https://github.com/reportedip/reportedip-blacklist#license)
- Fetched: 2026-11-06T01:45:01.420662Z
- Last-Modified: unknown
- Upstream metadata (JSON): {"comments": ["# ReportedIP Blacklist - All IPs", "# https://reportedip.com", "#", "# Copyright (c) 2026 ReportedIP / Patrick Schlesinger", "# Licensed under CC BY 4.0 - https://creativecommons.org/licenses/by/4.0/", "#", "# Daily snapshot, new addresses appear after 48 hours.", "# Live data: WordPress https://reportedip.com/products/wordpress-plugin/", "#            Linux     https://reportedip.com/products/linux-agent/", "#            API       https://reportedip.com/products/api/", "#", "# Generated: 2026-11-05", "# Total IPs: 13889", "#"]}

- Source notice: CC BY 4.0: https://creativecommons.org/licenses/by/4.0/. Provided as-is, without warranty; use at your own risk. The author is not liable for damages arising from use.

## shadowwhisperer

- Source: https://raw.githubusercontent.com/ShadowWhisperer/IPs/master/Lists/Threats
- Attribution: ShadowWhisperer / IPs (https://github.com/ShadowWhisperer/IPs)
- Original terms: Unlicense (https://github.com/ShadowWhisperer/IPs/blob/master/LICENSE)
- Fetched: 2026-11-06T01:45:01.535288Z
- Last-Modified: unknown
- Upstream metadata (JSON): {}

- Source notice: Public-domain dedication under the Unlicense; provided AS IS without warranty or liability. Only the classified Threats feed is included.

## spamhaus_v4

- Source: https://www.spamhaus.org/drop/drop_v4.json
- Attribution: The Spamhaus Project
- Original terms: Spamhaus DROP terms (https://www.spamhaus.org/blocklists/drop-fair-use-policy/)
- Fetched: 2026-11-06T01:45:01.663879Z
- Last-Modified: Thu, 05 Nov 2026 16:35:14 GMT
- Upstream metadata (JSON): {"copyright": "(c) 2026 The Spamhaus Project SLU", "records": 1763, "size": 107580, "terms": "https://www.spamhaus.org/drop/terms/", "timestamp": 1793927642, "type": "metadata"}

- Source notice: Original DROP data remains subject to Spamhaus terms; see upstream copyright and timestamp above.

## spamhaus_v6

- Source: https://www.spamhaus.org/drop/drop_v6.json
- Attribution: The Spamhaus Project
- Original terms: Spamhaus DROP terms (https://www.spamhaus.org/blocklists/drop-fair-use-policy/)
- Fetched: 2026-11-06T01:45:01.754795Z
- Last-Modified: Tue, 03 Nov 2026 20:04:51 GMT
- Upstream metadata (JSON): {"copyright": "(c) 2026 The Spamhaus Project SLU", "records": 90, "size": 5676, "terms": "https://www.spamhaus.org/drop/terms/", "timestamp": 1793870042, "type": "metadata"}

- Source notice: Original DROP data remains subject to Spamhaus terms; see upstream copyright and timestamp above.

## ffraud

- Source: https://raw.githubusercontent.com/FFraud-com/ip-fraud-database/main/threat-ips/confirmed-abusive.csv
- Attribution: ffraud / IP Fraud Database
- Original terms: MIT (data) (https://github.com/FFraud-com/ip-fraud-database/blob/main/LICENSE)
- Fetched: 2026-11-06T01:45:01.819880Z
- Last-Modified: unknown
- Upstream metadata (JSON): {"rows_before_filter": 1651503}

- Source notice: MIT License Copyright (c) 2026 ffraud Permission is hereby granted, free of charge, to any person obtaining a copy of this data and associated documentation files (the "Data"), to deal in the Data without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Data, and to permit persons to whom the Data is furnished to do so, subject to the following conditions: The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Data. THE DATA IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE DATA OR THE USE OR OTHER DEALINGS IN THE DATA.

## honeypot64_v4

- Source: https://ipv64.net/blocklists/ipv64_blocklist_v4_v64.txt
- Attribution: IPv64.net / Honeypot64
- Original terms: CC BY 4.0 (https://ipv64.net/docs/blocklists/)
- Fetched: 2026-11-06T01:45:09.158346Z
- Last-Modified: Fri, 06 Nov 2026 00:07:08 GMT
- Upstream metadata (JSON): {}

- Source notice: Daily IPv4 list. https://creativecommons.org/licenses/by/4.0/ Provided without warranty.

## jacobrakai

- Source: https://raw.githubusercontent.com/jacobyoby/honeypot-blocklist/main/blocklist.txt
- Attribution: Jacobrakai Foundation / jacobyoby
- Original terms: CC0 1.0 (https://github.com/jacobyoby/honeypot-blocklist#license)
- Fetched: 2026-11-06T01:45:09.972002Z
- Last-Modified: unknown
- Upstream metadata (JSON): {"comments": ["#", "# jacobrakai-honeypot-blocklist", "#", "# Description : IP addresses observed attacking live honeypot sensors", "#               (SSH, FTP, telnet, MySQL, VNC). Honeypot-confirmed from", "#               my own logs, not inferred from third-party data.", "# Maintainer  : jacobrakai", "# Homepage    : https://jacobrakai.org/feed/", "# Contact     : jacob@jacobrakai.org (delisting / false-positive reports)", "# Inclusion   : three tiers, all requiring attack activity within the", "#               last 30 days (entries age out automatically):", "#               - credential (335 IPs): connected to a decoy service and", "#                 submitted login credentials repeatedly (50+ attempts).", "#               - scanner (177 IPs): submitted no credentials but probed", "#                 at abusive volume \u2014 1000+ connection events in-window", "#                 (~33+/day sustained; the measured casual-scanner tail", "#                 tops out well under half that threshold).", "#               - loader (33 IPs): fetched a file into a honeypot session", "#                 (wget/curl dropper) or uploaded one over SFTP/SCP. No", "#                 volume floor: one captured payload is the evidence.", "# Exclusions  : private/reserved ranges and known benign internet-survey", "#               scanners (Censys, Rapid7 Sonar, Shadowserver, Shodan,", "#               BinaryEdge) are filtered out before publication \u2014 from", "#               ALL tiers.", "# Entries     : 545 (335 credential, 177 scanner, 33 loader)", "# Updated     : 2026-11-06T01:00:02Z (refreshed hourly)", "# License     : CC0 1.0 Universal (public domain) \u2014 use freely", "# Warranty    : none; provided as-is. Entries may involve dynamic or", "#               reassigned IPs and age out after 30 days of inactivity.", "#"]}

- Source notice: https://creativecommons.org/publicdomain/zero/1.0/ Provided as-is, without warranty.

