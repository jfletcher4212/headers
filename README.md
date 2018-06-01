# Request Header Parser

#### User Story
1. I can get the IP address, preferred languages (from header Accept-Language) 
and system infos (from header User-Agent) for my device.

#### Usage
/api/whoami shows information about your IP address, language, and system software
There are two other routes, /api/whoami-short and /api/whoami-full that give less or more information, from an earlier version. These are not necessary, but can be used if desired.

#### Example Output
```
{
  "ipaddress": "208.100.253.123",
  "language": "en-US,en;q=0.9,pt-BR;q=0.8,pt;q=0.7",
  "software": "Mozilla/5.0 (Windows NT 6.1; Win64; x64) AppleWebKit/537.36 
  (KHTML, like Gecko) Chrome/66.0.3359.181 Safari/537.36"
}
```