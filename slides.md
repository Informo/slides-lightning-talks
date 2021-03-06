
# ![Informo - Making information accessible](img/logo-full-white.png)<!-- .element: class="plain" -->
<!-- .slide: data-background="#417D44" -->


## Current status

- Started in Dec. 2017 during Collateral Freedom hackathon
- Proof of concept
- Open specifications since Oct. 2018

Notes:
- CF hackathon organised by RWB & La Cantine Numérique
- POC revealed some design limitations


## Who we are

- Vabd
    + Matrix `@vabd:weu.informo.network`
    + Mail `vabd@informo.network`
    + GPG `EA4BC86670028E3B26DD613D3972AC25F549D254`<!-- .element: style="font-size: 0.7em" -->
- GordonF
    + Matrix `@gordonf:weu.informo.network`
    + Mail `gordonf@informo.network`
    + GPG `12D7F3CE28D13F10C8B6D12ADA220606B48CF8E5`<!-- .element: style="font-size: 0.7em" -->

Notes:
- Working on our free time


------------------------------------------------------------


# Issues

- Some countries censor online information
- Governments or ISPs can track website users

[![2018 World press freedom index map](img/pressfreedom.png)<!-- .element: style="height: 370px; margin: 0;" -->](https://rsf.org/en/ranking)

Note:
- Map is _2018 World press freedom index map_
- light is good, dark is worse
- Belgium is 7th, France is 33th, UK is 40th


## Solution: VPN

- VPN traffic is easily detected
- Either costly or hard to set-up
- Privacy invasive

Note: VPN uses a specific protocol that can be detected (and generally specific ports)


## Solution: Tor

- Tor traffic is easily detected

Note: Tor uses a specific protocol that can be detected


## Solution: mirror

- Users rely on foreign entities
- They can be blocked too




------------------------------------------------------------

# Informo
<!-- .slide: data-background="#417D44" -->

### a federated information network


## Federated infrastructure

- Built on [![Matrix](img/matrix.png)<!-- .element: class="plain" style="height: 60px; margin: 0; vertical-align: middle;" -->](https://matrix.org)
    + Hides users' IP
    + Uses HTTPS (encrypted and harder to track)
    + Data is synchronised across the federation
    + Each server keeps a copy of all data sent
- Anybody can host a node
- The list of nodes is public

Notes: 
- User's IP is only known by user's entrypoint
- If the node goes down, users can switch to another known node
- __=> Anybody can send deceptive information__


## Trust management

- Organizations can share lists of:
    + Trusted information sources
    + Trusted organizations
    + Trusted servers
- User can trust
    + On per-entity basis
    + An organisation and its trusted entities

Notes:
- Similar to delegative / liquid democracy


## End-to-end signing

- Like E2E encryption, but without encryption
- Ensure information haven't been tampered with


------------------------------------------------------------

# Thanks!
<!-- .slide: data-background="#417D44" -->

- [__Github__: <u>https://github.com/informo</u>](https://github.com/informo)
- [__Read the specs__: <u>https://specs.informo.network</u>](https://specs.informo.network/)
- [__IRC__: `#informo` on chat.freenode.net](irc://chat.freenode.net/#informo)
- [__Matrix__: `#discuss:weu.informo.network`](https://matrix.to/#/!LppXGlMuWgaYNuljUr:weu.informo.network)
- __Mail__: <core@informo.network>

__Please come and contribute!__
