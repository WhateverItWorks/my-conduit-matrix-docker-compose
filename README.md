# my-conduit-matrix-docker-compose
[Conduit](https://conduit.rs/) is a simple, fast and reliable matrix homeserver written in rust.

### €⁠20 on [Hetzner Cloud](https://hetzner.cloud/?ref=eLtKhFK70n4h)


### Automatic Installs
```
https://github.com/WhateverItWorks/Watchtower
```

### Deploy with Docker-Compose

```
git clone https://github.com/WhateverItWorks/my-conduit-matrix-docker-compose.git matrix
cd matrix
nano config.json
nano docker-compose.yml
docker-compose up -d
```
http://localhost:8448 (Matrix)

http://localhost:8009 (Cinny)


### Maintaining
```
docker-compose down
docker-compose pull
docker-compose up -d
```

### Homeserver Testing

- [Matrix Federation Tester](https://federationtester.matrix.org/#matrix.whateveritworks.org)

### Issue Fixes
[End-to-End Encryption breaks Admin Room](https://gitlab.com/famedly/conduit/-/issues/326#note_1213758498)

### View Logs
```
docker logs conduit
docker logs cinny-web
```

### Contact

```
https://matrix.to/#/@xbdm:matrix.whateveritworks.org
```

## Security Audits:

- [Internet.nl](https://internet.nl/site/element.whateveritworks.org/2060148/)
- [HSTS Preload](https://hstspreload.org/)
- [SSL Labs](https://www.ssllabs.com/ssltest/analyze.html?d=element.whateveritworks.org)
- [Security Headers](https://securityheaders.com/?q=element.whateveritworks.org&hide=on&followRedirects=on)
- [pagespeed](https://pagespeed.web.dev/)
- [webbkoll](https://webbkoll.dataskydd.net/en)
- [ImmuniWeb](https://www.immuniweb.com/ssl/element.whateveritworks.org)
- [Hardenize](https://www.hardenize.com/report/element.whateveritworks.org/1686343966)
- [Mozilla.org](https://observatory.mozilla.org/)
- [report-uri.com](https://report-uri.com/home/tools)
- [check-your-website.server-daten.de](https://check-your-website.server-daten.de/?q=element.whateveritworks.org)
- [csp-evaluator.withgoogle.com](https://csp-evaluator.withgoogle.com/)
- [OpenWPM](https://github.com/openwpm/OpenWPM)
- [privacyscore.org](https://privacyscore.org)
