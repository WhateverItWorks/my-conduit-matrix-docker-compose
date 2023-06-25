# my-conduit-matrix-docker-compose
[Conduit](https://conduit.rs/) is a simple, fast and reliable matrix homeserver written in rust.

## Security Audits:

- [Internet.nl](https://internet.nl/site/matrix.whateveritworks.org/2060148/)
- [HSTS Preload](https://hstspreload.org/)
- [SSL Labs](https://www.ssllabs.com/ssltest/analyze.html?d=matrix.whateveritworks.org)
- [Security Headers](https://securityheaders.com/?q=matrix.whateveritworks.org&hide=on&followRedirects=on)
- [pagespeed](https://pagespeed.web.dev/)
- [webbkoll](https://webbkoll.dataskydd.net/en)
- [ImmuniWeb](https://www.immuniweb.com/ssl/matrix.whateveritworks.org)
- [Hardenize](https://www.hardenize.com/report/matrix.whateveritworks.org/1686343966)
- [Mozilla.org](https://observatory.mozilla.org/)
- [report-uri.com](https://report-uri.com/home/tools)
- [check-your-website.server-daten.de](https://check-your-website.server-daten.de/?q=matrix.whateveritworks.org)
- [csp-evaluator.withgoogle.com](https://csp-evaluator.withgoogle.com/)
- [OpenWPM](https://github.com/openwpm/OpenWPM)
- [privacyscore.org](https://privacyscore.org)

## Usage:

1. Buy [Hetzner.com](https://hetzner.com) it's 100% renewal hardware and you get affordable dedicated servers, and you also help save the world.

2. Get [Cloudflare](https://cloudflare.com) it's carbon renewal and you help save the world.

3. ```apt install git```

4. ```git clone https://github.com/WhateverItWorks/my-conduit-matrix-docker-compose.git matrix```

5. ```nano element_config.json```

6. ```nano docker-compose.yml```

7. ```docker-compose up -d```

```http://localhost:8448```

### Homeserver Testing

- [Matrix Federation Tester](https://federationtester.matrix.org/#matrix.whateveritworks.org)
