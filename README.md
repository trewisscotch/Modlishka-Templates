# Modlishka-Templates
Modlishka is a powerful and flexible HTTP reverse proxy. It implements an entirely new and interesting approach of handling browser-based HTTP traffic flow, which allows to transparently proxy multi-domain destination traffic, both TLS and non-TLS, over a single domain, without a requirement of installing any additional certificate on the client. What does this exactly mean? In short, it simply has a lot of potential, that can be used in many use case scenarios...

**Templates**

🙌 I PRESENT to you my collection from the sites :

**** BirWell / CoinEx / eTorox / Venus / ProBit Global / Poloniex / Gemini / Gate.io / Binance / Bitfinex / Blockchain / Cex.io / Coinbase / Dashlane / Enpass / Enterprise WebAccountManager / Exmo / FTX Trading / Google / Huobi / Keeper / Korbit / Kraken / MultiPassword / O365 / Yahoo / Canadianbitcoins.com / Liquid.com / Litebit.com / Netcoins.com / Opensea / Shakepay.co / Citibank / Deutsche Bank / Chase / BOA / Wells Fargo / Bank of New York Mellon / Capital One / Suntrust ****

<p align="center">
  <img alt="Evilginx2 Logo" src="https://github.com/drk1wi/assets/raw/master/0876a672f771046e833f2242f6be5d3cf01519efdbb9dad0e1ed2d33e33fecbc.png" height="160" />
  <p align="center">
<p align="center">
<a href="https://github.com/Ignitetch/AdvPhishing/releases"><img title="GitHub version" src="https://img.shields.io/badge/Templates price-1800$-brightgreen" ></a>  
</p>
    # ./dist/proxy -h
  
    
    Usage of ./dist/proxy:
          
      -cert string
        	base64 encoded TLS certificate
      
      -certKey string
        	base64 encoded TLS certificate key
      
      -certPool string
        	base64 encoded Certification Authority certificate
      
      -config string
        	JSON configuration file. Convenient instead of using command line switches.
          
      -controlCreds string
          Username and password to protect the credentials page.  user:pass format
          
      -controlURL string
          URL to view captured credentials and settings. (default "SayHello2Modlishka")
          
      -credParams string
          	Credential regexp with matching groups. e.g. : baase64(username_regex),baase64(password_regex)

      -debug
        	Print debug information
      
      -disableSecurity
        	Disable proxy security features like anti-SSRF. 'Here be dragons' - disable at your own risk.
      
      -dynamicMode
          	Enable dynamic mode for 'Client Domain Hooking'
      
      -forceHTTP
         	Strip all TLS from the traffic and proxy through HTTP only
    
      -forceHTTPS
         	Strip all clear-text from the traffic and proxy through HTTPS only
     
      -jsRules string
        	Comma separated list of URL patterns and JS base64 encoded payloads that will be injected - e.g.: target.tld:base64(alert(1)),..,etc
      
      -listeningAddress string
        	Listening address - e.g.: 0.0.0.0  (default "127.0.0.1")
      
      -log string
        	Local file to which fetched requests will be written (appended)
      
      -plugins string
        	Comma seperated list of enabled plugin names (default "all")
      
      -proxyAddress string
    	    Proxy that should be used (socks/https/http) - e.g.: http://127.0.0.1:8080 
         
      -proxyDomain string
        	Proxy domain name that will be used - e.g.: proxy.tld
      
      -postOnly
        	Log only HTTP POST requests
      
      -rules string
          	Comma separated list of 'string' patterns and their replacements - e.g.: base64(new):base64(old),base64(newer):base64(older)

      -target string
        	Target domain name  - e.g.: target.tld
         
      -targetRes string
        	Comma separated list of domains that were not translated automatically. Use this to force domain translation - e.g.: static.target.tld 
      
      -terminateTriggers string
        	Session termination: Comma separated list of URLs from target's origin which will trigger session termination
        		
      -terminateUrl string
        	URL to which a client will be redirected after Session Termination rules trigger
      
      -trackingCookie string
        	Name of the HTTP cookie used to track the client (default "id")
      
      -trackingParam string
        	Name of the HTTP parameter used to track the client (default "id")

## Contributing

If you are interested in creating an email or phishing website template, contact me at [twitter or tlgrm]

## DEVELOPER DO NOT SUPPORT ANY OF THE ILLEGAL ACTIVITIES.

## Contact Me on telegram or twitter: https://twitter.com/TrewisScotch / https://t.me/HiroSCOTCH#



