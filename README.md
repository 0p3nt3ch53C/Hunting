# Hunting

## Scope Parsing

### Wordlist Creation

## Recon and Discovery

### Web Spidering

[katana](https://github.com/projectdiscovery/katana)

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

### DNS

#### Automated

##### Passive

##### Active

##### Brute Forcing

[aiodnsbrute](https://github.com/blark/aiodnsbrute)

#### Manual

##### Passive

[whoxy](https://www.whoxy.com/)

##### Active

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

### Wordlist Creation

## HTTP Tools / Custom Requests / Brute Forcing

### Web Tools

#### SSL Ceritificate Cipher Testing

[testssl](https://github.com/drwetter/testssl.sh)

#### HTTP 4XX Errors Testing

[nomore403](https://github.com/devploit/nomore403)

#### Web Cache Poisoning

[Web-Cache-Vulnerability-Scanner](https://github.com/Hackmanit/Web-Cache-Vulnerability-Scanner)

#### Active XXS for Gadgets

[ppmap](https://github.com/kleiton0x00/ppmap)

#### Active SSRF / External Interaction

[interactsh](https://github.com/projectdiscovery/interactsh)

### Requests / DNS / SSTI / Fuzzing / LFI Checks / Param Fuzzing

[ffuf](https://github.com/ffuf/ffuf)


## Inscope Checking

[inscope](https://github.com/tomnomnom/hacks/tree/master/inscope)

## Notification

[notify](https://github.com/projectdiscovery/notify)


## Other Repo Lists:

 Amass
 anew
 anti-burl
 aquatone
 Arjun
 assetfinder
 axiom
 axiom-dockerfiles
 cent
 cero
 chaos-client
 commix
 concurl
 Corsy
 CrackMapExec
 crlfuzz
 dalfox
 dirdar
 DNSCewl
 dnsgen
 dnsrecon
 dns resolvers by trickest
 dnsvalidator
 dnsx
 Docker
 ERLPopper
 exclude-cdn
 feroxbuster
 fff
 findomain
 gau
 gauplus
 getJS
 gf
 Gf-Patterns
 github-endpoints
 github-subdomains
 Go
 gobuster
 google-chrome
 gorgo
 gospider
 gowitness
 gron
 Gxss
 hakrawler
 hakrevdns
 httprobe
 httpx
 interactsh-client
 Interlace
 ipcdn
 jaeles
 kiterunner
 kxss
 leaky-paths
 LinkFinder
 masscan
 massdns
 medusa
 meg
 naabu
 nmap
 nuclei
 OpenRedireX
 ParamSpider
 phantomjs
 proxychains-ng
 puredns
 qsreplace
 responder.py
 RustScan
 s3scanner
 scrying
 SecLists
 shuffledns
 six2dez dns permutations
 sqlmap
 subfinder
 subjack
 subjs
 testssl
 thc-hydra
 tlsx
 trufflehog
 ufw
 unimap
 wafw00f
 waybackurls
 wpscan


## Subdomains

- Passive ([subfinder](https://github.com/projectdiscovery/subfinder) and [github-subdomains](https://github.com/gwen001/github-subdomains))
- Certificate transparency ([crt](https://github.com/cemulus/crt))
- NOERROR subdomain discovery ([dnsx](https://github.com/projectdiscovery/dnsx), more info [here](https://www.securesystems.de/blog/enhancing-subdomain-enumeration-ents-and-noerror/))
- Bruteforce ([puredns](https://github.com/d3mondev/puredns))
- Permutations ([Gotator](https://github.com/Josue87/gotator), [ripgen](https://github.com/resyncgg/ripgen) and [regulator](https://github.com/cramppet/regulator))
- JS files & Source Code Scraping ([katana](https://github.com/projectdiscovery/katana))
- DNS Records ([dnsx](https://github.com/projectdiscovery/dnsx))
- Google Analytics ID ([AnalyticsRelationships](https://github.com/Josue87/AnalyticsRelationships))
- TLS handshake ([tlsx](https://github.com/projectdiscovery/tlsx))
- Recursive search ([dsieve](https://github.com/trickest/dsieve)).
- Subdomains takeover ([nuclei](https://github.com/projectdiscovery/nuclei))
- DNS takeover ([dnstake](https://github.com/pwnesia/dnstake))
- DNS Zone Transfer ()
- Cloud checkers ([S3Scanner](https://github.com/sa7mon/S3Scanner) and [cloud_enum](https://github.com/initstring/cloud_enum))

## Hosts

- IP info ([whoisxmlapi API](https://www.whoisxmlapi.com/))
- CDN checker ([ipcdn](https://github.com/six2dez/ipcdn))
- WAF checker ([wafw00f](https://github.com/EnableSecurity/wafw00f))
- Port Scanner (Active with [nmap](https://github.com/nmap/nmap) and passive with [smap](https://github.com/s0md3v/Smap))
- Port services vulnerability checks ([vulners](https://github.com/vulnersCom/nmap-vulners))
- Password spraying ([brutespray](https://github.com/x90skysn3k/brutespray))
- Geolocalization info (ipapi.co)

## Webs

- Web Prober ([httpx](https://github.com/projectdiscovery/httpx))
- Web screenshoting ([nuclei](https://github.com/projectdiscovery/nuclei))
- Web templates scanner ([nuclei](https://github.com/projectdiscovery/nuclei) and [nuclei geeknik](https://github.com/geeknik/the-nuclei-templates.git))
- CMS Scanner ([CMSeeK](https://github.com/Tuhinshubhra/CMSeeK))
- Url extraction ([gau](https://github.com/lc/gau),[waymore](https://github.com/xnl-h4ck3r/waymore), [katana](https://github.com/projectdiscovery/katana), [github-endpoints](https://gist.github.com/six2dez/d1d516b606557526e9a78d7dd49cacd3) and [JSA](https://github.com/w9w/JSA))
- URL patterns Search and filtering ([urless](https://github.com/xnl-h4ck3r/urless), [gf](https://github.com/tomnomnom/gf) and [gf-patterns](https://github.com/1ndianl33t/Gf-Patterns))
- Favicon Real IP ([fav-up](https://github.com/pielco11/fav-up))
- Javascript analysis ([subjs](https://github.com/lc/subjs), [JSA](https://github.com/w9w/JSA), [xnLinkFinder](https://github.com/xnl-h4ck3r/xnLinkFinder), [getjswords](https://github.com/m4ll0k/BBTz), [mantra](https://github.com/MrEmpy/mantra), [jsluice](https://github.com/BishopFox/jsluice))
- Sourcemap JS extraction ([sourcemapper](https://github.com/denandz/sourcemapper))
- Passwords dictionary creation ([pydictor](https://github.com/LandGrey/pydictor))

## Vulnerability checks

- XSS ([dalfox](https://github.com/hahwul/dalfox))
- Open redirect ([Oralyzer](https://github.com/r0075h3ll/Oralyzer))
- SSRF (headers [interactsh](https://github.com/projectdiscovery/interactsh))
- CRLF ([crlfuzz](https://github.com/dwisiswant0/crlfuzz))
- Cors ([Corsy](https://github.com/s0md3v/Corsy))
- SQLi Check ([SQLMap](https://github.com/sqlmapproject/sqlmap) and [ghauri](https://github.com/r0oth3x49/ghauri))




