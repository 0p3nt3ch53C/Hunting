# Hunting

## Scope Parsing

## Recon and Discovery

### Assets (multiple below)

[amass](https://github.com/owasp-amass/amass)

[assetfinder](https://github.com/tomnomnom/assetfinder)

### Web Spidering

[katana](https://github.com/projectdiscovery/katana)
++ JS Files, Source Code Scraping, URL Extracting

### IOT Search 

[shodan.io](shodan.io)

[censys.com](censys.com)

### WHOIS

[whoxy.com](https://whoxy.com)

### ASN

[bgo.he.net](https://bgo.he.net)

[dnschecker.org](https://dnschecker.org)

### Certificates

[crt.sh](https://crt.sh/)

[crt](https://github.com/cemulus/crt)

#### TLS Cipher Discovery

[tlsx](https://github.com/projectdiscovery/tlsx)

### DNS

#### Automated

##### Passive

[subfinder](https://github.com/projectdiscovery/subfinder)

[AnalyticsRelationships](https://github.com/Josue87/AnalyticsRelationships)

###### Multi-level DNS Discovery

[dsieve](https://github.com/trickest/dsieve)

###### Github Scanner for Subdomains

[github-subdomains](https://github.com/gwen001/github-subdomains)

##### Active

[dnsx](https://github.com/projectdiscovery/dnsx)

[dnscheck](https://github.com/six2dez/ipcdn) (was: [ipcdn](https://github.com/six2dez/ipcdn))

[Sublist3r](https://github.com/aboul3la/Sublist3r)

###### Subdomain Takeover Finder

[dnstake](https://github.com/pwnesia/dnstake)

####### Reference 

[can-i-take-over-xyz](https://github.com/EdOverflow/can-i-take-over-xyz)

###### Brute Force DNS Resolver

[puredns](https://github.com/d3mondev/puredns) (uses [massdns](https://github.com/blechschmidt/massdns))

###### Checking Content Delivery Network (CDN)

[cdncheck] https://github.com/projectdiscovery/cdncheck

###### HTTP Probing

[httpx](https://github.com/projectdiscovery/httpx)

###### Open Redirect Fuzzing 

[Oralyzer](https://github.com/r0075h3ll/Oralyzer)

###### URL Pattern Searching and Filtering

[rg](https://github.com/BurntSushi/ripgrep)

[gf](https://github.com/tomnomnom/gf)

[gf-patterns](https://github.com/1ndianl33t/Gf-Patterns)

##### Wayback URL / URL Extraction / Domain finder

[waymore](https://github.com/xnl-h4ck3r/waymore) (formerly [waybackurls](https://github.com/tomnomnom/waybackurls) and [gau](https://github.com/lc/gau))

[xnLinkFinder](https://github.com/xnl-h4ck3r/xnLinkFinder)

##### URL List Decluttering

[urless](https://github.com/xnl-h4ck3r/urless)

##### Brute Forcing

[aiodnsbrute](https://github.com/blark/aiodnsbrute)

#### Manual

##### Passive

[whoxy](https://www.whoxy.com/)

##### Active

[hakrevdns](https://github.com/hakluke/hakrevdns)

###### Web Application Firewall Fingerprinting

[wafw00f](https://github.com/EnableSecurity/wafw00f)

###### DNS Zone Transfer Checks

[dig](https://linux.die.net/man/1/dig)

###### Spoofability Check

[spoofcheck](https://github.com/MattKeeley/Spoofy)

#### DNS Verification

[dnsvalidator](https://github.com/vortexau/dnsvalidator)

### Email Address Discovery

[emailfinder](https://github.com/Josue87/EmailFinder)

[LeakSearch](https://github.com/JoelGMSec/LeakSearch)

### Metadata

[MetaFinder](https://github.com/Josue87/MetaFinder)

### API Leaks

[porch-pirate](https://github.com/MandConsultingGroup/porch-pirate)

[SwaggerSpy](https://github.com/UndeadSec/SwaggerSpy)

### Search Engines

#### Google Dorks

[dorks_hunter](https://github.com/six2dez/dorks_hunter)

### Github Dorks

[gitdorks_go](https://github.com/damit5/gitdorks_go)

### Secret Discovery

#### Github

[enumerepo](https://github.com/trickest/enumerepo)

[trufflehog](https://github.com/trufflesecurity/trufflehog)

[gitleaks](https://github.com/gitleaks/gitleaks)

### Website Misconfiguration

[misconfig-mapper](https://github.com/intigriti/misconfig-mapper)

### Browsing

#### Web Screenshots

[webscreenshot](https://github.com/maaaaz/webscreenshot)

#### Vulnerability Scanning

[nuclei](https://github.com/projectdiscovery/nuclei)

[nuclei geeknik](https://github.com/geeknik/the-nuclei-templates.git)
+ Subdomains takeover

#### Favicon based IP finder

[fav-up](https://github.com/pielco11/fav-up)

### Wordlist Creation

[pydictor](https://github.com/LandGrey/pydictor)

[cewl](https://github.com/digininja/CeWL)

[cewler](https://github.com/roys/cewler)

##### Precreated Wordlists

[assetnote-wordlists](https://wordlists.assetnote.io/)

[SecLists](https://github.com/danielmiessler/SecLists)

#### DNS Specific

[gotator](https://github.com/Josue87/gotator)

[ripgen](https://github.com/resyncgg/ripgen)

[regulator](https://github.com/cramppet/regulator)

## HTTP Tools / Custom Requests / Brute Forcing

### Web Tools

#### SSL Ceritificate Cipher Testing

[testssl](https://github.com/drwetter/testssl.sh)

#### CORS Web Testing

[Corsy](https://github.com/s0md3v/Corsy)

##### CORS 

[TheftFuzzer](https://github.com/lc/theftfuzzer)

#### CMS Detection

[CMSeeK](https://github.com/Tuhinshubhra/CMSeeK)

[wpscan](https://github.com/wpscanteam/wpscan)

#### HTTP 4XX Errors Testing

[nomore403](https://github.com/devploit/nomore403)

#### Web Cache Poisoning

[Web-Cache-Vulnerability-Scanner](https://github.com/Hackmanit/Web-Cache-Vulnerability-Scanner)

#### Active XXS for Gadgets

[ppmap](https://github.com/kleiton0x00/ppmap)

#### Active SSRF / External Interaction / Callback

[interactsh](https://github.com/projectdiscovery/interactsh)

### Requests / DNS / SSTI / Fuzzing / LFI Checks / Param Fuzzing

[ffuf](https://github.com/ffuf/ffuf)

## Network Scanning

### Active

[nmap](https://github.com/nmap/nmap)

[vulners](https://github.com/vulnersCom/nmap-vulners)

### Passive

[smap](https://github.com/s0md3v/Smap)

## Inscope Checking

[inscope](https://github.com/tomnomnom/hacks/tree/master/inscope)

## Notification

[notify](https://github.com/projectdiscovery/notify)

## SQL Injection Discovery and Exploitation

[SQLMap](https://github.com/sqlmapproject/sqlmap)

[ghauri](https://github.com/r0oth3x49/ghauri)

## Cross Site Scripting (XSS)

[dalfox](https://github.com/hahwul/dalfox) (formerly [gxss](https://github.com/KathanP19/Gxss))

## Carrage Return Line Feed (CRLF) Fuzzing

[crlfuzz](https://github.com/dwisiswant0/crlfuzz)

## JavaScript 

### Parsing Sourcemap or webpack

[sourcemapper](https://github.com/denandz/sourcemapper)

## Other

### IP Lookup

[whoisxmlapi API](https://www.whoisxmlapi.com/)

### IP Address Geolocation

[ipapi](ipapi.co)

### Brute Force Password spraying

[brutespray](https://github.com/x90skysn3k/brutespray)

### JavaScript Specific

[JSA](https://github.com/w9w/JSA)
++ URL Extraction

[LinkFinder](https://github.com/GerbenJavado/LinkFinder)

[getjswords](https://github.com/m4ll0k/BBTz)

#### Url Extracting

[jsluice](https://github.com/BishopFox/jsluice)

### Github Endpoints

[github-endpoints](https://gist.github.com/six2dez/d1d516b606557526e9a78d7dd49cacd3)

### ???

[ERLPopper](https://github.com/maikthulhu/ERLPopper)

### Depricated

[subjs](https://github.com/lc/subjs)

### Cloud / S3 Bucket Scanner

[S3Scanner](https://github.com/sa7mon/S3Scanner)

[cloud_enum](https://github.com/initstring/cloud_enum)

### Public Archived (outdated)

[subjack](https://github.com/haccer/subjack)

[aquatone](https://github.com/michenriksen/aquatone)

[ipcdn](https://github.com/six2dez/ipcdn)

### Attempts to cover everything in one tool (all in one, AIO)

[smartrecon](https://github.com/kh4sh3i/smartrecon)

[osmedeus](https://github.com/j3ssie/osmedeus)

All in one tool for XSS, Open Redirects, SSRF, CRLF, LFI, SQLi, SSL tests, SSTI, DNS zone transfers - [reconftw](https://github.com/six2dez/reconftw)

### Irrelevant

[proxychains-ng](https://github.com/rofl0r/proxychains-ng)

### Formatting

Diff for new items - [anew](https://github.com/tomnomnom/anew)

### Additional Tools

Burl (not anti-burl) - [burl](https://github.com/tomnomnom/burl)

HTTP Parameter Discovery - [arjun](https://github.com/s0md3v/Arjun)

Community Nuclei Templates - [cent](https://github.com/xm1k3/cent)

Connect to remote host and scrape certificates - [cero](https://github.com/glebarez/cero)

Active DNS Finding (requires project discovery API Key) - [chaos-client](https://github.com/projectdiscovery/chaos-client)

Pentesting - Command Injection - [commix](https://github.com/commixproject/commix)

Concurrent requests in CURL - [concurl](https://github.com/tomnomnom/concurl)

Password Cracking - [CrackMapExec](https://github.com/byt3bl33d3r/CrackMapExec)
 ++ Alternative [NexExec](https://github.com/Pennyw0rth/NetExec)

403 Finder and Brute Forcer - [dirdar](https://github.com/M4DM0e/DirDar)

HTML parser and santizer testing - [Dom-Explorer](https://github.com/yeswehack/Dom-Explorer)

Wordlist Generator for DNS - [DNSCewl](https://github.com/codingo/DNSCewl)

Wordlist Generator for DNS - [dnsgen](https://github.com/AlephNullSK/dnsgen)

Wordlist Generator for DNS with resolving - [altdns](https://github.com/infosec-au/altdns)

Multiple DNS Activities - [dnsrecon](https://github.com/darkoperator/dnsrecon)

Using different dns resolvers by trickest - [publicresolvers](https://github.com/root4loot/publicresolvers)

Validating DNS with resolvers - [dnsvalidator](https://github.com/vortexau/dnsvalidator)

Another tool for validating DNS Resolvers [dnsvalidator2](https://github.com/frost19k/DNSValidator)

Remove CDNs from DNS URLs - [exclude-cdn](https://github.com/Cgboal/exclude-cdn)

Active Content Discovery tool - [feroxbuster](https://github.com/epi052/feroxbuster)
    ++ [Documentation](https://epi052.github.io/feroxbuster-docs/docs/)

Fetching URL's quickly - [fff](https://github.com/tomnomnom/fff)

Find domains quickly - [findomain](https://github.com/Findomain/Findomain)

Retrieve data about and for Javascript files - [getJS](https://github.com/003random/getJS)

Directory / dns / s3 / gcs / vhost / fuzz / tftp brute force - [gobuster](https://github.com/OJ/gobuster)

Multi-threaded password sprayer - [gorgo](https://github.com/pry0cc/gorgo)

Fast Web Spider written in Go - [gospider](https://github.com/jaeles-project/gospider)

Website Screenshot utility in Go - [gowitness](https://github.com/sensepost/gowitness)

JSON grepping tool - [gron](https://github.com/tomnomnom/gron)

GO Web crawler for gathering URL's and js file locations - [hakrawler](https://github.com/hakluke/hakrawler)

Take a list of domains and probe for working http/https - [httprobe](https://github.com/tomnomnom/httprobe)

Web server (self hosted and SaaS) for interactsh - [interactsh-web](https://github.com/projectdiscovery/interactsh-web)

[Interlace](https://github.com/codingo/Interlace)

[jaeles](https://github.com/jaeles-project/jaeles)

[kiterunner](https://github.com/assetnote/kiterunner)

[kxss](https://github.com/tomnomnom/hacks/tree/6fd7870f20ab4ea96781f20d74fff714e0354046/kxss)

[leaky-paths](https://github.com/ayoubfathi/leaky-paths)

Massive IP Portscanner - [masscan](https://github.com/robertdavidgraham/masscan)

[medusa](https://github.com/jmk-foofus/medusa)

Fetching lots of URL's - [meg](https://github.com/tomnomnom/meg)

Go NMAP Alternative - [naabu](https://github.com/projectdiscovery/naabu)

A fuzzer for detecting open redirect vulns - [OpenRedireX](https://github.com/devanshbatham/OpenRedireX)

Mining URLs from dark corners of Web Archives - [ParamSpider](https://github.com/devanshbatham/ParamSpider)

[qsreplace](https://github.com/tomnomnom/qsreplace)

[responder.py](https://github.com/lgandx/Responder)

[RustScan](https://github.com/RustScan/RustScan)

[scrying](https://github.com/nccgroup/scrying)

[shuffledns](https://github.com/projectdiscovery/shuffledns)

[TheFTFuzzer](https://github.com/lc/theftfuzzer)

Bruteforceing Passwords - [thc-hydra](https://github.com/vanhauser-thc/thc-hydra)

Find Secrets in sourcecode - [TruffleHog](https://github.com/trufflesecurity/trufflehog)

Firewall for ubuntu - [ufw](https://wiki.ubuntu.com/UncomplicatedFirewall)

nmap alternative - [unimap](https://github.com/Edu4rdSHL/unimap)

Search Javascript Files for API Keys - [Mantra](https://github.com/brosck/mantra)

Secrets Scanning by Checkmarx - [2ms](https://github.com/checkmarx/2ms/)
