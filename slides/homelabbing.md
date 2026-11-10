---
title: "IT-Lab - homelabbing"
---

# Homelabbing

---

## What is homelabbing?

### Definition from Wiktionary:

> (computing) A server set up in one's home for the purpose of testing various configurations of hardware, operating systems, etc.

---

## What is homelabbing?

> (nederlands) Een prutsomgeving waar niets aan vasthangt, waar je te veel tijd, geld en moeite insteekt.

---

## Why should it matter to me?

Productie-systeem, maar niet helemaal:

- Geen SLA's
- Geen tijdsrestricties
- On-premise
- Geen boze klanten*

---

## Experimentatie - virtualisatie

- Virtualisatie: efficiënt gebruiken van hardware
- VirtualBox: good in a pinch/tijdelijk testen, maar geen permanente services
- Type 2 hypervisor versus Native OF Type 1 Hypervisor!
- Persoonlijke sandbox -> if it breaks, it breaks.

---


## Experimentatie - goede leersschool

- Persoonlijke sandbox -> if it breaks, it breaks.
- Geen verwachtingen, regels of verplichtingen
- Technische skills en leren documenteren...

---


## Digital sovereignty

> Fancy mandatory buzzword, MAAR!

- Onafhankelijk van Cloud (en Big Tech)
- Data privacy!
- Open Source!
- Transparantie!
- Geen licentiekosten of abonnementen!

---

## Getting started

### Start small!

- Oude laptop, oude PC
- Hardware moet niet extreem sterk zijn
- Zeker nu: RAMpocalypse


---

# Linux, Linux, Linux

- Linux is your best friend!
- 1 toestel met Linux en Docker (Compose) geïnstallerd -> meer heb je niet nodig!
- Kijk (eerst) naar een basisdistro (Ubuntu Server, AlmaLinux, ...)
- Headless/CLI: veel minder resources nodig dan GUI 

---

# Docker

- Virtualisatie op applicatie-niveau
- Niet de focus van vandaag, maar fantastische tool
- Meer info? Online en slides van [IT-Lab Workshop](https://hogent-it-lab.github.io/docker-workshop/slides)

---


## Hardware

- Zoek tweedehands!
- Oude laptops/toestellen repurposen
- Navraag bij vrienden/familie
- Mensen smijten vaak dingen weg die voor ons nog bruikbaar zijn

---

## Fancy stuff

- Type 1 Hypervisor* (**Proxmox**)
- Custom domain name with HTTPS (**Caddy** of een andere reverse proxy)
- Storage for network and clients (**NAS**)

---

# Small homelab tour

![](./img/Homelab_rack.JPG)

---

## Small homelab tour - toestellen

- Proxmodes nodes (2 actief, 2 WIP)
- UniFi router
- TP-Link switch (unmanaged)
- Raspberry Pi 5 (flex/experimenteel)
- Asustor NAS

---

## Devices - Proxmox nodes

- HP Prodesk - 8 GB RAM scavenged uitgefaseerd bij klant na PC-upgrade
- Lenovo ThinkCentre - 16 GB RAM scavenged 2ehands.be

---

## Devices - HP Prodesk

![](./img/HP_Prodesk.jpg)

---

## Devices - Lenovo ThinkCenter

![](./img/Lenovo_ThinkCentre.jpg)

---

## Devices - UniFi router

![](./img/UniFi_Dream_Router.jpeg)

---

## Devices - Unmanaged switch

![](./img/TPLink_switch.jpg)

---

## Devices - NAS

![](./img/Asustor_NAS.jpg)

---

## Dashboard software tour (Homarr)

- Nextcloud
- Jellyfin
- Immich
- Pihole
- Home assistant (WIP)
- Netbox

---

## Secure remote access (VPN)

- Tailscale
- Toegang tot hele netwerk (subnet router functionaliteit)
- 1 Tailscale node in netwerk


---

## Show weekmenu application

<!-- Demonstration of a practical homelab application -->
