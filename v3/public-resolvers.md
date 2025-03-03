# public-resolvers

This is an extensive list of public DNS resolvers supporting the
DNSCrypt and DNS-over-HTTP2 protocols.

This list is maintained by Frank Denis <j @ dnscrypt [.] info>

Warning: it includes servers that may censor content, servers that don't
verify DNSSEC records, and servers that will collect and monetize your
queries.

Adjust the `require_*` options in dnscrypt-proxy to filter that list
according to your needs.

To use that list, add this to the `[sources]` section of your
`dnscrypt-proxy.toml` configuration file:

    [sources.'public-resolvers']
    urls = ['https://raw.githubusercontent.com/DNSCrypt/dnscrypt-resolvers/master/v3/public-resolvers.md', 'https://download.dnscrypt.info/resolvers-list/v3/public-resolvers.md']
    minisign_key = 'RWQf6LRCGA9i53mlYecO4IzT51TGPpvWucNSCh1CBM0QTaLn73Y7GFO3'
    cache_file = 'public-resolvers.md'

--


## adfilter-adl

Hosted in Adelaide, Australia.

Blocks ads, malware, trackers and more. No persistent logs. DNSSEC. No EDNS Client-Subnet.

sdns://AgMAAAAAAAAADjE2My40Ny4xMTcuMTc2oMwQYNOcgym2K2-8fQ1t-TCYabmB5-Y5LVzY-kCPTYDmIEROvWe7g_iAezkh6TiskXi4gr1QqtsRIx8ETPXwjffOEGFkbC5hZGZpbHRlci5uZXQKL2Rucy1xdWVyeQ


## adfilter-adl-ipv6

Hosted in Adelaide, Australia.

Blocks ads, malware, trackers and more. No persistent logs. DNSSEC. No EDNS Client-Subnet.

sdns://AgMAAAAAAAAAHlsyNDAwOmM0MDE6OjUwNTQ6ZmY6ZmUxYjpiMDM2XaDMEGDTnIMptitvvH0NbfkwmGm5gefmOS1c2PpAj02A5iBETr1nu4P4gHs5Iek4rJF4uIK9UKrbESMfBEz18I33zhBhZGwuYWRmaWx0ZXIubmV0Ci9kbnMtcXVlcnk


## adfilter-per

Hosted in Perth, Australia.

Blocks ads, malware, trackers and more. No persistent logs. DNSSEC. No EDNS Client-Subnet.

sdns://AgMAAAAAAAAADTIwMy4yOS4yNDEuNzagzBBg05yDKbYrb7x9DW35MJhpuYHn5jktXNj6QI9NgOYgRE69Z7uD-IB7OSHpOKyReLiCvVCq2xEjHwRM9fCN984QcGVyLmFkZmlsdGVyLm5ldAovZG5zLXF1ZXJ5


## adfilter-per-ipv6

Hosted in Perth, Australia.

Blocks ads, malware, trackers and more. No persistent logs. DNSSEC. No EDNS Client-Subnet.

sdns://AgMAAAAAAAAAGFsyNDA0Ojk0MDA6NDFhOTo0ODAwOjoxXaDMEGDTnIMptitvvH0NbfkwmGm5gefmOS1c2PpAj02A5iBETr1nu4P4gHs5Iek4rJF4uIK9UKrbESMfBEz18I33zhBwZXIuYWRmaWx0ZXIubmV0Ci9kbnMtcXVlcnk


## adfilter-syd

Hosted in Sydney, Australia.

Blocks ads, malware, trackers and more. No persistent logs. DNSSEC. No EDNS Client-Subnet.

sdns://AgMAAAAAAAAADjExMi4yMTMuMzIuMjE5oMwQYNOcgym2K2-8fQ1t-TCYabmB5-Y5LVzY-kCPTYDmIEROvWe7g_iAezkh6TiskXi4gr1QqtsRIx8ETPXwjffOEHN5ZC5hZGZpbHRlci5uZXQKL2Rucy1xdWVyeQ


## adfilter-syd-ipv6

Hosted in Sydney, Australia.

Blocks ads, malware, trackers and more. No persistent logs. DNSSEC. No EDNS Client-Subnet.

sdns://AgMAAAAAAAAAGFsyNDA0Ojk0MDA6MjE0ZTplYTAwOjoxXaDMEGDTnIMptitvvH0NbfkwmGm5gefmOS1c2PpAj02A5iBETr1nu4P4gHs5Iek4rJF4uIK9UKrbESMfBEz18I33zhBzeWQuYWRmaWx0ZXIubmV0Ci9kbnMtcXVlcnk


## adfree.usableprivacy.net

Public updns DoH service with advertising, tracker and malware filters.
Hosted in Europe by @usableprivacy, details see: https://docs.usableprivacy.com

sdns://AgMAAAAAAAAADTc4LjQ3LjE2My4xNDGgzBBg05yDKbYrb7x9DW35MJhpuYHn5jktXNj6QI9NgOYgRE69Z7uD-IB7OSHpOKyReLiCvVCq2xEjHwRM9fCN984YYWRmcmVlLnVzYWJsZXByaXZhY3kubmV0Ci9kbnMtcXVlcnk


## adguard-dns

Remove ads and protect your computer from malware

Warning: This server is incompatible with anonymization.

sdns://AQMAAAAAAAAAETk0LjE0MC4xNC4xNDo1NDQzINErR_JS3PLCu_iZEIbq95zkSV2LFsigxDIuUso_OQhzIjIuZG5zY3J5cHQuZGVmYXVsdC5uczEuYWRndWFyZC5jb20


## adguard-dns-doh

Remove ads and protect your computer from malware (over DoH)

sdns://AgMAAAAAAAAADDk0LjE0MC4xNS4xNSCaOjT3J965vKUQA9nOnDn48n3ZxSQpAcK6saROY1oCGQ9kbnMuYWRndWFyZC5jb20KL2Rucy1xdWVyeQ


## adguard-dns-family

Adguard DNS with safesearch and adult content blocking

Warning: This server is incompatible with anonymization.

sdns://AQMAAAAAAAAAETk0LjE0MC4xNC4xNTo1NDQzILgxXdexS27jIKRw3C7Wsao5jMnlhvhdRUXWuMm1AFq6ITIuZG5zY3J5cHQuZmFtaWx5Lm5zMS5hZGd1YXJkLmNvbQ


## adguard-dns-family-doh

Adguard DNS with safesearch and adult content blocking (over DoH)

sdns://AgMAAAAAAAAADDk0LjE0MC4xNS4xNiCaOjT3J965vKUQA9nOnDn48n3ZxSQpAcK6saROY1oCGRZkbnMtZmFtaWx5LmFkZ3VhcmQuY29tCi9kbnMtcXVlcnk


## adguard-dns-family-ipv6

Adguard DNS with safesearch and adult content blocking (over IPv6)

Warning: This server is incompatible with anonymization.

sdns://AQMAAAAAAAAAGVsyYTEwOjUwYzA6OmJhZDE6ZmZdOjU0NDMguDFd17FLbuMgpHDcLtaxqjmMyeWG-F1FRda4ybUAWrohMi5kbnNjcnlwdC5mYW1pbHkubnMxLmFkZ3VhcmQuY29t


## adguard-dns-ipv6

Remove ads and protect your computer from malware (over IPv6)

Warning: This server is incompatible with anonymization.

sdns://AQMAAAAAAAAAGFsyYTEwOjUwYzA6OmFkMTpmZl06NTQ0MyDRK0fyUtzywrv4mRCG6vec5EldixbIoMQyLlLKPzkIcyIyLmRuc2NyeXB0LmRlZmF1bHQubnMxLmFkZ3VhcmQuY29t


## adguard-dns-unfiltered

AdGuard public DNS servers without filters

Warning: This server is incompatible with anonymization.

sdns://AQcAAAAAAAAAEjk0LjE0MC4xNC4xNDA6NTQ0MyC16ETWuDo-PhJo62gfvqcN48X6aNvWiBQdvy7AZrLa-iUyLmRuc2NyeXB0LnVuZmlsdGVyZWQubnMxLmFkZ3VhcmQuY29t


## adguard-dns-unfiltered-doh

AdGuard public DNS servers without filters (over DoH)

sdns://AgcAAAAAAAAADTk0LjE0MC4xNC4xNDAgmjo09yfeubylEAPZzpw5-PJ92cUkKQHCurGkTmNaAhkaZG5zLXVuZmlsdGVyZWQuYWRndWFyZC5jb20KL2Rucy1xdWVyeQ


## adguard-dns-unfiltered-ipv6

AdGuard public DNS servers without filters (over IPv6)

Warning: This server is incompatible with anonymization.

sdns://AQcAAAAAAAAAFlsyYTEwOjUwYzA6OjE6ZmZdOjU0NDMgtehE1rg6Pj4SaOtoH76nDePF-mjb1ogUHb8uwGay2volMi5kbnNjcnlwdC51bmZpbHRlcmVkLm5zMS5hZGd1YXJkLmNvbQ


## ahadns-doh-chi

A zero logging DNS with support for DNS-over-HTTPS (DoH) & DNS-over-TLS (DoT). Blocks ads, malware, trackers, viruses, ransomware, telemetry and more. No persistent logs. DNSSEC. Hosted in Chicago, USA. By https://ahadns.com/
Server statistics can be seen at: https://statistics.ahadns.com/?server=chi

sdns://AgMAAAAAAAAADTE5My4yOS42Mi4xOTagzBBg05yDKbYrb7x9DW35MJhpuYHn5jktXNj6QI9NgOYgRE69Z7uD-IB7OSHpOKyReLiCvVCq2xEjHwRM9fCN984SZG9oLmNoaS5haGFkbnMubmV0Ci9kbnMtcXVlcnk


## ahadns-doh-la

A zero logging DNS with support for DNS-over-HTTPS (DoH) & DNS-over-TLS (DoT). Blocks ads, malware, trackers, viruses, ransomware, telemetry and more. No persistent logs. DNSSEC. Hosted in Los Angeles, USA. By https://ahadns.com/
Server statistics can be seen at: https://statistics.ahadns.com/?server=la

sdns://AgMAAAAAAAAADTQ1LjY3LjIxOS4yMDigzBBg05yDKbYrb7x9DW35MJhpuYHn5jktXNj6QI9NgOYgRE69Z7uD-IB7OSHpOKyReLiCvVCq2xEjHwRM9fCN984RZG9oLmxhLmFoYWRucy5uZXQKL2Rucy1xdWVyeQ


## ahadns-doh-nl

A zero logging DNS with support for DNS-over-HTTPS (DoH) & DNS-over-TLS (DoT). Blocks ads, malware, trackers, viruses, ransomware, telemetry and more. No persistent logs. DNSSEC. Hosted in Amsterdam, Netherlands. By https://ahadns.com/
Server statistics can be seen at: https://statistics.ahadns.com/?server=nl

sdns://AgMAAAAAAAAACTUuMi43NS43NaDMEGDTnIMptitvvH0NbfkwmGm5gefmOS1c2PpAj02A5iBETr1nu4P4gHs5Iek4rJF4uIK9UKrbESMfBEz18I33zhFkb2gubmwuYWhhZG5zLm5ldAovZG5zLXF1ZXJ5


## ahadns-doh-pl

A zero logging DNS with support for DNS-over-HTTPS (DoH) & DNS-over-TLS (DoT). Blocks ads, malware, trackers, viruses, ransomware, telemetry and more. No persistent logs. DNSSEC. Hosted in Poland. By https://ahadns.com/
Server statistics can be seen at: https://statistics.ahadns.com/?server=pl

sdns://AgMAAAAAAAAADDQ1LjEzMi43NS4xNqDMEGDTnIMptitvvH0NbfkwmGm5gefmOS1c2PpAj02A5iBETr1nu4P4gHs5Iek4rJF4uIK9UKrbESMfBEz18I33zhFkb2gucGwuYWhhZG5zLm5ldAovZG5zLXF1ZXJ5


## alidns-doh

A public DNS resolver that supports DoH/DoT in mainland China, provided by Alibaba-Cloud.

Warning: GFW filtering rules are applied by that resolver.

Homepage: https://alidns.com/

sdns://AgAAAAAAAAAACTIyMy41LjUuNSCY49XlNq8pWM0vfxT3BO9KJ20l4zzWXy5l9eTycnwTMA5kbnMuYWxpZG5zLmNvbQovZG5zLXF1ZXJ5


## altername

Protocol: DNSCrypt | Features: Non-logging, Non-filtering, DNSSEC, EmerDNS | Location: Moscow, Russia

sdns://AQcAAAAAAAAAEDE4NS4yMDQuMi44Ojg0NDMgmfGTecriYs8VCfSDIUo6U6yQ5g98itBT7FWH3yYVB1MZMi5kbnNjcnlwdC1jZXJ0LmFsdGVybmFtZQ


## altername-ipv6

Protocol: DNSCrypt IPv6 | Features: Non-logging, Non-filtering, DNSSEC, EmerDNS | Location: Moscow, Russia

sdns://AQcAAAAAAAAAG1syYTA0OjUyMDA6ZmZmNDo6MTNmZl06ODQ0MyCZ8ZN5yuJizxUJ9IMhSjpTrJDmD3yK0FPsVYffJhUHUxkyLmRuc2NyeXB0LWNlcnQuYWx0ZXJuYW1l


## ams-ads-doh-nl

Resolver in Amsterdam. DoH protocol. Non-logging. Blocks ads, malware and trackers. DNSSEC enabled.

sdns://AgMAAAAAAAAADDg5LjM4LjEzMS4zOAAYZG5zbmwtbm9hZHMuYWxla2JlcmcubmV0Ci9kbnMtcXVlcnk


## ams-dnscrypt-nl

Resolver in Amsterdam. Dnscrypt protocol. Non-logging, non-filtering, DNSSEC.

sdns://AQcAAAAAAAAAETg5LjM4LjEzMS4zODo0MzQzIKWHS9r0FoKY--wcnJl1Ar5aOUb91xsufvPUjid3rNRaHzIuZG5zY3J5cHQtY2VydC5hbXMtZG5zY3J5cHQtbmw


## ams-dnscrypt-nl-ipv6

Resolver in Amsterdam. Dnscrypt protocol. Non-logging, non-filtering, DNSSEC.

sdns://AQcAAAAAAAAAGlsyYTBjOmI5YzA6Zjo0NTFkOjoxXTo0MzQzIKWHS9r0FoKY--wcnJl1Ar5aOUb91xsufvPUjid3rNRaHzIuZG5zY3J5cHQtY2VydC5hbXMtZG5zY3J5cHQtbmw


## ams-doh-nl

Resolver in Amsterdam. DoH protocol. Non-logging, non-filtering, DNSSEC.

sdns://AgcAAAAAAAAADDg5LjM4LjEzMS4zOKDMEGDTnIMptitvvH0NbfkwmGm5gefmOS1c2PpAj02A5iBETr1nu4P4gHs5Iek4rJF4uIK9UKrbESMfBEz18I33zhJkbnNubC5hbGVrYmVyZy5uZXQKL2Rucy1xdWVyeQ


## ams-doh-nl-ipv6

Resolver in Amsterdam. DoH protocol. Non-logging, non-filtering, DNSSEC.

sdns://AgcAAAAAAAAAFVsyYTBjOmI5YzA6Zjo0NTFkOjoxXaDMEGDTnIMptitvvH0NbfkwmGm5gefmOS1c2PpAj02A5iBETr1nu4P4gHs5Iek4rJF4uIK9UKrbESMfBEz18I33zhJkbnNubC5hbGVrYmVyZy5uZXQKL2Rucy1xdWVyeQ


## att

AT&T test DoH server.

sdns://AgUAAAAAAAAAAKC8hFRehaL-5iAWO74cDW6sa3toE6vGROtou_hQdtyuYyCY49XlNq8pWM0vfxT3BO9KJ20l4zzWXy5l9eTycnwTMBBkb2h0cmlhbC5hdHQubmV0Ci9kbnMtcXVlcnk


## bortzmeyer

Non-logging DoH server in France operated by Stéphane Bortzmeyer.

https://www.bortzmeyer.org/doh-bortzmeyer-fr-policy.html

sdns://AgcAAAAAAAAADDE5My43MC44NS4xMaDMEGDTnIMptitvvH0NbfkwmGm5gefmOS1c2PpAj02A5iBETr1nu4P4gHs5Iek4rJF4uIK9UKrbESMfBEz18I33zhFkb2guYm9ydHptZXllci5mcgEv


## bortzmeyer-ipv6

Non-logging DoH server in France operated by Stéphane Bortzmeyer (IPv6 only).

https://www.bortzmeyer.org/doh-bortzmeyer-fr-policy.html

sdns://AgcAAAAAAAAAGVsyMDAxOjQxZDA6MzAyOjIyMDA6OjE4MF2gzBBg05yDKbYrb7x9DW35MJhpuYHn5jktXNj6QI9NgOYgRE69Z7uD-IB7OSHpOKyReLiCvVCq2xEjHwRM9fCN984RZG9oLmJvcnR6bWV5ZXIuZnIBLw


## brahma-world

DNS-over-HTTPS server. Non Logging, filters ads, trackers and malware. DNSSEC ready, QNAME Minimization, No EDNS Client-Subnet.

Hosted in Stockholm, Sweden. (https://dns.brahma.world)

sdns://AgMAAAAAAAAADjE2LjE3MC4xNTAuMjIxoMwQYNOcgym2K2-8fQ1t-TCYabmB5-Y5LVzY-kCPTYDmIEROvWe7g_iAezkh6TiskXi4gr1QqtsRIx8ETPXwjffOEGRucy5icmFobWEud29ybGQKL2Rucy1xdWVyeQ


## brahma-world-ipv6

DNS-over-HTTPS server. Non Logging, filters ads, trackers and malware. DNSSEC ready, QNAME Minimization, No EDNS Client-Subnet.

Hosted in Stockholm, Sweden. (https://dns.brahma.world)

sdns://AgMAAAAAAAAAJ1syYTA1OmQwMTY6YWY4OjQwMDA6NzcxMDo2ZmM6YmRlMzpmZTBlXaDMEGDTnIMptitvvH0NbfkwmGm5gefmOS1c2PpAj02A5iBETr1nu4P4gHs5Iek4rJF4uIK9UKrbESMfBEz18I33zhBkbnMuYnJhaG1hLndvcmxkCi9kbnMtcXVlcnk


## circl-doh

DoH server operated by CIRCL, Computer Incident Response Center Luxembourg.

Hosted in Bettembourg, Luxembourg.

sdns://AgYAAAAAAAAADTE4NS4xOTQuOTQuNzEADGRucy5jaXJjbC5sdQovZG5zLXF1ZXJ5


## circl-doh-ipv6

DoH server operated by CIRCL, Computer Incident Response Center Luxembourg.

Hosted in Bettembourg, Luxembourg.

sdns://AgYAAAAAAAAAElsyYTAwOjU5ODA6OTQ6OjcxXQAMZG5zLmNpcmNsLmx1Ci9kbnMtcXVlcnk


## cisco

Remove your DNS blind spot (DNSCrypt protocol)

Warning: This server is incompatible with anonymization.

Warning: modifies your queries to include a copy of your network
address when forwarding them to a selection of companies and organizations.

sdns://AQEAAAAAAAAADjIwOC42Ny4yMjAuMjIwILc1EUAgbyJdPivYItf9aR6hwzzI1maNDL4Ev6vKQ_t5GzIuZG5zY3J5cHQtY2VydC5vcGVuZG5zLmNvbQ


## cisco-doh

Remove your DNS blind spot (DoH protocol)

Warning: modifies your queries to include a copy of your network
address when forwarding them to a selection of companies and organizations.

sdns://AgAAAAAAAAAADDE0Ni4xMTIuNDEuMiCYZO337qhZZ1J0sPrfvSaTZamrnrp3PahnSUxalKQ33w9kb2gub3BlbmRucy5jb20KL2Rucy1xdWVyeQ


## cisco-familyshield

Block websites not suitable for children (DNSCrypt protocol)

Warning: modifies your queries to include a copy of your network
address when forwarding them to a selection of companies and organizations.

Currently incompatible with DNS anonymization.

sdns://AQEAAAAAAAAADjIwOC42Ny4yMjAuMTIzILc1EUAgbyJdPivYItf9aR6hwzzI1maNDL4Ev6vKQ_t5GzIuZG5zY3J5cHQtY2VydC5vcGVuZG5zLmNvbQ


## cisco-familyshield-ipv6

Block websites not suitable for children (IPv6)

Warning: This server is incompatible with anonymization.

Warning: modifies your queries to include a copy of your network
address when forwarding them to a selection of companies and organizations.

sdns://AQEAAAAAAAAAEVsyNjIwOjExOTozNTo6MzVdILc1EUAgbyJdPivYItf9aR6hwzzI1maNDL4Ev6vKQ_t5GzIuZG5zY3J5cHQtY2VydC5vcGVuZG5zLmNvbQ


## cisco-ipv6

Cisco OpenDNS over IPv6 (DNSCrypt protocol)

Warning: This server is incompatible with anonymization.

Warning: modifies your queries to include a copy of your network
address when forwarding them to a selection of companies and organizations.

sdns://AQEAAAAAAAAAD1syNjIwOjA6Y2NjOjoyXSC3NRFAIG8iXT4r2CLX_WkeocM8yNZmjQy-BL-rykP7eRsyLmRuc2NyeXB0LWNlcnQub3BlbmRucy5jb20


## cisco-ipv6-doh

Cisco OpenDNS over IPv6 (DoH protocol)

Warning: modifies your queries to include a copy of your network
address when forwarding them to a selection of companies and organizations.

sdns://AgAAAAAAAAAAEFsyNjIwOjExOTpmYzo6Ml0gmGTt9-6oWWdSdLD6370mk2Wpq566dz2oZ0lMWpSkN98PZG9oLm9wZW5kbnMuY29tCi9kbnMtcXVlcnk


## cisco-sandbox

Cisco OpenDNS Sandbox (anycast) - RFC-compliant DNS service without filtering

dnssec/log/no-filter/ecs 146.112.41.4

Warning: This server is incompatible with anonymization.

sdns://AQUAAAAAAAAADDE0Ni4xMTIuNDEuNCC3NRFAIG8iXT4r2CLX_WkeocM8yNZmjQy-BL-rykP7eRsyLmRuc2NyeXB0LWNlcnQub3BlbmRucy5jb20


## cleanbrowsing-adult

Blocks access to all adult, pornographic and explicit sites. It does
not block proxy or VPNs, nor mixed-content sites. Sites like Reddit
are allowed. Google and Bing are set to the Safe Mode.

Warning: This server is incompatible with anonymization.

By https://cleanbrowsing.org/

sdns://AQMAAAAAAAAAEzE4NS4yMjguMTY4LjEwOjg0NDMgvKwy-tVDaRcfCDLWB1AnwyCM7vDo6Z-UGNx3YGXUjykRY2xlYW5icm93c2luZy5vcmc


## cleanbrowsing-family

Blocks access to all adult, pornographic and explicit sites. It also
blocks proxy and VPN domains that are used to bypass the filters.
Mixed content sites (like Reddit) are also blocked. Google, Bing and
Youtube are set to the Safe Mode.

Warning: This server is incompatible with anonymization.

By https://cleanbrowsing.org/

sdns://AQMAAAAAAAAAFDE4NS4yMjguMTY4LjE2ODo4NDQzILysMvrVQ2kXHwgy1gdQJ8MgjO7w6OmflBjcd2Bl1I8pEWNsZWFuYnJvd3Npbmcub3Jn


## cleanbrowsing-security

Block access to phishing, malware and malicious domains. It does not block adult content.
By https://cleanbrowsing.org/

Warning: This server is incompatible with anonymization.

sdns://AQMAAAAAAAAAEjE4NS4yMjguMTY4Ljk6ODQ0MyC8rDL61UNpFx8IMtYHUCfDIIzu8Ojpn5QY3HdgZdSPKRFjbGVhbmJyb3dzaW5nLm9yZw


## cloudflare

Cloudflare DNS (anycast) - aka 1.1.1.1 / 1.0.0.1

sdns://AgcAAAAAAAAABzEuMC4wLjEAEmRucy5jbG91ZGZsYXJlLmNvbQovZG5zLXF1ZXJ5


## cloudflare-family

Cloudflare DNS (anycast) with malware protection and parental control - aka 1.1.1.3 / 1.0.0.3

sdns://AgMAAAAAAAAABzEuMC4wLjMAGWZhbWlseS5jbG91ZGZsYXJlLWRucy5jb20KL2Rucy1xdWVyeQ


## cloudflare-family-ipv6

Cloudflare DNS over IPv6 (anycast) with malware protection and parental control

sdns://AgMAAAAAAAAAFlsyNjA2OjQ3MDA6NDcwMDo6MTExM10AGWZhbWlseS5jbG91ZGZsYXJlLWRucy5jb20KL2Rucy1xdWVyeQ
sdns://AgMAAAAAAAAAFlsyNjA2OjQ3MDA6NDcwMDo6MTAwM10AGWZhbWlseS5jbG91ZGZsYXJlLWRucy5jb20KL2Rucy1xdWVyeQ


## cloudflare-ipv6

Cloudflare DNS over IPv6 (anycast)

sdns://AgcAAAAAAAAAFlsyNjA2OjQ3MDA6NDcwMDo6MTExMV0AIDFkb3QxZG90MWRvdDEuY2xvdWRmbGFyZS1kbnMuY29tCi9kbnMtcXVlcnk
sdns://AgcAAAAAAAAAFlsyNjA2OjQ3MDA6NDcwMDo6MTAwMV0AIDFkb3QxZG90MWRvdDEuY2xvdWRmbGFyZS1kbnMuY29tCi9kbnMtcXVlcnk


## cloudflare-security

Cloudflare DNS (anycast) with malware blocking - aka 1.1.1.2 / 1.0.0.2

sdns://AgMAAAAAAAAABzEuMC4wLjIAG3NlY3VyaXR5LmNsb3VkZmxhcmUtZG5zLmNvbQovZG5zLXF1ZXJ5


## cloudflare-security-ipv6

Cloudflare DNS over IPv6 (anycast) with malware blocking

sdns://AgMAAAAAAAAAFlsyNjA2OjQ3MDA6NDcwMDo6MTExMl0AG3NlY3VyaXR5LmNsb3VkZmxhcmUtZG5zLmNvbQovZG5zLXF1ZXJ5
sdns://AgMAAAAAAAAAFlsyNjA2OjQ3MDA6NDcwMDo6MTAwMl0AG3NlY3VyaXR5LmNsb3VkZmxhcmUtZG5zLmNvbQovZG5zLXF1ZXJ5


## comodo-02

Comodo Dome Shield (anycast) - https://cdome.comodo.com/shield/

sdns://AQUAAAAAAAAACjguMjAuMjQ3LjIg0sJUqpYcHsoXmZb1X7yAHwg2xyN5q1J-zaiGG-Dgs7AoMi5kbnNjcnlwdC1jZXJ0LnNoaWVsZC0yLmRuc2J5Y29tb2RvLmNvbQ


## controld-block-malware

ControlD Free DNS. Take CONTROL of your Internet. Block unwanted content, bypass geo-restrictions and be more productive. DoH protocol and No logging. - https://controld.com/free-dns

This DNS blocks Malware domains.

sdns://AgMAAAAAAAAACjc2Ljc2LjIuMTEAFGZyZWVkbnMuY29udHJvbGQuY29tAy9wMQ


## controld-block-malware-ad

ControlD Free DNS. Take CONTROL of your Internet. Block unwanted content, bypass geo-restrictions and be more productive. DoH protocol and No logging. - https://controld.com/free-dns

This DNS blocks Malware, Ads & Tracking domains.

sdns://AgMAAAAAAAAACjc2Ljc2LjIuMTEAFGZyZWVkbnMuY29udHJvbGQuY29tAy9wMg


## controld-block-malware-ad-social

ControlD Free DNS. Take CONTROL of your Internet. Block unwanted content, bypass geo-restrictions and be more productive. DoH protocol and No logging. - https://controld.com/free-dns

This DNS blocks Malware, Ads & Tracking and Social Networks domains.

sdns://AgMAAAAAAAAACjc2Ljc2LjIuMTEAFGZyZWVkbnMuY29udHJvbGQuY29tAy9wMw


## controld-family-friendly

ControlD Free DNS. Take CONTROL of your Internet. Block unwanted content, bypass geo-restrictions and be more productive. DoH protocol and No logging. - https://controld.com/free-dns

This DNS blocks Malware, Ads & Tracking, Adult Content and Drugs domains.

sdns://AgMAAAAAAAAACjc2Ljc2LjIuMTEAFGZyZWVkbnMuY29udHJvbGQuY29tBy9mYW1pbHk


## controld-uncensored

ControlD Free DNS. Take CONTROL of your Internet. Block unwanted content, bypass geo-restrictions and be more productive. DoH protocol and No logging. - https://controld.com/free-dns

This DNS unblocks censored domains from various countries.

sdns://AgcAAAAAAAAACjc2Ljc2LjIuMTEAFGZyZWVkbnMuY29udHJvbGQuY29tCy91bmNlbnNvcmVk


## controld-unfiltered

ControlD Free DNS. Take CONTROL of your Internet. Block unwanted content, bypass geo-restrictions and be more productive. DoH protocol and No logging. - https://controld.com/free-dns

This is a Unfiltered DNS, no DNS record blocking or manipulation here, if you want to block Malware, Ads & Tracking or Social Network domains, use the other ControlD DNS configs.

sdns://AgcAAAAAAAAACjc2Ljc2LjIuMTEAFGZyZWVkbnMuY29udHJvbGQuY29tAy9wMA


## cs-austria

Wien, Austria DNSCrypt server provided by https://cryptostorm.is/

sdns://AQIAAAAAAAAADTk0LjE5OC40MS4yMzUgMTNyrVlWMsJBa4cvCY-FG925ZShMbL6aTxkJZDDbqVoeMi5kbnNjcnlwdC1jZXJ0LmNyeXB0b3N0b3JtLmlz


## cs-barcelona

Barcelona, Spain DNSCrypt server provided by https://cryptostorm.is/

sdns://AQIAAAAAAAAADjM3LjEyMC4xNDIuMTE1IDEzcq1ZVjLCQWuHLwmPhRvduWUoTGy-mk8ZCWQw26laHjIuZG5zY3J5cHQtY2VydC5jcnlwdG9zdG9ybS5pcw


## cs-belgium

Brussels, Belgium DNSCrypt server provided by https://cryptostorm.is/

sdns://AQIAAAAAAAAADTM3LjEyMC4yMzYuMTEgMTNyrVlWMsJBa4cvCY-FG925ZShMbL6aTxkJZDDbqVoeMi5kbnNjcnlwdC1jZXJ0LmNyeXB0b3N0b3JtLmlz


## cs-berlin

Berlin, Germany DNSCrypt server provided by https://cryptostorm.is/

sdns://AQIAAAAAAAAADTM3LjEyMC4yMTcuNzUgMTNyrVlWMsJBa4cvCY-FG925ZShMbL6aTxkJZDDbqVoeMi5kbnNjcnlwdC1jZXJ0LmNyeXB0b3N0b3JtLmlz


## cs-brazil

Sao Paulo, Brazil DNSCrypt server provided by https://cryptostorm.is/

sdns://AQIAAAAAAAAADjE3Ny41NC4xNDUuMTMxIDEzcq1ZVjLCQWuHLwmPhRvduWUoTGy-mk8ZCWQw26laHjIuZG5zY3J5cHQtY2VydC5jcnlwdG9zdG9ybS5pcw


## cs-bulgaria

Sofia, Bulgaria DNSCrypt server provided by https://cryptostorm.is/

sdns://AQIAAAAAAAAADjM3LjEyMC4xNTIuMjM1IDEzcq1ZVjLCQWuHLwmPhRvduWUoTGy-mk8ZCWQw26laHjIuZG5zY3J5cHQtY2VydC5jcnlwdG9zdG9ybS5pcw


## cs-czech

Prague, Czech Republic DNSCrypt server provided by https://cryptostorm.is/

sdns://AQIAAAAAAAAADzIxNy4xMzguMjIwLjI0MyAxM3KtWVYywkFrhy8Jj4Ub3bllKExsvppPGQlkMNupWh4yLmRuc2NyeXB0LWNlcnQuY3J5cHRvc3Rvcm0uaXM


## cs-dc

US - Washington, DC DNSCrypt server provided by https://cryptostorm.is/

sdns://AQIAAAAAAAAADDE5OC43LjU4LjIyNyAxM3KtWVYywkFrhy8Jj4Ub3bllKExsvppPGQlkMNupWh4yLmRuc2NyeXB0LWNlcnQuY3J5cHRvc3Rvcm0uaXM


## cs-de

Frankfurt, Germany DNSCrypt server provided by https://cryptostorm.is/

sdns://AQIAAAAAAAAACzE0Ni43MC44Mi4zIDEzcq1ZVjLCQWuHLwmPhRvduWUoTGy-mk8ZCWQw26laHjIuZG5zY3J5cHQtY2VydC5jcnlwdG9zdG9ybS5pcw


## cs-dk

Denmark DNSCrypt server provided by https://cryptostorm.is/

sdns://AQIAAAAAAAAADTM3LjEyMC4yMzIuNDMgMTNyrVlWMsJBa4cvCY-FG925ZShMbL6aTxkJZDDbqVoeMi5kbnNjcnlwdC1jZXJ0LmNyeXB0b3N0b3JtLmlz


## cs-dus1

Dusseldorf, Germany 1 DNSCrypt server provided by https://cryptostorm.is/

sdns://AQIAAAAAAAAADjIxMy4yMDIuMjE2LjEyIDEzcq1ZVjLCQWuHLwmPhRvduWUoTGy-mk8ZCWQw26laHjIuZG5zY3J5cHQtY2VydC5jcnlwdG9zdG9ybS5pcw


## cs-dus4

Dusseldorf, Germany 4 DNSCrypt server provided by https://cryptostorm.is/

sdns://AQIAAAAAAAAADjg1LjExNC4xMzguMTE5IDEzcq1ZVjLCQWuHLwmPhRvduWUoTGy-mk8ZCWQw26laHjIuZG5zY3J5cHQtY2VydC5jcnlwdG9zdG9ybS5pcw


## cs-finland

Finland DNSCrypt server provided by https://cryptostorm.is

sdns://AQIAAAAAAAAADjE4NS4xMTcuMTE4LjIwIDEzcq1ZVjLCQWuHLwmPhRvduWUoTGy-mk8ZCWQw26laHjIuZG5zY3J5cHQtY2VydC5jcnlwdG9zdG9ybS5pcw


## cs-fr

France DNSCrypt server provided by https://cryptostorm.is/

sdns://AQIAAAAAAAAADTE2My4xNzIuMzQuNTYgMTNyrVlWMsJBa4cvCY-FG925ZShMbL6aTxkJZDDbqVoeMi5kbnNjcnlwdC1jZXJ0LmNyeXB0b3N0b3JtLmlz


## cs-hungary

Budapest, Hungary DNSCrypt server provided by https://cryptostorm.is/

sdns://AQIAAAAAAAAADTg2LjEwNi43NC4yMTkgMTNyrVlWMsJBa4cvCY-FG925ZShMbL6aTxkJZDDbqVoeMi5kbnNjcnlwdC1jZXJ0LmNyeXB0b3N0b3JtLmlz


## cs-il

US - Chicago, IL DNSCrypt server provided by https://cryptostorm.is/

sdns://AQIAAAAAAAAADjE3My4yMzQuNTYuMTE1IDEzcq1ZVjLCQWuHLwmPhRvduWUoTGy-mk8ZCWQw26laHjIuZG5zY3J5cHQtY2VydC5jcnlwdG9zdG9ybS5pcw


## cs-il2

US - Chicago, IL 2 DNSCrypt server provided by https://cryptostorm.is/

sdns://AQIAAAAAAAAADjE3Mi4xMDcuMTk5LjE5IDEzcq1ZVjLCQWuHLwmPhRvduWUoTGy-mk8ZCWQw26laHjIuZG5zY3J5cHQtY2VydC5jcnlwdG9zdG9ybS5pcw


## cs-india

India DNSCrypt server provided by https://cryptostorm.is/

sdns://AQIAAAAAAAAADzE2NS4yMzEuMjUzLjE2MyAxM3KtWVYywkFrhy8Jj4Ub3bllKExsvppPGQlkMNupWh4yLmRuc2NyeXB0LWNlcnQuY3J5cHRvc3Rvcm0uaXM


## cs-ireland

Dublin, Ireland DNSCrypt server provided by https://cryptostorm.is/

sdns://AQIAAAAAAAAADjM3LjEyMC4yMzUuMTg3IDEzcq1ZVjLCQWuHLwmPhRvduWUoTGy-mk8ZCWQw26laHjIuZG5zY3J5cHQtY2VydC5jcnlwdG9zdG9ybS5pcw


## cs-is

Iceland DNSCrypt server provided by https://cryptostorm.is/

sdns://AQIAAAAAAAAADTgyLjIyMS4xMjguNDQgMTNyrVlWMsJBa4cvCY-FG925ZShMbL6aTxkJZDDbqVoeMi5kbnNjcnlwdC1jZXJ0LmNyeXB0b3N0b3JtLmlz


## cs-london

London, England DNSCrypt server provided by https://cryptostorm.is/

sdns://AQIAAAAAAAAADTc4LjEyOS4xNDAuNjUgMTNyrVlWMsJBa4cvCY-FG925ZShMbL6aTxkJZDDbqVoeMi5kbnNjcnlwdC1jZXJ0LmNyeXB0b3N0b3JtLmlz


## cs-lv

Latvia DNSCrypt server provided by https://cryptostorm.is/

sdns://AQIAAAAAAAAADzEwOS4yNDguMTQ5LjEzMyAxM3KtWVYywkFrhy8Jj4Ub3bllKExsvppPGQlkMNupWh4yLmRuc2NyeXB0LWNlcnQuY3J5cHRvc3Rvcm0uaXM


## cs-madrid

Madrid, Spain DNSCrypt server provided by https://cryptostorm.is/

sdns://AQIAAAAAAAAADjE4NS4xODMuMTA2LjgzIDEzcq1ZVjLCQWuHLwmPhRvduWUoTGy-mk8ZCWQw26laHjIuZG5zY3J5cHQtY2VydC5jcnlwdG9zdG9ybS5pcw


## cs-manchester

Manchester, England DNSCrypt server provided by https://cryptostorm.is/

sdns://AQIAAAAAAAAADTE5NS4xMi40OC4xNzEgMTNyrVlWMsJBa4cvCY-FG925ZShMbL6aTxkJZDDbqVoeMi5kbnNjcnlwdC1jZXJ0LmNyeXB0b3N0b3JtLmlz


## cs-md

Moldova DNSCrypt server provided by https://cryptostorm.is/

sdns://AQIAAAAAAAAADjE3OC4xNzUuMTI5LjE2IDEzcq1ZVjLCQWuHLwmPhRvduWUoTGy-mk8ZCWQw26laHjIuZG5zY3J5cHQtY2VydC5jcnlwdG9zdG9ybS5pcw


## cs-mexico

Mexico City, Mexico DNSCrypt server provided by https://cryptostorm.is/

sdns://AQIAAAAAAAAADTEwMy4xNC4yNi4xOTAgMTNyrVlWMsJBa4cvCY-FG925ZShMbL6aTxkJZDDbqVoeMi5kbnNjcnlwdC1jZXJ0LmNyeXB0b3N0b3JtLmlz


## cs-milan

Milan, Italy DNSCrypt server provided by https://cryptostorm.is/

sdns://AQIAAAAAAAAADzIxNy4xMzguMjE5LjIxOSAxM3KtWVYywkFrhy8Jj4Ub3bllKExsvppPGQlkMNupWh4yLmRuc2NyeXB0LWNlcnQuY3J5cHRvc3Rvcm0uaXM


## cs-nc

US - North Carolina DNSCrypt server provided by https://cryptostorm.is/

sdns://AQIAAAAAAAAADjE1NS4yNTQuMjEuMjUwIDEzcq1ZVjLCQWuHLwmPhRvduWUoTGy-mk8ZCWQw26laHjIuZG5zY3J5cHQtY2VydC5jcnlwdG9zdG9ybS5pcw


## cs-nl

Netherlands DNSCrypt server provided by https://cryptostorm.is/

sdns://AQIAAAAAAAAADTE4NS4xMDcuODAuODQgMTNyrVlWMsJBa4cvCY-FG925ZShMbL6aTxkJZDDbqVoeMi5kbnNjcnlwdC1jZXJ0LmNyeXB0b3N0b3JtLmlz


## cs-nl2

Netherlands 2 DNSCrypt server provided by https://cryptostorm.is/

sdns://AQIAAAAAAAAADzE3Mi4xMDcuMjI2LjEwNyAxM3KtWVYywkFrhy8Jj4Ub3bllKExsvppPGQlkMNupWh4yLmRuc2NyeXB0LWNlcnQuY3J5cHRvc3Rvcm0uaXM


## cs-norway

Oslo, Norway DNSCrypt server provided by https://cryptostorm.is/

sdns://AQIAAAAAAAAADjkxLjIxOS4yMTUuMjI3IDEzcq1ZVjLCQWuHLwmPhRvduWUoTGy-mk8ZCWQw26laHjIuZG5zY3J5cHQtY2VydC5jcnlwdG9zdG9ybS5pcw


## cs-nv

US - Las Vegas, NV DNSCrypt server provided by https://cryptostorm.is/

sdns://AQIAAAAAAAAADDM3LjEyMC4xNDcuMiAxM3KtWVYywkFrhy8Jj4Ub3bllKExsvppPGQlkMNupWh4yLmRuc2NyeXB0LWNlcnQuY3J5cHRvc3Rvcm0uaXM


## cs-nyc1

US - New York City, NY 1 DNSCrypt server provided by https://cryptostorm.is/

sdns://AQIAAAAAAAAADDIzLjE5LjI0NS44OCAxM3KtWVYywkFrhy8Jj4Ub3bllKExsvppPGQlkMNupWh4yLmRuc2NyeXB0LWNlcnQuY3J5cHRvc3Rvcm0uaXM


## cs-nyc2

US - New York City, NY 2 DNSCrypt server provided by https://cryptostorm.is/

sdns://AQIAAAAAAAAADDIzLjE5LjI0NS44NCAxM3KtWVYywkFrhy8Jj4Ub3bllKExsvppPGQlkMNupWh4yLmRuc2NyeXB0LWNlcnQuY3J5cHRvc3Rvcm0uaXM


## cs-ore

US - Oregon DNSCrypt server provided by https://cryptostorm.is/

sdns://AQIAAAAAAAAADTEwNC4yNTUuMTc1LjIgMTNyrVlWMsJBa4cvCY-FG925ZShMbL6aTxkJZDDbqVoeMi5kbnNjcnlwdC1jZXJ0LmNyeXB0b3N0b3JtLmlz


## cs-poland

Warsaw, Poland DNSCrypt server provided by https://cryptostorm.is/

sdns://AQIAAAAAAAAADTM3LjEyMC4yMTEuOTEgMTNyrVlWMsJBa4cvCY-FG925ZShMbL6aTxkJZDDbqVoeMi5kbnNjcnlwdC1jZXJ0LmNyeXB0b3N0b3JtLmlz


## cs-pt

Portugal DNSCrypt server provided by https://cryptostorm.is/

sdns://AQIAAAAAAAAADjkxLjIwNS4yMzAuMjI0IDEzcq1ZVjLCQWuHLwmPhRvduWUoTGy-mk8ZCWQw26laHjIuZG5zY3J5cHQtY2VydC5jcnlwdG9zdG9ybS5pcw


## cs-ro

Romania DNSCrypt server provided by https://cryptostorm.is/

sdns://AQIAAAAAAAAADTE0Ni43MC42Ni4yMjcgMTNyrVlWMsJBa4cvCY-FG925ZShMbL6aTxkJZDDbqVoeMi5kbnNjcnlwdC1jZXJ0LmNyeXB0b3N0b3JtLmlz


## cs-rome

Rome, Italy DNSCrypt server provided by https://cryptostorm.is/

sdns://AQIAAAAAAAAADjM3LjEyMC4yMDcuMTMxIDEzcq1ZVjLCQWuHLwmPhRvduWUoTGy-mk8ZCWQw26laHjIuZG5zY3J5cHQtY2VydC5jcnlwdG9zdG9ybS5pcw


## cs-sea

US - Seattle, WA DNSCrypt server provided by https://cryptostorm.is/

sdns://AQIAAAAAAAAADDY0LjEyMC41LjI1MSAxM3KtWVYywkFrhy8Jj4Ub3bllKExsvppPGQlkMNupWh4yLmRuc2NyeXB0LWNlcnQuY3J5cHRvc3Rvcm0uaXM


## cs-serbia

Belgrade, Serbia DNSCrypt server provided by https://cryptostorm.is/

sdns://AQIAAAAAAAAADjM3LjEyMC4xOTMuMjE5IDEzcq1ZVjLCQWuHLwmPhRvduWUoTGy-mk8ZCWQw26laHjIuZG5zY3J5cHQtY2VydC5jcnlwdG9zdG9ybS5pcw


## cs-sk

South Korea DNSCrypt server provided by https://cryptostorm.is/

sdns://AQIAAAAAAAAADzE3Mi4xMDcuMTU0LjIxMSAxM3KtWVYywkFrhy8Jj4Ub3bllKExsvppPGQlkMNupWh4yLmRuc2NyeXB0LWNlcnQuY3J5cHRvc3Rvcm0uaXM


## cs-slovakia

Bratislava, Slovakia DNSCrypt server provided by https://cryptostorm.is/

sdns://AQIAAAAAAAAADjE5My4zNy4yNTUuMjI3IDEzcq1ZVjLCQWuHLwmPhRvduWUoTGy-mk8ZCWQw26laHjIuZG5zY3J5cHQtY2VydC5jcnlwdG9zdG9ybS5pcw


## cs-swe

Sweden DNSCrypt server provided by https://cryptostorm.is/

sdns://AQIAAAAAAAAADzEyOC4xMjcuMTA0LjEwOCAxM3KtWVYywkFrhy8Jj4Ub3bllKExsvppPGQlkMNupWh4yLmRuc2NyeXB0LWNlcnQuY3J5cHRvc3Rvcm0uaXM


## cs-sydney

Sydney, Australia DNSCrypt server provided by https://cryptostorm.is/

sdns://AQIAAAAAAAAADjM3LjEyMC4yMzQuMjUxIDEzcq1ZVjLCQWuHLwmPhRvduWUoTGy-mk8ZCWQw26laHjIuZG5zY3J5cHQtY2VydC5jcnlwdG9zdG9ybS5pcw


## cs-tokyo

Tokyo, Japan DNSCrypt server provided by https://cryptostorm.is/

sdns://AQIAAAAAAAAADDE0Ni43MC4zMS40MyAxM3KtWVYywkFrhy8Jj4Ub3bllKExsvppPGQlkMNupWh4yLmRuc2NyeXB0LWNlcnQuY3J5cHRvc3Rvcm0uaXM


## cs-tx

US - Dallas, TX DNSCrypt server provided by https://cryptostorm.is/

sdns://AQIAAAAAAAAADTIwOS41OC4xNDcuMzYgMTNyrVlWMsJBa4cvCY-FG925ZShMbL6aTxkJZDDbqVoeMi5kbnNjcnlwdC1jZXJ0LmNyeXB0b3N0b3JtLmlz


## cs-tx2

US - Dallas, TX 2 DNSCrypt server provided by https://cryptostorm.is/

sdns://AQIAAAAAAAAACzQ1LjM1LjM1Ljk5IDEzcq1ZVjLCQWuHLwmPhRvduWUoTGy-mk8ZCWQw26laHjIuZG5zY3J5cHQtY2VydC5jcnlwdG9zdG9ybS5pcw


## cs-tx3

US - Dallas, TX 3 DNSCrypt server provided by https://cryptostorm.is/

sdns://AQIAAAAAAAAACzQ1LjM1LjcyLjQzIDEzcq1ZVjLCQWuHLwmPhRvduWUoTGy-mk8ZCWQw26laHjIuZG5zY3J5cHQtY2VydC5jcnlwdG9zdG9ybS5pcw


## cs-vancouver

Vancouver, Canada DNSCrypt server provided by https://cryptostorm.is/

sdns://AQIAAAAAAAAADDcxLjE5LjI1MS4zNCAxM3KtWVYywkFrhy8Jj4Ub3bllKExsvppPGQlkMNupWh4yLmRuc2NyeXB0LWNlcnQuY3J5cHRvc3Rvcm0uaXM


## dct-at1

DNSCrypt | IPv4 only | Non-logging | Non-filtering | DNSSEC | Vienna, Austria.

sdns://AQcAAAAAAAAADjQ2LjEwMi4xNTcuMTEwIPzthuna7r1J-i_Njw9AriFXZcuz9Lb406c1F9XLs56MFzIuZG5zY3J5cHQtY2VydC5kY3QtYXQx


## dct-de1

DNSCrypt | IPv4 only | Non-logging | Non-filtering | DNSSEC | Frankfurt, Germany.

sdns://AQcAAAAAAAAADzE0OS4xNTQuMTU5LjE5MSBCjJ9c_IkJLd7MVZP4wiqkOSy-sGt0GojSKJ48ztxbWRcyLmRuc2NyeXB0LWNlcnQuZGN0LWRlMQ


## dct-nl1

DNSCrypt | IPv4 only | Non-logging | Non-filtering | DNSSEC | Naaldwijk, Netherlands.

sdns://AQcAAAAAAAAAEzIzLjEzNy4yNDkuMTE2Ojg0NDMgEWD0g0vsKFqwslGBKql8eTiu1RvK2dzZIxLfR7ctlAwXMi5kbnNjcnlwdC1jZXJ0LmRjdC1ubDE


## dct-ru1

DNSCrypt | IPv4 only | Non-logging | Non-filtering | DNSSEC | Moscow, Russia.

sdns://AQcAAAAAAAAADTE4NS4yMi4xNTQuMTkgaWn7WaFj7FQw_9F1qge8LMND5xUdAtagWFZPPYRok1kXMi5kbnNjcnlwdC1jZXJ0LmRjdC1ydTE


## decloudus-nogoogle-tst

Servers helps you deGoogle and unGoogle by completely blocking Google tracking in addition to annoying ads, online trackers, and malware. Supports DNSSEC. No Logs.

Contributed by: https://decloudus.com

sdns://AQMAAAAAAAAAEjc4LjQ3LjIxMi4yMTE6OTQ0MyBNRN4TaVynkcwkVAbSBrCvr4X3c3Cygz_4VDUcRhhhYx4yLmRuc2NyeXB0LWNlcnQuRGVDbG91ZFVzLXRlc3Q


## decloudus-nogoogle-tstipv6

Servers helps you deGoogle and unGoogle by completely blocking Google tracking in addition to annoying ads, online trackers, and malware. Supports DNSSEC. No Logs. For IPv6.

Contributed by: https://decloudus.com

sdns://AQMAAAAAAAAAHFsyYTAxOjRmODoxM2E6MjUwYjo6MzBdOjk0NDMgTUTeE2lcp5HMJFQG0gawr6-F93NwsoM_-FQ1HEYYYWMeMi5kbnNjcnlwdC1jZXJ0LkRlQ2xvdWRVcy10ZXN0


## deffer-dns.au

DNSSEC/Non-logged/Uncensored in Sydney (AWS).
Encrypted DNS Server image by jedisct1, maintaned by DeffeR.

sdns://AQcAAAAAAAAADTUyLjY1LjIzNS4xMjkg5Q00RDDBkwx3fUaa0_etjz4iH3lLBOqsg95bYDmV07MdMi5kbnNjcnlwdC1jZXJ0LmRlZmZlci1kbnMuYXU


## dns.b33.network-dnscrypt

DNSCrypt | IPv4 only | Non-logging | DNSSEC | Blocks ads, malware, trackers, viruses, ransomware, telemetry and more | hosted on OVH | Location: Paris, France | Maintained by 0xb33 - (https://github.com/0xb33)

sdns://AQMAAAAAAAAAEjE2Mi4xOS4xMjkuMjA6NTQ0MyBLAxD2I-nLlzrjDQhX_eNLqCb-_DIIEiH7MBG2gbliLRsyLmRuc2NyeXB0LWNlcnQuYjMzLm5ldHdvcms


## dns.digitale-gesellschaft.ch

Public DoH resolver operated by the Digital Society (https://www.digitale-gesellschaft.ch).
Hosted in Zurich, Switzerland.

Non-logging, non-filtering, supports DNSSEC.

sdns://AgcAAAAAAAAADTE4NS45NS4yMTguNDKgzBBg05yDKbYrb7x9DW35MJhpuYHn5jktXNj6QI9NgOYgRE69Z7uD-IB7OSHpOKyReLiCvVCq2xEjHwRM9fCN984cZG5zLmRpZ2l0YWxlLWdlc2VsbHNjaGFmdC5jaAovZG5zLXF1ZXJ5


## dns.digitale-gesellschaft.ch-2

Public DoH resolver operated by the Digital Society (https://www.digitale-gesellschaft.ch).
Hosted in Zurich, Switzerland.

Non-logging, non-filtering, supports DNSSEC.

sdns://AgcAAAAAAAAADTE4NS45NS4yMTguNDOgzBBg05yDKbYrb7x9DW35MJhpuYHn5jktXNj6QI9NgOYgRE69Z7uD-IB7OSHpOKyReLiCvVCq2xEjHwRM9fCN984cZG5zLmRpZ2l0YWxlLWdlc2VsbHNjaGFmdC5jaAovZG5zLXF1ZXJ5


## dns.digitale-gesellschaft.ch-ipv6

Public IPv6 DoH resolver operated by the Digital Society (https://www.digitale-gesellschaft.ch).
Hosted in Zurich, Switzerland.

Non-logging, non-filtering, supports DNSSEC.

sdns://AgcAAAAAAAAAD1syYTA1OmZjODQ6OjQyXaDMEGDTnIMptitvvH0NbfkwmGm5gefmOS1c2PpAj02A5iBETr1nu4P4gHs5Iek4rJF4uIK9UKrbESMfBEz18I33zhxkbnMuZGlnaXRhbGUtZ2VzZWxsc2NoYWZ0LmNoCi9kbnMtcXVlcnk


## dns.digitale-gesellschaft.ch-ipv6-2

Public IPv6 DoH resolver operated by the Digital Society (https://www.digitale-gesellschaft.ch).
Hosted in Zurich, Switzerland.

Non-logging, non-filtering, supports DNSSEC.

sdns://AgcAAAAAAAAAD1syYTA1OmZjODQ6OjQzXaDMEGDTnIMptitvvH0NbfkwmGm5gefmOS1c2PpAj02A5iBETr1nu4P4gHs5Iek4rJF4uIK9UKrbESMfBEz18I33zhxkbnMuZGlnaXRhbGUtZ2VzZWxsc2NoYWZ0LmNoCi9kbnMtcXVlcnk


## dns.digitalsize.net

A public, non-tracking, non-filtering DNS resolver with DNSSEC enabled and hosted in Germany (https://dns.digitalsize.net)

sdns://AgcAAAAAAAAADjk0LjEzMC4xMzUuMjAzoMwQYNOcgym2K2-8fQ1t-TCYabmB5-Y5LVzY-kCPTYDmIEROvWe7g_iAezkh6TiskXi4gr1QqtsRIx8ETPXwjffOE2Rucy5kaWdpdGFsc2l6ZS5uZXQKL2Rucy1xdWVyeQ


## dns.digitalsize.net-ipv6

A public, non-tracking, non-filtering DNS resolver with DNSSEC enabled and hosted in Germany (https://dns.digitalsize.net)

sdns://AgcAAAAAAAAAGVsyYTAxOjRmODoxM2I6MzQwNzo6ZmFjZV2gzBBg05yDKbYrb7x9DW35MJhpuYHn5jktXNj6QI9NgOYgRE69Z7uD-IB7OSHpOKyReLiCvVCq2xEjHwRM9fCN984TZG5zLmRpZ2l0YWxzaXplLm5ldAovZG5zLXF1ZXJ5


## dns.ryan-palmer

Non-logging, non-filtering, DNSSEC DoH Server. Hosted in the UK.

sdns://AgcAAAAAAAAADjY4LjE4My4yNTMuMjAwoMwQYNOcgym2K2-8fQ1t-TCYabmB5-Y5LVzY-kCPTYDmIEROvWe7g_iAezkh6TiskXi4gr1QqtsRIx8ETPXwjffOFGRuczEucnlhbi1wYWxtZXIuY29tCi9kbnMtcXVlcnk


## dns.sb

DoH server runned by xTom.com. No logs, no filtering, supports DNSSEC.

Homepage: https://dns.sb

sdns://AgcAAAAAAAAADzE4NS4yMjIuMjIyLjIyMiCaOjT3J965vKUQA9nOnDn48n3ZxSQpAcK6saROY1oCGQ8xODUuMjIyLjIyMi4yMjIKL2Rucy1xdWVyeQ
sdns://AgcAAAAAAAAACzQ1LjExLjQ1LjExIJo6NPcn3rm8pRAD2c6cOfjyfdnFJCkBwrqxpE5jWgIZCzQ1LjExLjQ1LjExCi9kbnMtcXVlcnk


## dns.therifleman.name

DNS-over-HTTPS DNS forwarder from Mumbai, India.

Blocks web, Android trackers and ads.

Does not log client IP addresses, but logs queries for 24 hours for debugging
and delegates DNS resolution to the default Linode DNS server.

Report issues, and send suggestions to @ joker349 at protonmail.com.

Also supports DoT (for android) @ dns.therifleman.name and plain
DNS @ 172.104.206.174 (Note: because of spam bots mostly from USA,
plain DNS access is limited to India and Singapore for now. If you
are not from these countries and would like to access plain DNS, send
a request at aforementioned email address.

DoT and DoH are available world-wide.

sdns://AgMAAAAAAAAADzE3Mi4xMDQuMjA2LjE3NKDMEGDTnIMptitvvH0NbfkwmGm5gefmOS1c2PpAj02A5iBETr1nu4P4gHs5Iek4rJF4uIK9UKrbESMfBEz18I33zhRkbnMudGhlcmlmbGVtYW4ubmFtZQovZG5zLXF1ZXJ5


## dns.watch

Free, uncensored, non-logging server in Germany.
https://dns.watch

sdns://AQcAAAAAAAAADDg0LjIwMC43MC40MCBATVoA32LgIUTsC0hxmLlKGa_o5PRngHyldrEei5T5sCMyLmRuc2NyeXB0LWNlcnQucmVzb2x2ZXIyLmRucy53YXRjaA


## dns.watch-ipv6

Free, uncensored, non-logging server in Germany. IPv6 only.
https://dns.watch

sdns://AQcAAAAAAAAAHFsyMDAxOjE2MDg6MTA6MjU6OjkyNDk6ZDY5Yl0gQE1aAN9i4CFE7AtIcZi5Shmv6OT0Z4B8pXaxHouU-bAjMi5kbnNjcnlwdC1jZXJ0LnJlc29sdmVyMi5kbnMud2F0Y2g


## dns0

A free, sovereign and GDPR-compliant recursive DNS resolver with a
strong focus on security to protect the citizens and organizations of
the European Union.

Blocks new domains, dynamic DNS, parked domains, uncommon TLDs, etc.

https://www.dns0.eu/

sdns://AgMAAAAAAAAAACCaOjT3J965vKUQA9nOnDn48n3ZxSQpAcK6saROY1oCGQdkbnMwLmV1Ci9kbnMtcXVlcnk


## dns0-kids

A free, sovereign and GDPR-compliant recursive DNS resolver with a
strong focus on security to protect the citizens and organizations of
the European Union.

This version blocks content not suitable for children.

Also blocks new domains, dynamic DNS, parked domains, uncommon TLDs, etc.

https://www.dns0.eu/

sdns://AgMAAAAAAAAAACCaOjT3J965vKUQA9nOnDn48n3ZxSQpAcK6saROY1oCGQxraWRzLmRuczAuZXUKL2Rucy1xdWVyeQ


## dnscrypt-ch-blahdns-ipv4

Blocks ad and Tracking, no Logging, DNSSEC, Hosted in Switzerland. By https://blahdns.com/

sdns://AQMAAAAAAAAAETQ1LjkxLjkyLjEyMTo4NDQzIIUTqWvE4INLlQ1jtQLo0-LVTQSWayYCkzTpBx26I_wrGzIuZG5zY3J5cHQtY2VydC5ibGFoZG5zLmNvbQ


## dnscrypt-de-blahdns-ipv4

Blocks ad and Tracking, no Logging, DNSSEC, Hosted in Germany. By https://blahdns.com/

sdns://AQMAAAAAAAAAEjc4LjQ2LjI0NC4xNDM6ODQ0MyCFE6lrxOCDS5UNY7UC6NPi1U0ElmsmApM06QcduiP8KxsyLmRuc2NyeXB0LWNlcnQuYmxhaGRucy5jb20


## dnscrypt-de-blahdns-ipv6

Blocks ad and Tracking, no Logging, DNSSEC, Hosted in Germany. By https://blahdns.com/

sdns://AQMAAAAAAAAAG1syYTAxOjRmODpjMTc6ZWM2Nzo6MV06ODQ0MyCFE6lrxOCDS5UNY7UC6NPi1U0ElmsmApM06QcduiP8KxsyLmRuc2NyeXB0LWNlcnQuYmxhaGRucy5jb20


## dnscrypt.be

Resolver in Leuven, Belgium (UCLL Campus Proximus). Non-logging/DNSSEC/Uncensored. https://dnscrypt.be
Maintained by Sigfried (https://sigfried.be) hosted by ISW Leuven (https://iswleuven.be).

sdns://AQcAAAAAAAAADzE5My4xOTEuMTg3LjEwNyAzWmXOT_I8k2BKJzxIJ_iYoXRQRWcR0Q1FFyrJWtvogxsyLmRuc2NyeXB0LWNlcnQuZG5zY3J5cHQuYmU


## dnscrypt.ca-1

Free, Canadian, uncensored, no-logs, encrypted, and DNSSEC validated DNS service for your pleasure. https://dnscrypt.ca/

sdns://AQcAAAAAAAAADzE2Ny4xMTQuMjIwLjEyNSAaU6PJUHicvdELGTOkaJtshGpA8bc9F1KuysmCnst84h0yLmRuc2NyeXB0LWNlcnQuZG5zY3J5cHQuY2EtMQ


## dnscrypt.ca-1-doh

Free, Canadian, uncensored, no-logs, encrypted, and DNSSEC validated DNS service for your pleasure. https://dnscrypt.ca/

sdns://AgcAAAAAAAAAEzE2Ny4xMTQuMjIwLjEyNTo0NTOgzBBg05yDKbYrb7x9DW35MJhpuYHn5jktXNj6QI9NgOYgRE69Z7uD-IB7OSHpOKyReLiCvVCq2xEjHwRM9fCN984UZG5zMS5kbnNjcnlwdC5jYTo0NTMKL2Rucy1xdWVyeQ


## dnscrypt.ca-1-doh-ipv6

Free, Canadian, uncensored, no-logs, encrypted, and DNSSEC validated DNS service for your pleasure. https://dnscrypt.ca/

sdns://AgcAAAAAAAAAKVsyNjA3OjUzMDA6NjE6OTVmOjcyODM6MTFkOTpmODY6ZTY4OV06NDUzoMwQYNOcgym2K2-8fQ1t-TCYabmB5-Y5LVzY-kCPTYDmIEROvWe7g_iAezkh6TiskXi4gr1QqtsRIx8ETPXwjffOGWRuczEuaXB2Ni5kbnNjcnlwdC5jYTo0NTMKL2Rucy1xdWVyeQ


## dnscrypt.ca-1-ipv6

Free, Canadian, uncensored, no-logs, encrypted, and DNSSEC validated DNS service for your pleasure. https://dnscrypt.ca/

sdns://AQcAAAAAAAAAJVsyNjA3OjUzMDA6NjE6OTVmOjcyODM6MTFkOTpmODY6ZTY4OV0gINkZ1Ow8UAjNxwpR6itPy_6KmTxkMdDsaB1epzhFq4AiMi5kbnNjcnlwdC1jZXJ0LmRuc2NyeXB0LmNhLTEtaXB2Ng


## dnscrypt.ca-2

Free, Canadian, uncensored, no-logs, encrypted, and DNSSEC validated DNS service for your pleasure. https://dnscrypt.ca/

sdns://AQcAAAAAAAAADTE0OS41Ni4yMjguNDUgAQhUqztWp-7505FY_vaCC_-TojV8iRYI254V07vgEYUdMi5kbnNjcnlwdC1jZXJ0LmRuc2NyeXB0LmNhLTI


## dnscrypt.ca-2-doh

Free, Canadian, uncensored, no-logs, encrypted, and DNSSEC validated DNS service for your pleasure. https://dnscrypt.ca/

sdns://AgcAAAAAAAAAETE0OS41Ni4yMjguNDU6NDUzoMwQYNOcgym2K2-8fQ1t-TCYabmB5-Y5LVzY-kCPTYDmIEROvWe7g_iAezkh6TiskXi4gr1QqtsRIx8ETPXwjffOFGRuczIuZG5zY3J5cHQuY2E6NDUzCi9kbnMtcXVlcnk


## dnscrypt.ca-2-doh-ipv6

Free, Canadian, uncensored, no-logs, encrypted, and DNSSEC validated DNS service for your pleasure. https://dnscrypt.ca/

sdns://AgcAAAAAAAAAKVsyNjA3OjUzMDA6NjE6OTVmOjcyODM6MTFkOTpmODY6ZTY5MF06NDUzoMwQYNOcgym2K2-8fQ1t-TCYabmB5-Y5LVzY-kCPTYDmIEROvWe7g_iAezkh6TiskXi4gr1QqtsRIx8ETPXwjffOGWRuczIuaXB2Ni5kbnNjcnlwdC5jYTo0NTMKL2Rucy1xdWVyeQ


## dnscrypt.ca-2-ipv6

Free, Canadian, uncensored, no-logs, encrypted, and DNSSEC validated DNS service for your pleasure. https://dnscrypt.ca/

sdns://AQcAAAAAAAAAJVsyNjA3OjUzMDA6NjE6OTVmOjcyODM6MTFkOTpmODY6ZTY5MF0gmHxwqJfb2hUaNK1LVeqADvVhzASq1cV90sPYYfwX9CkiMi5kbnNjcnlwdC1jZXJ0LmRuc2NyeXB0LmNhLTItaXB2Ng


## dnscrypt.pl

Free | No filtering | Zero logs | DNSSEC | Poland | https://dnscrypt.pl/ | @dnscryptpl

sdns://AQcAAAAAAAAAFDE3OC4yMTYuMjAxLjEyODoyMDUzIH9hfLgepVPSNMSbwnnHT3tUmAUNHb8RGv7mmWPGR6FpGzIuZG5zY3J5cHQtY2VydC5kbnNjcnlwdC5wbA


## dnscrypt.pl-guardian

Free | Malware and phishing filtering | Zero logs | DNSSEC | Poland | https://dnscrypt.pl/ | @dnscryptpl

sdns://AQMAAAAAAAAAFDE3OC4yMTYuMjAxLjEyODoyMDU0IH9hfLgepVPSNMSbwnnHT3tUmAUNHb8RGv7mmWPGR6FpGzIuZG5zY3J5cHQtY2VydC5kbnNjcnlwdC5wbA


## dnscrypt.uk-doh-ipv4

DoH, no logs, uncensored, DNSSEC. Hosted in London UK on Digital Ocean
https://www.dnscrypt.uk

sdns://AgcAAAAAAAAADzE2NS4yMjcuMjMzLjIwMAATZG9oLmRuc2NyeXB0LnVrOjQ0MwovZG5zLXF1ZXJ5


## dnscrypt.uk-doh-ipv6

DoH, no logs, uncensored, DNSSEC. Hosted in London UK on Digital Ocean
https://www.dnscrypt.uk

sdns://AgcAAAAAAAAAGlsyYTAzOmIwYzA6MTpkMDo6ZWJlOmQwMDFdABNkb2guZG5zY3J5cHQudWs6NDQzCi9kbnMtcXVlcnk


## dnscrypt.uk-ipv4

DNSCrypt, no logs, uncensored, DNSSEC. Hosted in London UK on Digital Ocean
https://www.dnscrypt.uk

sdns://AQcAAAAAAAAADTE2NS4yMzIuMzIuOTUgAdMO6A4gTdoYcdOhDyhRVGdlvxS02kQEpP8EbX2paDwbMi5kbnNjcnlwdC1jZXJ0LmRuc2NyeXB0LnVr


## dnscrypt.uk-ipv6

DNSCrypt, no logs, uncensored, DNSSEC. Hosted in London UK on Digital Ocean
https://www.dnscrypt.uk

sdns://AQcAAAAAAAAAGlsyYTAzOmIwYzA6MTplMDo6NDg3OjEwMDFdIAHTDugOIE3aGHHToQ8oUVRnZb8UtNpEBKT_BG19qWg8GzIuZG5zY3J5cHQtY2VydC5kbnNjcnlwdC51aw


## dnsforfamily

(DNSCrypt Protocol) (Now supports DNSSEC). Block adult websites, gambling websites, malwares and advertisements.
It also enforces safe search in: Google, YouTube, Bing, DuckDuckGo and Yandex.

Social websites like Facebook and Instagram are not blocked. No DNS queries are logged.

As of 26-May-2022 5.9 million websites are blocked and new websites are added to blacklist daily.
Completely free, no ads or any commercial motive. Operating for 4 years now.

Warning: This server is incompatible with anonymization.

Provided by: https://dnsforfamily.com

sdns://AQMAAAAAAAAADDc4LjQ3LjY0LjE2MSATJeLOABXNSYcSJIoqR5_iUYz87Y4OecMLB84aEAKPrRBkbnNmb3JmYW1pbHkuY29t


## dnsforfamily-doh

(DoH Protocol) (Now supports DNSSEC). Block adult websites, gambling websites, malwares and advertisements.
It also enforces safe search in: Google, YouTube, Bing, DuckDuckGo and Yandex.

Social websites like Facebook and Instagram are not blocked. No DNS queries are logged.

As of 26-May-2022 5.9 million websites are blocked and new websites are added to blacklist daily.
Completely free, no ads or any commercial motive. Operating for 4 years now.

Provided by: https://dnsforfamily.com

sdns://AgMAAAAAAAAADzE2Ny4yMzUuMjM2LjEwN6DMEGDTnIMptitvvH0NbfkwmGm5gefmOS1c2PpAj02A5iBETr1nu4P4gHs5Iek4rJF4uIK9UKrbESMfBEz18I33zhhkbnMtZG9oLmRuc2ZvcmZhbWlseS5jb20KL2Rucy1xdWVyeQ


## dnsforfamily-doh-no-safe-search

(DoH Protocol) (Now supports DNSSEC) Block adult websites, gambling websites, malwares and advertisements.
Unlike other dnsforfamily servers, this one does not enforces safe search. So Google, YouTube, Bing, DuckDuckGo and Yandex are completely accessible without any restriction.

Social websites like Facebook and Instagram are not blocked. No DNS queries are logged.

As of 26-May-2022 5.9 million websites are blocked and new websites are added to blacklist daily.
Completely free, no ads or any commercial motive. Operating for 4 years now.

Warning: This server is incompatible with anonymization.

Provided by: https://dnsforfamily.com

sdns://AgMAAAAAAAAADzE2Ny4yMzUuMjM2LjEwN6DMEGDTnIMptitvvH0NbfkwmGm5gefmOS1c2PpAj02A5iBETr1nu4P4gHs5Iek4rJF4uIK9UKrbESMfBEz18I33zidkbnMtZG9oLW5vLXNhZmUtc2VhcmNoLmRuc2ZvcmZhbWlseS5jb20KL2Rucy1xdWVyeQ


## dnsforfamily-no-safe-search

(DNSCrypt Protocol) (Now supports DNSSEC) Block adult websites, gambling websites, malwares and advertisements.
Unlike other dnsforfamily servers, this one does not enforces safe search. So Google, YouTube, Bing, DuckDuckGo and Yandex are completely accessible without any restriction.

Social websites like Facebook and Instagram are not blocked. No DNS queries are logged.

As of 26-May-2022 5.9 million websites are blocked and new websites are added to blacklist daily.
Completely free, no ads or any commercial motive. Operating for 4 years now.

Warning: This server is incompatible with anonymization.

Provided by: https://dnsforfamily.com

sdns://AQMAAAAAAAAADzEzNS4xODEuMTkzLjIyMiDrxcZ_hFtGE6tfATvQZYjxgl5pTY_e2cRH_ms8bEWofBBkbnNmb3JmYW1pbHkuY29t


## dnsforfamily-v6

(DNSCrypt Protocol) (Now supports DNSSEC) Block adult websites, gambling websites, malwares and advertisements.
It also enforces safe search in: Google, YouTube, Bing, DuckDuckGo and Yandex.

Social websites like Facebook and Instagram are not blocked. No DNS queries are logged.

As of 26-May-2022 5.9 million websites are blocked and new websites are added to blacklist daily.
Completely free, no ads or any commercial motive. Operating for 4 years now.

Provided by: https://dnsforfamily.com

sdns://AQMAAAAAAAAAF1syYTAxOjRmODoxYzE3OjRkZjg6OjFdIBMl4s4AFc1JhxIkiipHn-JRjPztjg55wwsHzhoQAo-tEGRuc2ZvcmZhbWlseS5jb20


## dnsforge.de

Public DoH resolver running with Pihole for Adblocking (https://dnsforge.de).

Non-logging, AD-filtering, supports DNSSEC. Hosted in Germany.

sdns://AgMAAAAAAAAADDE3Ni45LjkzLjE5OKDMEGDTnIMptitvvH0NbfkwmGm5gefmOS1c2PpAj02A5iBETr1nu4P4gHs5Iek4rJF4uIK9UKrbESMfBEz18I33zgtkbnNmb3JnZS5kZQovZG5zLXF1ZXJ5


## dnslow.me

dnslow.me is an open source project, also your advertisement and threat blocking, privacy-first, encrypted DNS.

All DNS requests will be protected with threat-intelligence feeds and randomly distributed to some other DNS resolvers.

More info on the [homepage](https://dnslow.me) and [GitHub](https://github.com/PeterDaveHello/dnslow.me)

sdns://AgAAAAAAAAAAAKDMEGDTnIMptitvvH0NbfkwmGm5gefmOS1c2PpAj02A5iBETr1nu4P4gHs5Iek4rJF4uIK9UKrbESMfBEz18I33zglkbnNsb3cubWUKL2Rucy1xdWVyeQ


## dnspod

A public DNS resolver that supports DoH/DoT in mainland China, provided by dnspod/Tencent-cloud.

Warning: GFW filtering rules are applied by that resolver.

Homepage: https://dnspod.cn/

sdns://AgAAAAAAAAAACjEuMTIuMTIuMTIgD3COiTWYzhCaz4188tVyp8i8EAR0UYsu0tkTgK_E7aYHZG9oLnB1YgovZG5zLXF1ZXJ5


## dnspod-doh

DoH server runned by Tencent's DNSPod, has logs, support DNSSEC. China's GFW filtering rules are applied.

Homepage: https://www.dnspod.cn/Products/publicdns

sdns://AgEAAAAAAAAAACDBlAfoWsQD52fP2oOBh_Ag-lY6yBaIr1EMIqd559RaVgdkb2gucHViCi9kbnMtcXVlcnk


## dnswarden-adult-doh

Blocks adult content and enforces safe search on major search engines.
For further customization look here: https://dnswarden.com/customfilter.html

sdns://AgMAAAAAAAAAAKDMEGDTnIMptitvvH0NbfkwmGm5gefmOS1c2PpAj02A5iBETr1nu4P4gHs5Iek4rJF4uIK9UKrbESMfBEz18I33zhFkbnMuZG5zd2FyZGVuLmNvbQwvYWR1bHRmaWx0ZXI


## dnswarden-uncensor-dc

Hosted in multiple locations.
For more information look at https://github.com/bhanupratapys/dnswarden or https://dnswarden.com
Note: Anonymized DNS may not work for this server.

sdns://AQcAAAAAAAAADDEzNy42Ni42LjE0NiDg_LCuCApY3CtucAKfyQyqk3g9NAq607r906qVDWVBLiwyLmRuc2NyeXB0LWNlcnQuZG5zd2FyZGVuLXVuY2Vuc29yZWQtYW55Y2FzdA


## dnswarden-uncensor-dc-swiss

Hosted in switzerland.
For more information look at https://github.com/bhanupratapys/dnswarden or https://dnswarden.com

sdns://AQcAAAAAAAAAFDE4OC4yNDQuMTE3LjExNDoxNDQzIOK0J6XON4YjPmXjlonI5Lx0ZenB5Din7hrX-8uYlDxHKjIuZG5zY3J5cHQtY2VydC5kbnN3YXJkZW4tdW5jZW5zb3JlZC1zd2lzcw


## doh-cleanbrowsing-adult

Blocks access to all adult, pornographic and explicit sites. It does
not block proxy or VPNs, nor mixed-content sites. Sites like Reddit
are allowed. Google and Bing are set to the Safe Mode.

By https://cleanbrowsing.org/

sdns://AgMAAAAAAAAAAAAVZG9oLmNsZWFuYnJvd3Npbmcub3JnEi9kb2gvYWR1bHQtZmlsdGVyLw


## doh-cleanbrowsing-family

Blocks access to all adult, pornographic and explicit sites. It also
blocks proxy and VPN domains that are used to bypass the filters.
Mixed content sites (like Reddit) are also blocked. Google, Bing and
Youtube are set to the Safe Mode.

By https://cleanbrowsing.org/

sdns://AgMAAAAAAAAAAAAVZG9oLmNsZWFuYnJvd3Npbmcub3JnEy9kb2gvZmFtaWx5LWZpbHRlci8


## doh-cleanbrowsing-security

Block access to phishing, malware and malicious domains. It does not block adult content.
By https://cleanbrowsing.org/

sdns://AgMAAAAAAAAAAAAVZG9oLmNsZWFuYnJvd3Npbmcub3JnFS9kb2gvc2VjdXJpdHktZmlsdGVyLw


## doh-crypto-sx

DNS-over-HTTPS server. Anycast, no logs, no censorship, DNSSEC.
Backend hosted by Scaleway, globally cached via Cloudflare.
Maintained by Frank Denis.

sdns://AgcAAAAAAAAACzEwNC4yMS42Ljc4AA1kb2guY3J5cHRvLnN4Ci9kbnMtcXVlcnk
sdns://AgcAAAAAAAAADjE3Mi42Ny4xMzQuMTU3AA1kb2guY3J5cHRvLnN4Ci9kbnMtcXVlcnk


## doh-crypto-sx-ipv6

DNS-over-HTTPS server accessible over IPv6. Anycast, no logs, no censorship, DNSSEC.
Backend hosted by Scaleway, globally cached via Cloudflare.
Maintained by Frank Denis.

sdns://AgcAAAAAAAAAGlsyNjA2OjQ3MDA6MzAzNzo6NjgxNTo2NGVdABJkb2gtaXB2Ni5jcnlwdG8uc3gKL2Rucy1xdWVyeQ
sdns://AgcAAAAAAAAAG1syNjA2OjQ3MDA6MzAzNjo6YWM0Mzo4NjlkXQASZG9oLWlwdjYuY3J5cHRvLnN4Ci9kbnMtcXVlcnk


## doh-ibksturm

DoH & DoT Server, No Logging, No Filters, DNSSEC

Running privately by ibksturm in Thurgau, Switzerland

sdns://AgcAAAAAAAAAAKDMEGDTnIMptitvvH0NbfkwmGm5gefmOS1c2PpAj02A5iBETr1nu4P4gHs5Iek4rJF4uIK9UKrbESMfBEz18I33zhRpYmtzdHVybS5zeW5vbG9neS5tZQovZG5zLXF1ZXJ5


## doh-jp-blahdns

Blocks ad and Tracking, no Logging, DNSSEC, Hosted in Japan. By https://blahdns.com/

sdns://AgMAAAAAAAAADDIxMi41Mi4wLjEyMiC00mapDYeq93KU38D1wQdQ8CGA8TJtF_1fknJi-UdrxBJkb2gtanAuYmxhaGRucy5jb20KL2Rucy1xdWVyeQ


## doh.appliedprivacy.net

Public DoH resolver operated by the Foundation for Applied Privacy (https://appliedprivacy.net).
Hosted in Vienna, Austria.

Non-logging, non-filtering, supports DNSSEC.

sdns://AgcAAAAAAAAAAKDMEGDTnIMptitvvH0NbfkwmGm5gefmOS1c2PpAj02A5iBETr1nu4P4gHs5Iek4rJF4uIK9UKrbESMfBEz18I33zhZkb2guYXBwbGllZHByaXZhY3kubmV0Bi9xdWVyeQ


## doh.ffmuc.net

An open (non-logging, non-filtering, non-censoring) DoH resolver operated by Freifunk Munich with nodes in DE.
https://ffmuc.net/

sdns://AgcAAAAAAAAACjUuMS42Ni4yNTWgzBBg05yDKbYrb7x9DW35MJhpuYHn5jktXNj6QI9NgOYgRE69Z7uD-IB7OSHpOKyReLiCvVCq2xEjHwRM9fCN984NZG9oLmZmbXVjLm5ldAovZG5zLXF1ZXJ5


## doh.ffmuc.net-2

An open (non-logging, non-filtering, non-censoring) DoH resolver operated by Freifunk Munich with nodes in DE.
https://ffmuc.net/

sdns://AgcAAAAAAAAADjE4NS4xNTAuOTkuMjU1oMwQYNOcgym2K2-8fQ1t-TCYabmB5-Y5LVzY-kCPTYDmIEROvWe7g_iAezkh6TiskXi4gr1QqtsRIx8ETPXwjffODWRvaC5mZm11Yy5uZXQKL2Rucy1xdWVyeQ


## doh.ffmuc.net-v6

An open (non-logging, non-filtering, non-censoring) DoH resolver operated by Freifunk Munich with nodes in DE.
https://ffmuc.net/

sdns://AgcAAAAAAAAAFVsyMDAxOjY3ODplNjg6ZjAwMDo6XaDMEGDTnIMptitvvH0NbfkwmGm5gefmOS1c2PpAj02A5iBETr1nu4P4gHs5Iek4rJF4uIK9UKrbESMfBEz18I33zg1kb2guZmZtdWMubmV0Ci9kbnMtcXVlcnk


## doh.ffmuc.net-v6-2

An open (non-logging, non-filtering, non-censoring) DoH resolver operated by Freifunk Munich with nodes in DE.
https://ffmuc.net/

sdns://AgcAAAAAAAAAFVsyMDAxOjY3ODplZDA6ZjAwMDo6XaDMEGDTnIMptitvvH0NbfkwmGm5gefmOS1c2PpAj02A5iBETr1nu4P4gHs5Iek4rJF4uIK9UKrbESMfBEz18I33zg1kb2guZmZtdWMubmV0Ci9kbnMtcXVlcnk


## doh.tiarap.org

Non-Logging DNS-over-HTTPS server, cached via Cloudflare.
Filters out ads, trackers and malware, NO ECS, supports DNSSEC.

sdns://AgMAAAAAAAAADDEwNC4yMS42NS42MAAOZG9oLnRpYXJhcC5vcmcKL2Rucy1xdWVyeQ


## doh.tiarap.org-ipv6

Non-Logging DNS-over-HTTPS server (IPv6), cached via Cloudflare.
Filters out ads, trackers and malware, NO ECS, supports DNSSEC.

sdns://AgMAAAAAAAAAG1syNjA2OjQ3MDA6MzAzNDo6NjgxNTo0MTNjXQAOZG9oLnRpYXJhcC5vcmcKL2Rucy1xdWVyeQ


## e-utp.net-ipv6-doh

e-utp.net DNS Cache service, only accessible over IPv6
https://fido.e-utp.net/display/EUTPNET/Recursive+DNS

sdns://AgcAAAAAAAAAE1syMDAxOjY3YzoyMWVjOjo1M10gXMJdnIoy7PLLu5Hr9wvZVsUgOfnyDoQJ2mFUcVI21x0SZG5zY2FjaGUuZS11dHAubmV0Ci9kbnMtcXVlcnk


## faelix-ch-ipv4

An open (non-logging, non-filtering, no ECS) DNSCrypt resolver operated by https://faelix.net/ with IPv4 nodes anycast within AS41495 in Switzerland.

sdns://AQYAAAAAAAAAEzE4NS4xMzQuMTk2LjU0Ojg0NDMgfsvvPi8BgDKNYODh0ewj5Oh32OoJoZNwGgTWs8C-i-EfMi5kbnNjcnlwdC1jZXJ0LnJkbnMuZmFlbGl4Lm5ldA
sdns://AQYAAAAAAAAAEzE4NS4xMzQuMTk2LjU1Ojg0NDMgfsvvPi8BgDKNYODh0ewj5Oh32OoJoZNwGgTWs8C-i-EfMi5kbnNjcnlwdC1jZXJ0LnJkbnMuZmFlbGl4Lm5ldA


## faelix-uk-ipv4

An open (non-logging, non-filtering, no ECS) DNSCrypt resolver operated by https://faelix.net/ with IPv4 nodes anycast within AS41495 in the UK.

sdns://AQYAAAAAAAAAEjQ2LjIyNy4yMDAuNTQ6ODQ0MyB-y-8-LwGAMo1g4OHR7CPk6HfY6gmhk3AaBNazwL6L4R8yLmRuc2NyeXB0LWNlcnQucmRucy5mYWVsaXgubmV0


## faelix-uk-ipv6

An open (non-logging, non-filtering, no ECS) DNSCrypt resolver operated by https://faelix.net/ with IPv6 nodes anycast within AS41495 in the UK.

sdns://AQYAAAAAAAAAFFsyYTAxOjllMDA6OjU0XTo4NDQzIH7L7z4vAYAyjWDg4dHsI-Tod9jqCaGTcBoE1rPAvovhHzIuZG5zY3J5cHQtY2VydC5yZG5zLmZhZWxpeC5uZXQ
sdns://AQYAAAAAAAAAFFsyYTAxOjllMDA6OjU1XTo4NDQzIH7L7z4vAYAyjWDg4dHsI-Tod9jqCaGTcBoE1rPAvovhHzIuZG5zY3J5cHQtY2VydC5yZG5zLmZhZWxpeC5uZXQ


## ffmuc.net

An open (non-logging, non-filtering, non-censoring) DNSCrypt resolver operated by Freifunk Munich with nodes in DE.
https://ffmuc.net/

sdns://AQcAAAAAAAAADzUuMS42Ni4yNTU6ODQ0MyAH0Hrxz9xdmXadPwJmkKcESWXCdCdseRyu9a7zuQxG-hkyLmRuc2NyeXB0LWNlcnQuZmZtdWMubmV0


## ffmuc.net-v6

An open (non-logging, non-filtering, non-censoring) DNSCrypt resolver operated by Freifunk Munich with nodes in DE.
https://ffmuc.net/

sdns://AQcAAAAAAAAAGlsyMDAxOjY3ODplNjg6ZjAwMDo6XTo4NDQzIAfQevHP3F2Zdp0_AmaQpwRJZcJ0J2x5HK71rvO5DEb6GTIuZG5zY3J5cHQtY2VydC5mZm11Yy5uZXQ


## google

Google DNS (anycast)

sdns://AgUAAAAAAAAABzguOC44LjigHvYkz_9ea9O63fP92_3qVlRn43cpncfuZnUWbzAMwbmgdoAkR6AZkxo_AEMExT_cbBssN43Evo9zs5_ZyWnftEUgalBisNF41VbxY7E7Gw8ZQ10CWIKRzHVYnf7m6xHI1cMKZG5zLmdvb2dsZQovZG5zLXF1ZXJ5


## google-ipv6

Google DNS (anycast)

sdns://AgUAAAAAAAAAFlsyMDAxOjQ4NjA6NDg2MDo6ODg4OF2gHvYkz_9ea9O63fP92_3qVlRn43cpncfuZnUWbzAMwbmgdoAkR6AZkxo_AEMExT_cbBssN43Evo9zs5_ZyWnftEUgalBisNF41VbxY7E7Gw8ZQ10CWIKRzHVYnf7m6xHI1cMKZG5zLmdvb2dsZQovZG5zLXF1ZXJ5


## he

Hurricane Electric DoH server (anycast)

Unknown logging policy.

sdns://AgUAAAAAAAAACzc0LjgyLjQyLjQyoMwQYNOcgym2K2-8fQ1t-TCYabmB5-Y5LVzY-kCPTYDmIEROvWe7g_iAezkh6TiskXi4gr1QqtsRIx8ETPXwjffODG9yZG5zLmhlLm5ldAovZG5zLXF1ZXJ5


## ibksturm

DNSCRYPT V2 Server, No Logging, No Filters, DNSSEC

Running privately by ibksturm in Thurgau, Switzerland

sdns://AQcAAAAAAAAAEzIxMy4xOTYuMTkxLjk2Ojg0NDMgHK0AUhqiLSuBFR07jpBhKvko_oyqyWnot8z4cce7cKkYMi5kbnNjcnlwdC1jZXJ0Lmlia3N0dXJt


## id-gmail

Non-Logging DNSCrypt server located in Singapore.
Filters out ads, trackers and malware, supports DNSSEC, provided by id-gmail.

sdns://AQMAAAAAAAAADjE3NC4xMzguMjEuMTI4IO-WgGbo2ZTwZdg-3dMa7u31bYZXRj5KykfN1_6Xw9T2HDIuZG5zY3J5cHQtY2VydC5kbnMudGlhci5hcHA


## id-gmail-doh

Non-Logging DNS-over-HTTPS server located in Singapore.
Filters out ads, trackers and malware, supports DNSSEC, provided by id-gmail.

sdns://AgMAAAAAAAAADjE3NC4xMzguMjkuMTc1oMwQYNOcgym2K2-8fQ1t-TCYabmB5-Y5LVzY-kCPTYDmIEROvWe7g_iAezkh6TiskXi4gr1QqtsRIx8ETPXwjffODGRvaC50aWFyLmFwcAovZG5zLXF1ZXJ5


## id-gmail-doh-ipv6

Non-Logging DNS-over-HTTPS (IPv6) server located in Singapore.
Filters out ads, trackers and malware, supports DNSSEC, provided by id-gmail.

sdns://AgMAAAAAAAAAG1syNDAwOjYxODA6MDpkMDo6NWY3Mzo0MDAxXaDMEGDTnIMptitvvH0NbfkwmGm5gefmOS1c2PpAj02A5iBETr1nu4P4gHs5Iek4rJF4uIK9UKrbESMfBEz18I33zgxkb2gudGlhci5hcHAKL2Rucy1xdWVyeQ


## id-gmail-ipv6

Non-Logging DNSCrypt (IPv6) server located in Singapore.
Filters out ads, trackers and malware, supports DNSSEC, provided by id-gmail.

sdns://AQMAAAAAAAAAG1syNDAwOjYxODA6MDpkMDo6NWY2ZTo0MDAxXSDvloBm6NmU8GXYPt3TGu7t9W2GV0Y-SspHzdf-l8PU9hwyLmRuc2NyeXB0LWNlcnQuZG5zLnRpYXIuYXBw


## iij

DoH server operated by Internet Initiative Japan in Tokyo. Blocks child pornography.
https://www.iij.ad.jp/

sdns://AgEAAAAAAAAACjEwMy4yLjU3LjUgmOPV5TavKVjNL38U9wTvSidtJeM81l8uZfXk8nJ8EzARcHVibGljLmRucy5paWouanAKL2Rucy1xdWVyeQ


## jp.tiar.app

Non-Logging, Non-Filtering DNSCrypt server in Japan.
No ECS, Support DNSSEC

sdns://AQcAAAAAAAAAEjE3Mi4xMDQuOTMuODA6MTQ0MyAyuHY-8b9lNqHeahPAzW9IoXnjiLaZpTeNbVs8TN9UUxsyLmRuc2NyeXB0LWNlcnQuanAudGlhci5hcHA


## jp.tiar.app-doh

Non-Logging, Non-Filtering DNS-over-HTTPS server in Japan.
No ECS, Support DNSSEC

sdns://AgcAAAAAAAAADTE3Mi4xMDQuOTMuODCgzBBg05yDKbYrb7x9DW35MJhpuYHn5jktXNj6QI9NgOYgRE69Z7uD-IB7OSHpOKyReLiCvVCq2xEjHwRM9fCN984LanAudGlhci5hcHAKL2Rucy1xdWVyeQ


## jp.tiar.app-doh-ipv6

Non-Logging, Non-Filtering DNS-over-HTTPS (IPv6) server in Japan.
No ECS, Support DNSSEC

sdns://AgcAAAAAAAAAIFsyNDAwOjg5MDI6OmYwM2M6OTFmZjpmZWRhOmM1MTRdoMwQYNOcgym2K2-8fQ1t-TCYabmB5-Y5LVzY-kCPTYDmIEROvWe7g_iAezkh6TiskXi4gr1QqtsRIx8ETPXwjffOC2pwLnRpYXIuYXBwCi9kbnMtcXVlcnk


## jp.tiar.app-ipv6

Non-Logging, Non-Filtering DNSCrypt (IPv6) server in Japan.
No ECS, Support DNSSEC

sdns://AQcAAAAAAAAAJVsyNDAwOjg5MDI6OmYwM2M6OTFmZjpmZWRhOmM1MTRdOjE0NDMgMrh2PvG_ZTah3moTwM1vSKF544i2maU3jW1bPEzfVFMbMi5kbnNjcnlwdC1jZXJ0LmpwLnRpYXIuYXBw


## jp.tiarap.org

DNS-over-HTTPS Server. Non-Logging, Non-Filtering, No ECS, Support DNSSEC.
Cached via Cloudflare.

sdns://AgcAAAAAAAAAAAANanAudGlhcmFwLm9yZwovZG5zLXF1ZXJ5


## jp.tiarap.org-ipv6

DNS-over-HTTPS Server (IPv6). Non-Logging, Non-Filtering, No ECS, Support DNSSEC.
Cached via Cloudflare.

sdns://AgcAAAAAAAAAG1syNjA2OjQ3MDA6MzAzMDo6YWM0MzphZDNiXQANanAudGlhcmFwLm9yZwovZG5zLXF1ZXJ5


## libredns

DoH server in Germany. No logging, but no DNS padding and no DNSSEC support.
https://libredns.gr/

sdns://AgYAAAAAAAAADjExNi4yMDIuMTc2LjI2oMwQYNOcgym2K2-8fQ1t-TCYabmB5-Y5LVzY-kCPTYDmIEROvWe7g_iAezkh6TiskXi4gr1QqtsRIx8ETPXwjffOD2RvaC5saWJyZWRucy5ncgovZG5zLXF1ZXJ5


## libredns-noads

DoH server in Germany. No logging, but no DNS padding and no DNSSEC support.
no ads version, uses StevenBlack's host list: https://github.com/StevenBlack/hosts

sdns://AgIAAAAAAAAADjExNi4yMDIuMTc2LjI2oMwQYNOcgym2K2-8fQ1t-TCYabmB5-Y5LVzY-kCPTYDmIEROvWe7g_iAezkh6TiskXi4gr1QqtsRIx8ETPXwjffOD2RvaC5saWJyZWRucy5ncgQvYWRz


## meganerd

DNSCrypt server by MegaNerd.nl (IPv4) - https://meganerd.nl/encrypted-dns-server
Hosted in Amsterdam (AMS1), The Netherlands.

Non-logging, non-filtering, supports DNSSEC.

sdns://AQcAAAAAAAAADjEzNi4yNDQuOTcuMTE0ICif6V9M6EF_9Xo_MHwkDN4ZJjERopSJN8hBuUWg9YeMJTIuZG5zY3J5cHQtY2VydC5jaGV3YmFjY2EubWVnYW5lcmQubmw


## meganerd-doh-ipv4

DoH server by MegaNerd.nl (IPv4) - https://meganerd.nl/encrypted-dns-server
Hosted in Amsterdam (AMS1), The Netherlands.

Non-logging, non-filtering, supports DNSSEC.

sdns://AgcAAAAAAAAADjEzNi4yNDQuOTcuMTE0IFkaneMM4pPbY6hfvwOotK0c18K3ichOc9LzR0pw9zdAFWNoZXdiYWNjYS5tZWdhbmVyZC5ubAovZG5zLXF1ZXJ5


## meganerd-doh-ipv6

DoH server by MegaNerd.nl (IPv6) - https://meganerd.nl/encrypted-dns-server
Hosted in Amsterdam (AMS1), The Netherlands.

Non-logging, non-filtering, supports DNSSEC.

sdns://AgcAAAAAAAAAKFsyMDAxOjE5ZjA6NTAwMTpjYmI6NTQwMDowM2ZmOmZlMDc6ZjcwZF0gWRqd4wzik9tjqF-_A6i0rRzXwreJyE5z0vNHSnD3N0AVY2hld2JhY2NhLm1lZ2FuZXJkLm5sCi9kbnMtcXVlcnk


## meganerd-ipv6

DNSCrypt server by MegaNerd.nl (IPv6) - https://meganerd.nl/encrypted-dns-server
Hosted in Amsterdam (AMS1), The Netherlands.

Non-logging, non-filtering, supports DNSSEC.

sdns://AQcAAAAAAAAAJ1syMDAxOjE5ZjA6NTAwMTpjYmI6NTQwMDozZmY6ZmUwNzpmNzBkXSAon-lfTOhBf_V6PzB8JAzeGSYxEaKUiTfIQblFoPWHjCUyLmRuc2NyeXB0LWNlcnQuY2hld2JhY2NhLm1lZ2FuZXJkLm5s


## mullvad-adblock-doh

Public ad-blocking, non-logging (audited), DNSSEC-capable, DNS-over-HTTPS resolver hosted by VPN provider Mullvad
Anycast IPv4/IPv6 with servers in SE, DE, UK, US, AU and SG
https://mullvad.net/en/help/dns-over-https-and-dns-over-tls/

sdns://AgMAAAAAAAAAAAAXYWRibG9jay5kb2gubXVsbHZhZC5uZXQKL2Rucy1xdWVyeQ


## mullvad-doh

Public non-filtering, non-logging (audited), DNSSEC-capable, DNS-over-HTTPS resolver hosted by VPN provider Mullvad
Anycast IPv4/IPv6 with servers in SE, DE, UK, US, AU and SG
https://mullvad.net/en/help/dns-over-https-and-dns-over-tls/

sdns://AgcAAAAAAAAAAAAPZG9oLm11bGx2YWQubmV0Ci9kbnMtcXVlcnk


## nextdns

NextDNS is a cloud-based private DNS service that gives you full control
over what is allowed and what is blocked on the Internet.

DNSSEC, Anycast, Non-logging, NoFilters

https://www.nextdns.io/

sdns://AgcAAAAAAAAACjQ1LjkwLjMwLjAgmjo09yfeubylEAPZzpw5-PJ92cUkKQHCurGkTmNaAhkWYW55Y2FzdC5kbnMubmV4dGRucy5pbwovZG5zLXF1ZXJ5


## nextdns-ipv6

Connects to NextDNS over IPv6.

NextDNS is a cloud-based private DNS service that gives you full control
over what is allowed and what is blocked on the Internet.

DNSSEC, Anycast, Non-logging, NoFilters

https://www.nextdns.io/

sdns://AgcAAAAAAAAADVsyYTA3OmE4YzA6Ol0gmjo09yfeubylEAPZzpw5-PJ92cUkKQHCurGkTmNaAhkWYW55Y2FzdC5kbnMubmV4dGRucy5pbwovZG5zLXF1ZXJ5


## nextdns-ultralow

NextDNS is a cloud-based private DNS service that gives you full control
over what is allowed and what is blocked on the Internet.

https://www.nextdns.io/

To select the server location, the "-ultralow" variant relies on bootstrap servers
instead of anycast.

sdns://AgcAAAAAAAAAACCaOjT3J965vKUQA9nOnDn48n3ZxSQpAcK6saROY1oCGQ5kbnMubmV4dGRucy5pbw8vZG5zY3J5cHQtcHJveHk


## njalla-doh

Non-logging DoH server in Sweden operated by Njalla.

https://dns.njal.la/

sdns://AgcAAAAAAAAADDk1LjIxNS4xOS41M6DMEGDTnIMptitvvH0NbfkwmGm5gefmOS1c2PpAj02A5iBETr1nu4P4gHs5Iek4rJF4uIK9UKrbESMfBEz18I33zgtkbnMubmphbC5sYQovZG5zLXF1ZXJ5


## openinternet

DNSCrypt resolver colocated at Sonic.net in Santa Rosa, CA in the United States.
No log, no filter, DNSSEC. Provided by https://openinternet.io

sdns://AQcAAAAAAAAADTcwLjM2LjE3MC4xMjYgHRhodSnh6n0lyl8T0d5e2OSapsrl455sspOSW_cLlQ0cMi5kbnNjcnlwdC1jZXJ0Lm9wZW5pbnRlcm5ldA


## opennameserver-2-doh

OpenNIC • DoH • DoT • DNSSEC • No Logging • Uncensored - https://opennameserver.org

sdns://AgcAAAAAAAAAAKDMEGDTnIMptitvvH0NbfkwmGm5gefmOS1c2PpAj02A5iBETr1nu4P4gHs5Iek4rJF4uIK9UKrbESMfBEz18I33zhZuczIub3Blbm5hbWVzZXJ2ZXIub3JnCi9kbnMtcXVlcnk


## opennameserver-3-doh

OpenNIC • DoH • DoT • DNSSEC • No Logging • Uncensored - https://opennameserver.org

sdns://AgcAAAAAAAAAAKDMEGDTnIMptitvvH0NbfkwmGm5gefmOS1c2PpAj02A5iBETr1nu4P4gHs5Iek4rJF4uIK9UKrbESMfBEz18I33zhZuczMub3Blbm5hbWVzZXJ2ZXIub3JnCi9kbnMtcXVlcnk


## opennameserver-4-doh

OpenNIC • DoH • DoT • DNSSEC • No Logging • Uncensored - https://opennameserver.org

sdns://AgcAAAAAAAAAAKDMEGDTnIMptitvvH0NbfkwmGm5gefmOS1c2PpAj02A5iBETr1nu4P4gHs5Iek4rJF4uIK9UKrbESMfBEz18I33zhZuczQub3Blbm5hbWVzZXJ2ZXIub3JnCi9kbnMtcXVlcnk


## oszx

Secure DNS Project by PumpleX - Hosted in the UK by OVH
No Logging / Ad-Blocking
Information at https://dns.oszx.co

sdns://AQIAAAAAAAAAETUxLjM4LjgzLjE0MTo1MzUzIMwm9_oYw26P4JIVoDhJ_5kFDdNxX1ke4fEzL1V5bwEjFzIuZG5zY3J5cHQtY2VydC5vc3p4LmNv


## plan9dns-fl

Miami Florida, US No-logs, no-filters, DNSSEC -info https://jlongua.github.io/plan9-dns

sdns://AQcAAAAAAAAAEzE0OS4yOC4xMDEuMTE5Ojg0NDMgVaFV4a8StIfx8fnCxDxVlxppqm-hJYyCKqtMtQENnCwkMi5kbnNjcnlwdC1jZXJ0LnBsdXRvbi5wbGFuOS1kbnMuY29t


## plan9dns-fl-doh

Miami Florida, US No-logs, no-filters, DNSSEC -info https://jlongua.github.io/plan9-dns

sdns://AgcAAAAAAAAADjE0OS4yOC4xMDEuMTE5IJo6NPcn3rm8pRAD2c6cOfjyfdnFJCkBwrqxpE5jWgIZFHBsdXRvbi5wbGFuOS1kbnMuY29tCi9kbnMtcXVlcnk


## plan9dns-fl-doh-ipv6

Miami Florida, US No-logs, no-filters, DNSSEC -info https://jlongua.github.io/plan9-dns

sdns://AgcAAAAAAAAAJ1syMDAxOjE5ZjA6OTAwMjpkZTQ6NTQwMDo0ZmY6ZmUwODo3ZGUzXSCaOjT3J965vKUQA9nOnDn48n3ZxSQpAcK6saROY1oCGRRwbHV0b24ucGxhbjktZG5zLmNvbQovZG5zLXF1ZXJ5


## plan9dns-mx

Mexico City, Mexico No-logs, no-filters, DNSSEC -info https://jlongua.github.io/plan9-dns

sdns://AQcAAAAAAAAAEzIxNi4yMzguODAuMjE5Ojg0NDMgKmPCui35rtOj9yk7c07sEtC_Khyo_9_HcpO23GCroNskMi5kbnNjcnlwdC1jZXJ0LmhlbGlvcy5wbGFuOS1kbnMuY29t


## plan9dns-mx-doh

Mexico City, Mexico No-logs, no-filters, DNSSEC -info https://jlongua.github.io/plan9-dns

sdns://AgcAAAAAAAAADjIxNi4yMzguODAuMjE5IJo6NPcn3rm8pRAD2c6cOfjyfdnFJCkBwrqxpE5jWgIZFGhlbGlvcy5wbGFuOS1kbnMuY29tCi9kbnMtcXVlcnk


## plan9dns-mx-doh-ipv6

Mexico City, Mexico No-logs, no-filters, DNSSEC -info https://jlongua.github.io/plan9-dns

sdns://AgcAAAAAAAAAKFsyMDAxOjE5ZjA6YjQwMDoxZDhjOjU0MDA6NGZmOmZlMTE6YjE1YV0gmjo09yfeubylEAPZzpw5-PJ92cUkKQHCurGkTmNaAhkUaGVsaW9zLnBsYW45LWRucy5jb20KL2Rucy1xdWVyeQ


## plan9dns-nj

Piscataway New Jersey, US No-logs, no-filters, DNSSEC -info https://jlongua.github.io/plan9-dns

sdns://AQcAAAAAAAAAEjIwNy4yNDYuODcuOTY6ODQ0MyCwmQlIDpKk8SiiyrJbPgKhHxCrBJLb8ZWlu6tvr1KvkyQyLmRuc2NyeXB0LWNlcnQua3Jvbm9zLnBsYW45LWRucy5jb20


## plan9dns-nj-doh

Piscataway New Jersey, US No-logs, no-filters, DNSSEC -info https://jlongua.github.io/plan9-dns

sdns://AgcAAAAAAAAADTIwNy4yNDYuODcuOTYgmjo09yfeubylEAPZzpw5-PJ92cUkKQHCurGkTmNaAhkUa3Jvbm9zLnBsYW45LWRucy5jb20KL2Rucy1xdWVyeQ


## plan9dns-nj-doh-ipv6

Piscataway New Jersey, US No-logs, no-filters, DNSSEC -info https://jlongua.github.io/plan9-dns

sdns://AgcAAAAAAAAAJVsyMDAxOjE5ZjA6NTozYmQ3OjU0MDA6NGZmOmZlMDU6ZGE4M10gmjo09yfeubylEAPZzpw5-PJ92cUkKQHCurGkTmNaAhkUa3Jvbm9zLnBsYW45LWRucy5jb20KL2Rucy1xdWVyeQ


## pryv8boi

By pryv8, non Logging, uncensored, DNSSEC - hosted on contabo servers

sdns://AQcAAAAAAAAAEzE2NC42OC4xMjEuMTYyOjQ0NDMgHtKNfXpUMzPyLnXK8DauHpWm1Rqhz7LqwBBmSzdY9BIcMi5kbnNjcnlwdC1jZXJ0LnByeXY4Ym9pLm9yZw


## publicarray-au-doh

DNSSEC • OpenNIC • Non-logging • Uncensored - hosted on vultr.com
Maintained by publicarray - https://dns.seby.io

sdns://AgcAAAAAAAAADDQ1Ljc2LjExMy4zMaDMEGDTnIMptitvvH0NbfkwmGm5gefmOS1c2PpAj02A5iBETr1nu4P4gHs5Iek4rJF4uIK9UKrbESMfBEz18I33zhBkb2guc2VieS5pbzo4NDQzCi9kbnMtcXVlcnk


## publicarray-au2-doh

DNSSEC • OpenNIC • Non-logging • Uncensored - hosted on ovh.com.au
Maintained by publicarray - https://dns.seby.io

sdns://AgcAAAAAAAAADTEzOS45OS4yMjIuNzKgzBBg05yDKbYrb7x9DW35MJhpuYHn5jktXNj6QI9NgOYgRE69Z7uD-IB7OSHpOKyReLiCvVCq2xEjHwRM9fCN984NZG9oLTIuc2VieS5pbwovZG5zLXF1ZXJ5


## qihoo360-doh

DoH server runned by Qihoo 360, has logs, supports DNSSEC. GFW filtering rules are applied.

Homepage: https://sdns.360.net/

sdns://AgEAAAAAAAAAACBZPi1Jp0AjVVUmrvm3QisZ5bixZzkbbe5e0pKxyiOnTApkb2guMzYwLmNuCi9kbnMtcXVlcnk


## quad101

DNSSEC-aware public resolver by the Taiwan Network Information Center (TWNIC)
https://101.101.101.101/index_en.html

sdns://AgcAAAAAAAAAACC2vD25TAYM7EnyCH8Xw1-0g5OccnTsGH9vQUUH0njRtAxkbnMudHduaWMudHcKL2Rucy1xdWVyeQ


## quad9-dnscrypt-ip4-filter-ecs-pri

Quad9 (anycast) dnssec/no-log/filter/ecs 9.9.9.11 - 149.112.112.11

sdns://AQMAAAAAAAAADTkuOS45LjExOjg0NDMgZ8hHuMh1jNEgJFVDvnVnRt803x2EwAuMRwNo34Idhj4ZMi5kbnNjcnlwdC1jZXJ0LnF1YWQ5Lm5ldA
sdns://AQMAAAAAAAAAEzE0OS4xMTIuMTEyLjExOjg0NDMgZ8hHuMh1jNEgJFVDvnVnRt803x2EwAuMRwNo34Idhj4ZMi5kbnNjcnlwdC1jZXJ0LnF1YWQ5Lm5ldA


## quad9-dnscrypt-ip4-filter-pri

Quad9 (anycast) dnssec/no-log/filter 9.9.9.9 - 149.112.112.9 - 149.112.112.112

sdns://AQMAAAAAAAAADDkuOS45Ljk6ODQ0MyBnyEe4yHWM0SAkVUO-dWdG3zTfHYTAC4xHA2jfgh2GPhkyLmRuc2NyeXB0LWNlcnQucXVhZDkubmV0
sdns://AQMAAAAAAAAAEjE0OS4xMTIuMTEyLjk6ODQ0MyBnyEe4yHWM0SAkVUO-dWdG3zTfHYTAC4xHA2jfgh2GPhkyLmRuc2NyeXB0LWNlcnQucXVhZDkubmV0
sdns://AQMAAAAAAAAAFDE0OS4xMTIuMTEyLjExMjo4NDQzIGfIR7jIdYzRICRVQ751Z0bfNN8dhMALjEcDaN-CHYY-GTIuZG5zY3J5cHQtY2VydC5xdWFkOS5uZXQ


## quad9-dnscrypt-ip4-nofilter-ecs-pri

Quad9 (anycast) no-dnssec/no-log/no-filter/ecs 9.9.9.12 - 149.112.112.12

sdns://AQYAAAAAAAAADTkuOS45LjEyOjg0NDMgZ8hHuMh1jNEgJFVDvnVnRt803x2EwAuMRwNo34Idhj4ZMi5kbnNjcnlwdC1jZXJ0LnF1YWQ5Lm5ldA
sdns://AQYAAAAAAAAAEzE0OS4xMTIuMTEyLjEyOjg0NDMgZ8hHuMh1jNEgJFVDvnVnRt803x2EwAuMRwNo34Idhj4ZMi5kbnNjcnlwdC1jZXJ0LnF1YWQ5Lm5ldA


## quad9-dnscrypt-ip4-nofilter-pri

Quad9 (anycast) no-dnssec/no-log/no-filter 149.112.112.10

sdns://AQYAAAAAAAAAEzE0OS4xMTIuMTEyLjEwOjg0NDMgZ8hHuMh1jNEgJFVDvnVnRt803x2EwAuMRwNo34Idhj4ZMi5kbnNjcnlwdC1jZXJ0LnF1YWQ5Lm5ldA


## quad9-doh-ip4-port443-filter-ecs-pri

Quad9 (anycast) dnssec/no-log/filter/ecs 9.9.9.11 - 149.112.112.11

sdns://AgMAAAAAAAAACDkuOS45LjExICoV9dastufAkBreTrvHQ7LM1IkDK0bhZC8Gk2gwASWKE2RuczExLnF1YWQ5Lm5ldDo0NDMKL2Rucy1xdWVyeQ
sdns://AgMAAAAAAAAADjE0OS4xMTIuMTEyLjExICoV9dastufAkBreTrvHQ7LM1IkDK0bhZC8Gk2gwASWKE2RuczExLnF1YWQ5Lm5ldDo0NDMKL2Rucy1xdWVyeQ


## quad9-doh-ip4-port443-filter-pri

Quad9 (anycast) dnssec/no-log/filter 9.9.9.9 - 149.112.112.9 - 149.112.112.112

sdns://AgMAAAAAAAAABzkuOS45LjkgKhX11qy258CQGt5Ou8dDsszUiQMrRuFkLwaTaDABJYoSZG5zOS5xdWFkOS5uZXQ6NDQzCi9kbnMtcXVlcnk
sdns://AgMAAAAAAAAADTE0OS4xMTIuMTEyLjkgKhX11qy258CQGt5Ou8dDsszUiQMrRuFkLwaTaDABJYoSZG5zOS5xdWFkOS5uZXQ6NDQzCi9kbnMtcXVlcnk
sdns://AgMAAAAAAAAADzE0OS4xMTIuMTEyLjExMiAqFfXWrLbnwJAa3k67x0OyzNSJAytG4WQvBpNoMAElihFkbnMucXVhZDkubmV0OjQ0MwovZG5zLXF1ZXJ5


## quad9-doh-ip4-port443-nofilter-ecs-pri

Quad9 (anycast) no-dnssec/no-log/no-filter/ecs 9.9.9.12 - 149.112.112.12

sdns://AgYAAAAAAAAACDkuOS45LjEyICoV9dastufAkBreTrvHQ7LM1IkDK0bhZC8Gk2gwASWKE2RuczEyLnF1YWQ5Lm5ldDo0NDMKL2Rucy1xdWVyeQ
sdns://AgYAAAAAAAAADjE0OS4xMTIuMTEyLjEyICoV9dastufAkBreTrvHQ7LM1IkDK0bhZC8Gk2gwASWKE2RuczEyLnF1YWQ5Lm5ldDo0NDMKL2Rucy1xdWVyeQ


## quad9-doh-ip4-port443-nofilter-pri

Quad9 (anycast) no-dnssec/no-log/no-filter 9.9.9.10 - 149.112.112.10

sdns://AgYAAAAAAAAACDkuOS45LjEwICoV9dastufAkBreTrvHQ7LM1IkDK0bhZC8Gk2gwASWKE2RuczEwLnF1YWQ5Lm5ldDo0NDMKL2Rucy1xdWVyeQ
sdns://AgYAAAAAAAAADjE0OS4xMTIuMTEyLjEwICoV9dastufAkBreTrvHQ7LM1IkDK0bhZC8Gk2gwASWKE2RuczEwLnF1YWQ5Lm5ldDo0NDMKL2Rucy1xdWVyeQ


## quad9-doh-ip4-port5053-filter-ecs-pri

Quad9 (anycast) dnssec/no-log/filter/ecs 9.9.9.11 - 149.112.112.11

sdns://AgMAAAAAAAAACDkuOS45LjExICoV9dastufAkBreTrvHQ7LM1IkDK0bhZC8Gk2gwASWKFGRuczExLnF1YWQ5Lm5ldDo1MDUzCi9kbnMtcXVlcnk
sdns://AgMAAAAAAAAADjE0OS4xMTIuMTEyLjExICoV9dastufAkBreTrvHQ7LM1IkDK0bhZC8Gk2gwASWKFGRuczExLnF1YWQ5Lm5ldDo1MDUzCi9kbnMtcXVlcnk


## quad9-doh-ip4-port5053-filter-pri

Quad9 (anycast) dnssec/no-log/filter 9.9.9.9 - 149.112.112.9 - 149.112.112.112

sdns://AgMAAAAAAAAABzkuOS45LjkgKhX11qy258CQGt5Ou8dDsszUiQMrRuFkLwaTaDABJYoTZG5zOS5xdWFkOS5uZXQ6NTA1MwovZG5zLXF1ZXJ5
sdns://AgMAAAAAAAAADTE0OS4xMTIuMTEyLjkgKhX11qy258CQGt5Ou8dDsszUiQMrRuFkLwaTaDABJYoTZG5zOS5xdWFkOS5uZXQ6NTA1MwovZG5zLXF1ZXJ5
sdns://AgMAAAAAAAAADzE0OS4xMTIuMTEyLjExMiAqFfXWrLbnwJAa3k67x0OyzNSJAytG4WQvBpNoMAElihJkbnMucXVhZDkubmV0OjUwNTMKL2Rucy1xdWVyeQ


## quad9-doh-ip4-port5053-nofilter-ecs-pri

Quad9 (anycast) no-dnssec/no-log/no-filter/ecs 9.9.9.12 - 149.112.112.12

sdns://AgYAAAAAAAAACDkuOS45LjEyICoV9dastufAkBreTrvHQ7LM1IkDK0bhZC8Gk2gwASWKFGRuczEyLnF1YWQ5Lm5ldDo1MDUzCi9kbnMtcXVlcnk
sdns://AgYAAAAAAAAADjE0OS4xMTIuMTEyLjEyICoV9dastufAkBreTrvHQ7LM1IkDK0bhZC8Gk2gwASWKFGRuczEyLnF1YWQ5Lm5ldDo1MDUzCi9kbnMtcXVlcnk


## quad9-doh-ip4-port5053-nofilter-pri

Quad9 (anycast) no-dnssec/no-log/no-filter 9.9.9.10 - 149.112.112.10

sdns://AgYAAAAAAAAACDkuOS45LjEwICoV9dastufAkBreTrvHQ7LM1IkDK0bhZC8Gk2gwASWKFGRuczEwLnF1YWQ5Lm5ldDo1MDUzCi9kbnMtcXVlcnk
sdns://AgYAAAAAAAAADjE0OS4xMTIuMTEyLjEwICoV9dastufAkBreTrvHQ7LM1IkDK0bhZC8Gk2gwASWKFGRuczEwLnF1YWQ5Lm5ldDo1MDUzCi9kbnMtcXVlcnk


## quad9-doh-ip6-port443-filter-ecs-pri

Quad9 (anycast) dnssec/no-log/filter/ecs 2620:fe::11 - 2620:fe::fe:11

sdns://AgMAAAAAAAAADVsyNjIwOmZlOjoxMV0gKhX11qy258CQGt5Ou8dDsszUiQMrRuFkLwaTaDABJYoTZG5zMTEucXVhZDkubmV0OjQ0MwovZG5zLXF1ZXJ5
sdns://AgMAAAAAAAAAEFsyNjIwOmZlOjpmZToxMV0gKhX11qy258CQGt5Ou8dDsszUiQMrRuFkLwaTaDABJYoTZG5zMTEucXVhZDkubmV0OjQ0MwovZG5zLXF1ZXJ5


## quad9-doh-ip6-port443-filter-pri

Quad9 (anycast) dnssec/no-log/filter 2620:fe::fe - 2620:fe::9 - 2620:fe::fe:9

sdns://AgMAAAAAAAAADVsyNjIwOmZlOjpmZV0gKhX11qy258CQGt5Ou8dDsszUiQMrRuFkLwaTaDABJYoRZG5zLnF1YWQ5Lm5ldDo0NDMKL2Rucy1xdWVyeQ
sdns://AgMAAAAAAAAADFsyNjIwOmZlOjo5XSAqFfXWrLbnwJAa3k67x0OyzNSJAytG4WQvBpNoMAElihFkbnMucXVhZDkubmV0OjQ0MwovZG5zLXF1ZXJ5
sdns://AgMAAAAAAAAAD1syNjIwOmZlOjpmZTo5XSAqFfXWrLbnwJAa3k67x0OyzNSJAytG4WQvBpNoMAElihJkbnM5LnF1YWQ5Lm5ldDo0NDMKL2Rucy1xdWVyeQ


## quad9-doh-ip6-port443-nofilter-ecs-pri

Quad9 (anycast) no-dnssec/no-log/no-filter/ecs 2620:fe::12 - 2620:fe::fe:12

sdns://AgYAAAAAAAAADVsyNjIwOmZlOjoxMl0gKhX11qy258CQGt5Ou8dDsszUiQMrRuFkLwaTaDABJYoTZG5zMTIucXVhZDkubmV0OjQ0MwovZG5zLXF1ZXJ5
sdns://AgYAAAAAAAAAEFsyNjIwOmZlOjpmZToxMl0gKhX11qy258CQGt5Ou8dDsszUiQMrRuFkLwaTaDABJYoTZG5zMTIucXVhZDkubmV0OjQ0MwovZG5zLXF1ZXJ5


## quad9-doh-ip6-port443-nofilter-pri

Quad9 (anycast) no-dnssec/no-log/no-filter 2620:fe::10 - 2620:fe::fe:10

sdns://AgYAAAAAAAAADVsyNjIwOmZlOjoxMF0gKhX11qy258CQGt5Ou8dDsszUiQMrRuFkLwaTaDABJYoTZG5zMTAucXVhZDkubmV0OjQ0MwovZG5zLXF1ZXJ5
sdns://AgYAAAAAAAAAEFsyNjIwOmZlOjpmZToxMF0gKhX11qy258CQGt5Ou8dDsszUiQMrRuFkLwaTaDABJYoTZG5zMTAucXVhZDkubmV0OjQ0MwovZG5zLXF1ZXJ5


## quad9-doh-ip6-port5053-filter-ecs-pri

Quad9 (anycast) dnssec/no-log/filter/ecs 2620:fe::11 - 2620:fe::fe:11

sdns://AgMAAAAAAAAADVsyNjIwOmZlOjoxMV0gKhX11qy258CQGt5Ou8dDsszUiQMrRuFkLwaTaDABJYoUZG5zMTEucXVhZDkubmV0OjUwNTMKL2Rucy1xdWVyeQ
sdns://AgMAAAAAAAAAEFsyNjIwOmZlOjpmZToxMV0gKhX11qy258CQGt5Ou8dDsszUiQMrRuFkLwaTaDABJYoUZG5zMTEucXVhZDkubmV0OjUwNTMKL2Rucy1xdWVyeQ


## quad9-doh-ip6-port5053-filter-pri

Quad9 (anycast) dnssec/no-log/filter 2620:fe::fe - 2620:fe::9 - 2620:fe::fe:9

sdns://AgMAAAAAAAAADVsyNjIwOmZlOjpmZV0gKhX11qy258CQGt5Ou8dDsszUiQMrRuFkLwaTaDABJYoSZG5zLnF1YWQ5Lm5ldDo1MDUzCi9kbnMtcXVlcnk
sdns://AgMAAAAAAAAADFsyNjIwOmZlOjo5XSAqFfXWrLbnwJAa3k67x0OyzNSJAytG4WQvBpNoMAElihJkbnMucXVhZDkubmV0OjUwNTMKL2Rucy1xdWVyeQ
sdns://AgMAAAAAAAAAD1syNjIwOmZlOjpmZTo5XSAqFfXWrLbnwJAa3k67x0OyzNSJAytG4WQvBpNoMAElihNkbnM5LnF1YWQ5Lm5ldDo1MDUzCi9kbnMtcXVlcnk


## quad9-doh-ip6-port5053-nofilter-ecs-pri

Quad9 (anycast) no-dnssec/no-log/no-filter/ecs 2620:fe::12 - 2620:fe::fe:12

sdns://AgYAAAAAAAAADVsyNjIwOmZlOjoxMl0gKhX11qy258CQGt5Ou8dDsszUiQMrRuFkLwaTaDABJYoUZG5zMTIucXVhZDkubmV0OjUwNTMKL2Rucy1xdWVyeQ
sdns://AgYAAAAAAAAAEFsyNjIwOmZlOjpmZToxMl0gKhX11qy258CQGt5Ou8dDsszUiQMrRuFkLwaTaDABJYoUZG5zMTIucXVhZDkubmV0OjUwNTMKL2Rucy1xdWVyeQ


## quad9-doh-ip6-port5053-nofilter-pri

Quad9 (anycast) no-dnssec/no-log/no-filter 2620:fe::10 - 2620:fe::fe:10

sdns://AgYAAAAAAAAADVsyNjIwOmZlOjoxMF0gKhX11qy258CQGt5Ou8dDsszUiQMrRuFkLwaTaDABJYoUZG5zMTAucXVhZDkubmV0OjUwNTMKL2Rucy1xdWVyeQ
sdns://AgYAAAAAAAAAEFsyNjIwOmZlOjpmZToxMF0gKhX11qy258CQGt5Ou8dDsszUiQMrRuFkLwaTaDABJYoUZG5zMTAucXVhZDkubmV0OjUwNTMKL2Rucy1xdWVyeQ


## safesurfer

Family safety focused blocklist for over 2 million adult sites, as well as phishing and malware and more.
Free to use, paid for customizing blocking for more categories+sites and viewing usage at my.safesurfer.io. Logs taken for viewing
usage, data never sold - https://safesurfer.io

Warning: this server is incompatible with DNS anonymization.

sdns://AQIAAAAAAAAADzEwNC4xNTUuMjM3LjIyNSAnIH_VEgToNntINABd-f_R0wu-KpwzY55u2_iu2R1A2CAyLmRuc2NyeXB0LWNlcnQuc2FmZXN1cmZlci5jby5ueg


## safesurfer-doh

Family safety focused blocklist for over 2 million adult sites, as well as phishing and malware and more.
Free to use, paid for customizing blocking for more categories+sites and viewing usage at my.safesurfer.io. Logs taken for viewing
usage, data never sold - https://safesurfer.io

sdns://AgAAAAAAAAAAACBqUGKw0XjVVvFjsTsbDxlDXQJYgpHMdVid_ubrEcjVwxFkb2guc2FmZXN1cmZlci5pbwovZG5zLXF1ZXJ5


## saldns01-conoha-ipv4

Hosted on ConoHa VPS Tokyo region. No log. No filter. From experimental [&mu;ODNS project](https://junkurihara.github.io/dns/).

sdns://AQcAAAAAAAAAFDExOC4yNy4xMDguMTQwOjUwNDQzIPL_JdttytAhcocG8vZH5EVk-uQKKose72bD0ji5G-xlIjIuZG5zY3J5cHQtY2VydC5zYWxkbnMwMS50eXBlcS5vcmc


## saldns02-conoha-ipv4

Hosted on ConoHa VPS Tokyo region. No log. No filter. From experimental [&mu;ODNS project](https://junkurihara.github.io/dns/).

sdns://AQcAAAAAAAAAFTEzMy4xMzAuMTE4LjEwMzo1MDQ0MyB7SI0q4_Ff8lFRUCbjPtcAQ3HfdWlLxyGDUUNc3NUZdiIyLmRuc2NyeXB0LWNlcnQuc2FsZG5zMDIudHlwZXEub3Jn


## saldns03-conoha-ipv4

Hosted on ConoHa VPS Tokyo region. No log. No filter. From experimental [&mu;ODNS project](https://junkurihara.github.io/dns/).

sdns://AQcAAAAAAAAAFDEzMy4xMzAuOTguMjUwOjUwNDQzIFl1NfOwMd24kRlr0mXR4rKo-c_jMV7DBUVooDEY1xFeIjIuZG5zY3J5cHQtY2VydC5zYWxkbnMwMy50eXBlcS5vcmc


## sby-doh-limotelu

non-censoring, non-logging, DNSSEC-capable Hosted in Surabaya, Indonesia (DoH) https://limotelu.org maintained by poentodewo (https://github.com/poentodewo)

sdns://AgcAAAAAAAAADjE5OS4xODAuMTMwLjM5oDUJq9J2eoL0zQJHsLcq9AQ3obsl8h1hFreCavqWy4TdIGpQYrDReNVW8WOxOxsPGUNdAliCkcx1WJ3-5usRyNXDFHNieS1kb2gubGltb3RlbHUub3JnCi9kbnMtcXVlcnk


## sby-limotelu

non-censoring, non-logging, DNSSEC-capable Hosted in Surabaya, Indonesia (Dnscrypt) https://limotelu.org maintained by poentodewo (https://github.com/poentodewo)

sdns://AQcAAAAAAAAAEzE5OS4xODAuMTMwLjM5Ojg0NDMg1U5MYSDK58uVdJ8dKtp0UZaCKSG0znwQLVHYKk1QyuwcMi5kbnNjcnlwdC1jZXJ0LnNieS1saW1vdGVsdQ


## scaleway-ams

DNSSEC/Non-logged/Uncensored in Amsterdam - DEV1-S instance donated by Scaleway.com
Maintained by Frank Denis - https://fr.dnscrypt.info

sdns://AQcAAAAAAAAADTUxLjE1LjEyMi4yNTAg6Q3ZfapcbHgiHKLF7QFoli0Ty1Vsz3RXs1RUbxUrwZAcMi5kbnNjcnlwdC1jZXJ0LnNjYWxld2F5LWFtcw


## scaleway-ams-ipv6

DNSSEC/Non-logged/Uncensored in Amsterdam - IPv6 only - DEV1-S instance donated by Scaleway.com
Maintained by Frank Denis - https://fr.dnscrypt.info

sdns://AQcAAAAAAAAAFlsyMDAxOmJjODoxODIwOjUwZDo6MV0g6Q3ZfapcbHgiHKLF7QFoli0Ty1Vsz3RXs1RUbxUrwZAcMi5kbnNjcnlwdC1jZXJ0LnNjYWxld2F5LWFtcw


## scaleway-fr

DNSSEC/Non-logged/Uncensored in Paris - DEV1-S instance donated by Scaleway.com
Maintained by Frank Denis - https://fr.dnscrypt.info

sdns://AQcAAAAAAAAADjIxMi40Ny4yMjguMTM2IOgBuE6mBr-wusDOQ0RbsV66ZLAvo8SqMa4QY2oHkDJNHzIuZG5zY3J5cHQtY2VydC5mci5kbnNjcnlwdC5vcmc


## scaleway-fr-ipv6

DNSSEC/Non-logged/Uncensored in Paris - IPv6 only - DEV1-S instance donated by Scaleway.com
Maintained by Frank Denis - https://fr.dnscrypt.info

sdns://AQcAAAAAAAAAF1syMDAxOmJjODo0N2IwOjFhMDE6OjFdIOgBuE6mBr-wusDOQ0RbsV66ZLAvo8SqMa4QY2oHkDJNHzIuZG5zY3J5cHQtY2VydC5mci5kbnNjcnlwdC5vcmc


## serbica

Public DNSCrypt server in the Netherlands by https://litepay.ch

sdns://AQcAAAAAAAAAEzE4NS42Ni4xNDMuMTc4OjUzNTMg-Y2MQmGOXiggAEKulN-ITGEn_Kj3TIP1UK1X2wh3o7wXMi5kbnNjcnlwdC1jZXJ0LnNlcmJpY2E


## sfw.scaleway-fr

Uses deep learning to block adult websites. Free, DNSSEC, no logs.
Hosted in Paris, running on a 1-XS server donated by Scaleway.com
Maintained by Frank Denis - https://fr.dnscrypt.info/sfw.html

sdns://AQMAAAAAAAAADzE2My4xNzIuMTgwLjEyNSDfYnO_x1IZKotaObwMhaw_-WRF1zZE9mJygl01WPGh_x8yLmRuc2NyeXB0LWNlcnQuc2Z3LnNjYWxld2F5LWZy


## starrydns

DNSCrypt server in Singapore, no filter, no logs, DNSSEC support

sdns://AQcAAAAAAAAACzUyLjc3LjMuMjE1IDb9YzoMbw-DD4Ql0GG-maGsuKFCEor_AW69i7NlvWuXIDIuZG5zY3J5cHQtY2VydC5zdGFycnlkbnMucGxhbmV0


## starrydns-ipv6

DNSCrypt server in Singapore, no filter, no logs, DNSSEC support (IPv6 server)

sdns://AQcAAAAAAAAAKFsyNDA2OmRhMTg6Njc2OjQxMDI6ODdiOTplMjk5OjJhNWE6ODk0Yl0gNv1jOgxvD4MPhCXQYb6Zoay4oUISiv8Bbr2Ls2W9a5cgMi5kbnNjcnlwdC1jZXJ0LnN0YXJyeWRucy5wbGFuZXQ


## sth-ads-doh-se

Resolver in Stockholm, Sweden. DoH server. Non-logging, remove ads and malware, DNSSEC.

sdns://AgMAAAAAAAAADTQ1LjE1My4xODcuOTYAGGRuc3NlLW5vYWRzLmFsZWtiZXJnLm5ldAovZG5zLXF1ZXJ5


## sth-dnscrypt-se

Resolver in Stockholm, Sweden. DNSCrypt server. Non-logging, non-filtering, DNSSEC.

sdns://AQcAAAAAAAAAEjQ1LjE1My4xODcuOTY6NDM0MyDxcH8AVvN5Rqr3-HUqRjpgUFVw3NgiJ-IGTCbEVu__7x8yLmRuc2NyeXB0LWNlcnQuc3RoLWRuc2NyeXB0LXNl


## sth-dnscrypt-se-ipv6

Resolver in Stockholm, Sweden. DNSCrypt server. Non-logging, non-filtering, DNSSEC.

sdns://AQcAAAAAAAAAGlsyYTA5OmNkNDI6Zjo0MjViOjoxXTo0MzQzIPFwfwBW83lGqvf4dSpGOmBQVXDc2CIn4gZMJsRW7__vHzIuZG5zY3J5cHQtY2VydC5zdGgtZG5zY3J5cHQtc2U


## sth-doh-se

Resolver in Stockholm, Sweden. DoH server. Non-logging, non-filtering, DNSSEC.

sdns://AgcAAAAAAAAADTQ1LjE1My4xODcuOTagzBBg05yDKbYrb7x9DW35MJhpuYHn5jktXNj6QI9NgOYgRE69Z7uD-IB7OSHpOKyReLiCvVCq2xEjHwRM9fCN984SZG5zc2UuYWxla2JlcmcubmV0Ci9kbnMtcXVlcnk


## switch

Public DoH service provided by SWITCH in Switzerland

https://www.switch.ch

Provides protection against malware, but does not block ads.

sdns://AgMAAAAAAAAAACAqFfXWrLbnwJAa3k67x0OyzNSJAytG4WQvBpNoMAElig1kbnMuc3dpdGNoLmNoCi9kbnMtcXVlcnk


## techsaviours.org-dnscrypt

No filter | No logs | DNSSEC | Nuremberg, Germany (netcup) | Maintained by https://techsaviours.org/

sdns://AQcAAAAAAAAAEDg5LjU4LjYuMTY5OjQ0MzQgB4isFl7gD2-efHhMEtFjyCz_nHFCaQ8OsbBTgZCa3zsgMi5kbnNjcnlwdC1jZXJ0LnRlY2hzYXZpb3Vycy5vcmc


## tuna-doh-ipv4

DoH server provided by Tsinghua University TUNA Association, located in mainland China, no GFW poisoning yet it has a manual blacklist.

sdns://AgEAAAAAAAAACTEwMS42LjYuNiBZPi1Jp0AjVVUmrvm3QisZ5bixZzkbbe5e0pKxyiOnTA4xMDEuNi42LjY6ODQ0MwovZG5zLXF1ZXJ5


## uncensoreddns-dk-ipv4

Also known as censurfridns.
DoH, no logs, no filter, DNSSEC, unicast hosted in Denmark - https://blog.uncensoreddns.org

sdns://AgcAAAAAAAAADDg5LjIzMy40My43MaDMEGDTnIMptitvvH0NbfkwmGm5gefmOS1c2PpAj02A5iBETr1nu4P4gHs5Iek4rJF4uIK9UKrbESMfBEz18I33zhl1bmljYXN0LnVuY2Vuc29yZWRkbnMub3JnCi9kbnMtcXVlcnk


## uncensoreddns-dk-ipv6

Also known as censurfridns.
DoH, no logs, no filter, DNSSEC, unicast hosted in Denmark - https://blog.uncensoreddns.org

sdns://AgcAAAAAAAAAElsyYTAxOjNhMDo1Mzo1Mzo6XaDMEGDTnIMptitvvH0NbfkwmGm5gefmOS1c2PpAj02A5iBETr1nu4P4gHs5Iek4rJF4uIK9UKrbESMfBEz18I33zhl1bmljYXN0LnVuY2Vuc29yZWRkbnMub3JnCi9kbnMtcXVlcnk


## uncensoreddns-ipv4

Also known as censurfridns.
DoH, no logs, no filter, DNSSEC, anycast - https://blog.uncensoreddns.org

sdns://AgcAAAAAAAAADjkxLjIzOS4xMDAuMTAwoMwQYNOcgym2K2-8fQ1t-TCYabmB5-Y5LVzY-kCPTYDmIEROvWe7g_iAezkh6TiskXi4gr1QqtsRIx8ETPXwjffOGWFueWNhc3QudW5jZW5zb3JlZGRucy5vcmcKL2Rucy1xdWVyeQ


## uncensoreddns-ipv6

Also known as censurfridns.
DoH, no logs, no filter, DNSSEC, anycast - https://blog.uncensoreddns.org

sdns://AgcAAAAAAAAAEVsyMDAxOjY3YzoyOGE0OjpdoMwQYNOcgym2K2-8fQ1t-TCYabmB5-Y5LVzY-kCPTYDmIEROvWe7g_iAezkh6TiskXi4gr1QqtsRIx8ETPXwjffOGWFueWNhc3QudW5jZW5zb3JlZGRucy5vcmcKL2Rucy1xdWVyeQ


## userspace-australia

DNSCrypt in Australia (Brisbane & Melbourne) by UserSpace.
No logs | IPv4 | Filtered

sdns://AQMAAAAAAAAAEDEwMy4xNi4xMzEuNzc6NTQgnRNtOLv4IzxEfkbLFOaHa-ncLImdQiP-pS1jaFY5jlUdMi5kbnNjcnlwdC1jZXJ0LnVzZXJzcGFjZS1ibmU
sdns://AQMAAAAAAAAAEjEwMy4yMzYuMTYyLjExOTo1NCBPr5jCD_2geOTMmS5LgQg_v79pgppTm3vLZhe_oahbgR0yLmRuc2NyeXB0LWNlcnQudXNlcnNwYWNlLW1lbA


## userspace-australia-ipv6

DNSCrypt in Australia (Brisbane & Melbourne) by UserSpace.
No logs | IPv6 | Filtered

sdns://AQMAAAAAAAAAJVsyNDA0Ojk0MDA6MTowOjIxNjozZWZmOmZlZjA6MTgwYV06NTQgnRNtOLv4IzxEfkbLFOaHa-ncLImdQiP-pS1jaFY5jlUdMi5kbnNjcnlwdC1jZXJ0LnVzZXJzcGFjZS1ibmU
sdns://AQMAAAAAAAAAJVsyNDA0Ojk0MDA6MzowOjIxNjozZWZmOmZlZTA6N2Y2OV06NTQgT6-Ywg_9oHjkzJkuS4EIP7-_aYKaU5t7y2YXv6GoW4EdMi5kbnNjcnlwdC1jZXJ0LnVzZXJzcGFjZS1tZWw


## v.dnscrypt.uk-ipv4

DNSCrypt, no logs, uncensored, DNSSEC. Hosted in London UK on Digital Ocean
https://www.dnscrypt.uk

sdns://AQcAAAAAAAAADzEwNC4yMzguMTg2LjE5MiDtST2M6teQZk8GPEe3lZojaS18kDY8nkPMtZF75bQe5R0yLmRuc2NyeXB0LWNlcnQudi5kbnNjcnlwdC51aw


## v.dnscrypt.uk-ipv6

DNSCrypt, no logs, uncensored, DNSSEC. Hosted in London UK on Digital Ocean
https://www.dnscrypt.uk

sdns://AQcAAAAAAAAAKFsyMDAxOjE5ZjA6NzQwMjoxNTc0OjU0MDA6MmZmOmZlNjY6MmNmZl0g7Uk9jOrXkGZPBjxHt5WaI2ktfJA2PJ5DzLWRe-W0HuUdMi5kbnNjcnlwdC1jZXJ0LnYuZG5zY3J5cHQudWs


## wevpn-singapore

Private DNSCrypt service by WeVPN in Singapore - https://wevpn.com/dns
With ad blocking.

sdns://AQcAAAAAAAAAEzE0My4yNDQuMzMuNzQ6MTUzNTMgFTXwu5MfYkBOrRpDeoB-yOWEjCnf-l3yixhtuzuPBskfMi5kbnNjcnlwdC1jZXJ0LnNlY3VyZS5kbnMudGVzdA


## wevpn-useast

Private DNSCrypt service by WeVPN in New Jersey, USA - https://wevpn.com/dns
With ad blocking.

sdns://AQcAAAAAAAAAFDIzLjIyNi4xMzQuMjQyOjE1MzUzII_Le5DiGa3AfdRxR7DRt52ZaexL_22aLfjDJwp5saIsHzIuZG5zY3J5cHQtY2VydC5zZWN1cmUuZG5zLnRlc3Q


## yandex

Yandex public DNS server (anycast)

sdns://AQQAAAAAAAAAEDc3Ljg4LjguNzg6MTUzNTMg04TAccn3RmKvKszVe13MlxTUB7atNgHhrtwG1W1JYyciMi5kbnNjcnlwdC1jZXJ0LmJyb3dzZXIueWFuZGV4Lm5ldA

