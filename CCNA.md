---
title: CCNA

---
title: 'CCNA'
---
<style>
.two-column-layout {
  column-count: 2; /* Set column number */
  column-gap: 20px;
  max-width: 100%;
  overflow: hidden;
}
@media (max-width: 768px) {
  .two-column-layout {
    column-count: 1; /* Switch to single column on small screens */
    column-gap: 0;   /* Optional: Set gap to 0 for single column */
  }
}

.markdown-body, .ui-infobar {
    max-width: unset !important;
}

.two-column-layout ul, 
.two-column-layout ol {
  margin: 0;
  padding-left: 20px;
}

.two-column-layout strong {
  font-weight: bold;
}

.two-column-layout em {
  font-style: italic;
}
    
.two-column-layout h1,
.two-column-layout h2,
.two-column-layout h3,
.two-column-layout h4,
.two-column-layout h5,
.two-column-layout h6 {
    margin-top: 0;    
}
</style>
<style>
.three-column-layout {
    display: flex; /* Use flexbox for layout */
    justify-content: space-between; /* Space between columns */
}

.three-column-layout > div {
    flex: 100; /* Each column takes equal space */
    margin: 10px; /* Add some margin between columns */
}

.three-column-layout h4 {
    margin: 0; /* Reset margin */
    padding: 0; /* Reset padding */
    text-align: left; /* Center align the titles */
}

.three-column-layout p {
    margin-top: 10px; /* Add some space above the paragraph */
}
</style>
# Inhoud
* [Networks Connect Us](https://hackmd.io/dDu8WELgSRGvO0CEY6XFCA?both#Networks-connect-us)
* [No Boundries](https://hackmd.io/dDu8WELgSRGvO0CEY6XFCA?both#No-Boundries)
* [Components](https://hackmd.io/dDu8WELgSRGvO0CEY6XFCA?both#Components)
    * [Hosts/End Devices](https://hackmd.io/dDu8WELgSRGvO0CEY6XFCA?both#Hostsend-devices)
    * [IP-adressen](https://hackmd.io/dDu8WELgSRGvO0CEY6XFCA?view#IP-adres)
    * [Subnet Masker](https://hackmd.io/dDu8WELgSRGvO0CEY6XFCA?view#Subnet-masker)
    * [Peer-to-Peer](https://hackmd.io/dDu8WELgSRGvO0CEY6XFCA?view#Peer-to-Peer)
    * [Intermediary Devices](https://hackmd.io/dDu8WELgSRGvO0CEY6XFCA?view#Intermediary-devices)
* [Media](https://hackmd.io/dDu8WELgSRGvO0CEY6XFCA?view#Media)
    * [Koper](https://hackmd.io/dDu8WELgSRGvO0CEY6XFCA?view#Koper)
        * [Types](https://hackmd.io/dDu8WELgSRGvO0CEY6XFCA?view#Types)
    * [Fiber](https://hackmd.io/dDu8WELgSRGvO0CEY6XFCA?view#Fiber)
        * [Types](https://hackmd.io/dDu8WELgSRGvO0CEY6XFCA?view#Types16)
    * [Wireless](https://hackmd.io/dDu8WELgSRGvO0CEY6XFCA?view#Wireless)
        * [Types](https://hackmd.io/dDu8WELgSRGvO0CEY6XFCA?view#Types20)
    * [Converging Networks](https://hackmd.io/dDu8WELgSRGvO0CEY6XFCA?view#converging-networks)
    * [Type Connectie](https://hackmd.io/dDu8WELgSRGvO0CEY6XFCA?view#Type-connectie)
        * [Kabel](https://hackmd.io/dDu8WELgSRGvO0CEY6XFCA?view#Kabel)
        * [DSL](https://hackmd.io/dDu8WELgSRGvO0CEY6XFCA?view#DSL)
        * [Cellular](https://hackmd.io/dDu8WELgSRGvO0CEY6XFCA?view#Cellular)
        * [Satteliet](https://hackmd.io/dDu8WELgSRGvO0CEY6XFCA?view#Satteliet)
* [Topologies](https://hackmd.io/dDu8WELgSRGvO0CEY6XFCA?view#Topologies)
    * [Physical]()
    * [Logical]()
    * [WAN Topologies]()
        * [Point-to-Point]()
        * [Hub en Spoke]()
        * [Mesh]()
    * [Type Connectie]()
        * [LAN]()
        * [WAN]()
        * [Internet]()
        * [Intranet]()
        * [Extranet]()
    * [Reliable Networks](https://hackmd.io/dDu8WELgSRGvO0CEY6XFCA?both#Reliable-Networks)




# Networks Connect Us
Chatting
Gaming

# No Boundries
We hebben overal internet door sattelieten

# Components
## Hosts/End Devices
alle apparaten die deelnemen in netwerk communicatie
een end device is een PC, tablet, smartphone
<div style="text-align: center;">
  <img src="https://i.imgur.com/dBMuX1r.png">
</div>

## Nodes
* Toestel dat data kan
    * Ontvangen
    * Doorsturen
    * Opslaan
    * Genereren
## IP-adres
Elke host heeft een IP-adres. Dit maakt het mogelijk om het netwerk en de hosts in dit netwerk te identificeren.
## Subnet Masker
Splitst IP-adres in Netwerk en Host deel

## Peer-to-Peer
2 of meer hosts die direct en gelijk contact met elkaar hebben.
* makkelijk om op te bouwen
* goedkoop
* onveilig
* minder performant

## Intermediary Devices
* Switches
* Routers
* Firewall

Hebben geen eigen IP (meestal). Versterken en doorsturen van signalen.
<div style="text-align: center;">
  <img src="https://i.imgur.com/50fnWna.png">
</div>

# Media
## Koper
Data wordt doorgestuurd als elektrisch signaal
* Kan verstoord worden door EMI en RFI
<div style="text-align: center;">
  <img src="https://i.imgur.com/CPIgmD7.png">
</div>

### Types  

<div class="three-column-layout">
    <div>
        <h4>UTP</h4>
        <p>niet beschermd tegen EMI en RFI</p>
    </div>
    <div>
        <h4>STP</h4>
        <p>Metalen behuizing die beschermd tegen EMI en RFI</p>
    </div>
    <div>
        <h4>COAX</h4>
        <p>Radiofrequenties dragen</p>
    </div>
</div>

## Fiber
Zeer dun glas dat lichtpulsen geleidt
### Types

<div class="two-column-layout">

#### SMF
* licht gaat rechtdoor
* half duplex
* 100 km
 <div style="text-align: center;">
  <img src="https://i.imgur.com/hltyx5H.png">
 </div>

#### MMF
* licht botst tegen wand
* full duplex
* 550 m
 <div style="text-align: center;">
  <img src="https://i.imgur.com/hltyx5H.png">
 </div>
</div>

## Koper vs Fiber

 <div style="text-align: center;">
  <img src="https://i.imgur.com/lNmpRG6.png">
 </div>

## Wireless
* EM-signalen gedragen door radio- of microgolven
* kleine oppervlakte
* storingen door andere draadloze apparaten en microgolven
* altijd half duplex
### Types
* WiFi
* Bluetooth
* Wimax
* Zigbee (IoT)
## Converging networks 
* alle communicatie verloopt via hetzelfde medium 

## Type connectie
### Kabel
* Hoge bandbreedte
* Hoge beschikbaarheid
* Altijd online
### DSL
* =kabel MAAR download ≠ upload
### Cellular
* Verbinding met telefoonmast
### Satteliet
* Goed voor afgelegen gebieden

# Topologies
<div class="two-column-layout">

## Physical
Op welke plaats staan de apparaten?
<div style="text-align: center;">
  <img src="https://i.imgur.com/r9nQ12f.png">
</div>

## Logical
Tot welk netwerk behoren de apparaten?
<div style="text-align: center;">
  <img src="https://i.imgur.com/kYn6yIu.png">
</div>
</div>

## WAN Topologies

<div style="display: flex; justify-content: space-between;">

<div style="flex: 1; margin: 10px; text-align: left;">
    <h3>Point-to-Point</h3>
    <p>Permanente link tussen 2 routers</p>
    <img src="https://i.imgur.com/xl4URWo.png">
</div>

<div style="flex: 1; margin: 10px; text-align: left;">
    <h3>Hub en Spoke</h3>
    <p>Verbindt meerdere routers met elkaar adhv een Point-to-Point connectie naar een centrale router</p>
    <img src="https://i.imgur.com/pwGijqg.png">
</div>

<div style="flex: 1; margin: 10px; text-align: left;">
    <h3>Mesh</h3>
    <p>Elke router is verbonden met elkaar door een Point-to-Point connectie tussen elke router</p>
    <img src="https://i.imgur.com/ZCASkKW.png">
</div>
</div>

## Type Connectie
<div style= "text-align: center;">
<div class="three-column-layout">
    <div>
        <h3>LAN</h3>
        Klein gebied
        (vb. thuis, school, bedrijf)
    </div>
    <div>
        <h3>WAN</h3>
        2 LAN's die met elkaar verbonden worden
    </div>
    <div>
        <h3>Internet</h3>
        Alle LAN's en WAN's samen
    </div>
</div>

<div class="two-column-layout">
    <h3>Intranet</h3>
    <p>Privé connectie binnen een bedrijf/organisatie</p>
    <h3>Extranet</h3>
    <p>Connectie voor mensen buiten het bedrijf die toegang tot specifieke data nodig hebben</p>
</div>
</div>


## Reliable Networks
### Fault Tolerance
Als er één apparaat uitvalt moet dit opgevangen worden door een ander toestel

<div style="text-align: center;">
  <img src="https://i.imgur.com/lhI5KrA.png">
</div>

### Scalability
Er kunnen meer apparaten op hetzelfde netwerk zonder dat dit een impact heeft op de performantie
<div style="text-align: center;">
  <img src="https://i.imgur.com/jbe5k0Q.png">
</div>

### Quality of Service
Er wordt onderscheid gemaakt tussen de prioriteit van de services
vb. mail < VoIP
<div style="text-align: center;">
  <img src="https://i.imgur.com/80GnUK4.png">
</div>

### Security
Het netwerk beschermen tegen personen die geen toegang zouden mogen hebben, zowel fysiek als online
#### Threats
<div style="text-align: center;">
  <img src="https://i.imgur.com/WOfAs6C.png">
</div>

| External | Kan geblokkeerd worden door Firewall |
| -------- | -------- |
| Internal     | Groter risico sinds BYOD     |

| Solutions ||
| -------- | -------- |
| Firewall| Verkeer filteren op basis van poorten en IP-adressen|
| Access Control List |Filteren op basis van applicaties en IP-adressen|
| Intrusion Prevention System |Snel verspreidende threaths onderscheppen|
| Virtual Private Network | Veilige toegang voor externe gebruikers tot het intern netwerk |

## Trends
### BYOD
Persoonlijke apparaten gebruiken op het netwerk van bedrijf
### Online Collab
Online meetings/samenwerken
vb. Teams
### Cloud Computing
Data opslaan op servers over heel het internet
### Wireless Broadband
Internet op afgelegen gebieden door gsm-masten

## Communicatie
* Source = zender
* Destination = ontvanger
* Channel = weg tussen zender en ontvanger

### Rules
* Zender en ontvanger moeten geïdentificeerd worden

<div class='three-column-layout'>
    <div style='column'>
    <h4>Broadcast</h4>
        <p>Wordt naar elk toestel verzonden behalve de zender</p>
    </div>
    <div style='column'>
    <h4>Multicast</h4>
        <p>Wordt naar een speciaal multicast adres gestuurd</p>
    </div>
    <div style='column'>
    <h4>Unicast</h4>
        <p>Wordt naar één toestel gestuurd</p>
    </div>
</div>

### Encoding
* Zender verpakt data = encoding
* Verstuurd de verpakte data = channeling
* Ontvanger pakt data uit = decoding

### Encapsulating
* Data wordt verpakt in header met Source en Destination

### Size
* Er kan niet oneindig veel data in één pakket
* Te grote pakketten worden opgesplitst

### Timing
**Flow Control**
* Snelheid en hoeveelheid data  

**Response Timeout**
* Zender antwoord niet
    * Opnieuw verzenden

**Access Methods**
* 2 apparaten kunnen niet tegelijk met elkaar praten

## Protocols
<div style="text-align:center;">
  <img src="https://i.imgur.com/ftolkLD.png"></div>
  
### Segmenting
* Verhoogde snelheid
    * Veel kleine bestanden
* Verhoogde efficiëntie
    * Als één pakket failed moet één klein pakket vestuurd worden ipv één groot pakket

### Sequencing
* Pakketjes nummeren om opnieuw aan elkaar te kunnen plakken in de juiste volgorde

### Protocol Data Units (PDU)
<div style="text-align:center;">
  <img src="https://i.imgur.com/m8EIMET.png"></div>

## Physical Layer
* Fysieke connectie tussen End-Devices mbv medium
### Components
**Bandwidth**
* Maximum hoeveelheid data kan worden verstuurd in een bepaalde tijd
<div class='three-column-layout'>
    <div style='column'>
    <h4>Latency</h4>
        <p>Tijd tussen het sturen en ontvangen</p>
    </div>
    <div style='column'>
    <h4>Throughput</h4>
        <p>Hoeveelheid data wordt verstuurd in een bepaalde tijd</p>
    </div>
    <div style='column'>
    <h4>Goodput</h4>
        <p>Bruikbare data in een bepaalde tijd (puur data zonder headers</p>
    </div>
</div>

## Data-Link Layer
* Toegang naar de hogere lagen
* Encapsulatie van layer 3 naar layer 2
* Error detectie




# Switching
### Ingress
* De poort waar een frame binnenkomt
* Input
### Egress
* De poort waar een frame buitengaat
* Output/Exit

### MAC-adres tabel/CAM tabel
* Associatie tussen source-poort en source-MAC-adres
<div class='two-column-layout'>
    <h4>Source leren</h4>
    <div style="text-align:center;">
  <img src="https://i.imgur.com/mQ0zxxA.png"></div>
    <h4>Destination leren</h4>
    <div style="text-align:center;">
  <img src="https://i.imgur.com/RrN94PS.png"></div>
</div>

### Forwarding methodes
<div class='three-column-layout'>
    <div class='column'>
    <h4>Store-and-Forward</h4>
        <p>Ontvangt volledige frame voor doorsturen</p>
        <p>Maakt gebruik van CRC om fouten te detecteren</p>
    <div style="text-align:center;">
        <img src="https://i.imgur.com/8DN2bJs.png">
    </div>
    </div>
    <div class='column'>
    <h4>Cut-Through</h4>
        <p>Ontvangt enkel destination MAC-adres voor doorsturen</p>
        <p>Sneller dan Store-and-Forward maar voert geen checks uit</p>
    <div style="text-align:center;">
            <img src="https://i.imgur.com/zN4ztE7.png">
        </div>
    </div>
    <div class='column'>
    <h4>Fragment-Free</h4>
        <p>Gelijk aan Cut-Through maar voert WEL een error-check uit</p>
        <p>Trager dan Cut-Through maar bijna onzichtbaar</p>
        <div style="text-align:center;">
            <img src="https://i.imgur.com/sIHz63A.png">
        </div>
    </div>
</div>

### Collision Domains
Devices op éénzelfde medium en dezelfde bandwidth delen zijn **Collision Domains** (meestal bij Half-Duplex)  
#### Collision
Frames die "botsen" door communicatie op hetzelfde moment op éénzelfde medium

### Broadcast Domains
De samenhang van verschillende (met elkaar verbonden) switches (+ alle toestellen die een broadcast kunnen ontvangen) vormen een **Broadcast Domain**  

Enkel layer3 toestellen kunnen **Broadcast Domains** scheiden van elkaar

#### Congestion
Meer frames op éénzelfde medium dan dit medium kan verwerken
## Congestion opheffen
### Switch karakteristieken
* Full-Duplex poorten
* Hoge poort-snelheid (100Mbps - 100 Gbps)
* Intern geheugen
* Grote frame buffers
* Poort densiteit
    --> hoeveelheid poorten op één switch

## VLAN
één switch opdelen in meerdere kleine switches
* Meerdere logische netwerken (zie [Topologies](https://hackmd.io/dDu8WELgSRGvO0CEY6XFCA?view#Topologies))
* Splitsen van grote **Broadcast Domains**
* Policies instellen per VLAN
<div style="text-align:center;">
    <img src="https://i.imgur.com/EGsKcuE.png"></div>

### Voordelen
<div style="text-align:center;">
    <img src="https://i.imgur.com/Al3NnTa.png"></div>

### Type VLAN
* Default
    * Alle poorten behoren tot "VLAN 1"
    * VLAN 1 is de standaard VLAN
    * VLAN 1 is de beheer VLAN
    * VLAN 1 kan niet verwijderd of hernoemd worden
* Data
    * Verdelen netwerk in groepen gebruikers of toestellen
    * Wordt gebruikt door toestellen die data moeten verzenden/ontvangen
* Native
    * Taggen van frames
    * Enkel trunk links
    * Hier komen untagged frames terecht
* Management
    * Specifieke poort voor netwerk beheer
        * SHH, Telnet, ...
* Voice (outdated)
    * Ondersteund VoIP
        * Hoge bandbreedte
        * Prioriteit over ander netwerk verkeer
        * delay <150ms over heel het netwerk
<div style="text-align:center;">
    <img src="https://i.imgur.com/6ihn7V4.png"></div>

## VLAN Trunks
* Dragen van VLAN verkeer tussen switches
* Toestellen van verschillende switches verbinden zonder router
* Point-to-Point verbinding
* Hoort niet tot één VLAN
* VLAN ID van tagged frame = Native VLAN --> Frame Drop
<div style="text-align:center;">
    <img src="https://i.imgur.com/t3Xw8Im.png">
</div>

## Voice Tagging
<div style="text-align:center;">
    <img src="https://i.imgur.com/e9FE8Eu.png">
</div>

<div style="text-align:center;">
    <img src="https://i.imgur.com/OJ3KChc.png"></div>

### VLAN identificatie
Ethernet frame header bevat standaard geen VLAN informatie
* Tagging
    * 4 bytes binnen originele Ethernet frame header plaatsen
    * FCS opnieuw berekenen
<div style="text-align:center;">
    <img src="https://hackmd.io/_uploads/SywlHqgqyx.png"></div>

## Normal Range VLAN
* VLAN ID 1 - 1005
* 1, 1002, 1005 zijn vaste VLAN ID's
* Configuratie in Flash Memory (vlan.dat)
## Extended Range VLAN
* Vooral gebruikt door ISP
* VLAN ID 1006 - 4094
* Configuratie in Running-Config
* Minder features

# Inter-VLAN Routing
Doorsturen van verkeer tussen verschillende VLAN's

<div class='three-column-layout'>
<div style='column'>
    <h3>Legacy</h3>
    <p>Geen scalability</p>
    <p>één router interface per VLAN</p>
        <div style="text-align:center;">
        <img src="https://hackmd.io/_uploads/ByvNc1ccJe.png">
        </div>
</div>
<div style='column'>
    <h3>Router-on-a-stick</h3>
    <p>Goed voor klein tot middelgrote netwerken</p>
    <p>Router heeft subinterfaces (zie video)</p>
<iframe title="vimeo-player" src="https://player.vimeo.com/video/1059709725?h=94ed6f3b5c" width="640" height="360" frameborder="0"    allowfullscreen>
</iframe>
</div>
<div style='column'>
    <h3>Layer 3 Switch</h3>
    <p>Goede scalability voor grote tot middelgrote netwerken</p>
    <p>Werkt hetzelfde als een router-on-a-stick</p>
<div style="text-align:center;">
    <img src="https://hackmd.io/_uploads/rJCKWl9ckg.png">
</div>
</div>
</div>





























# Switch, Router en End-device configuratie
**OS**
* Kernel
* Shell

**GUI en CLI**
* Graphical User Interface
* Command Line Interface

**Access Methods**
* Console
    * Fysieke connectie met het toestel
* SSH
    * Remote connectie met het toestel (veilig)
* Telnet
    * Remote connectie met het toestel (onvelig)
## Navigation
**Command Modes**
* User Exec
        * Gelimiteerd aantal commando's
* Privileged Exec
        * Alle commando's beschikbaar
    * Line Config
        * conosle
        * vty
    * Interface Config
        * poorten
        
**Command Structure**
<div style="text-align: center;">
  <img src="https://hackmd.io/_uploads/SJW8uyctkg.png">
</div>

## Device Configuration
### Device Names
* Start met letters
* Geen spaties
* Eindigen met letter of cijfer
* <64 karakters
* Enkel letter, cijfers, streepjes

``Switch# configure terminal``
``Switch(config)# hostname Sw-Floor-1``
``Sw-Floor-1(config)#``
### Passwords
* 8+ karakters
* Hoofd- en kleine letters
* Cijfers
* Speciale karakters

#### Password instellen
``Sw-Floor-1# configure terminal``
``Sw-Floor-1(config)# line console 0``
``Sw-Floor-1(config-line)# password cisco``
``Sw-Floor-1(config-line)# login``

#### Secret password instellen
``Sw-Floor-1# configure terminal``
``Sw-Floor-1(config)# enable secret class``

#### Passwords encrypteren
``Sw-Floor-1# configure terminal``
``Sw-Floor-1(config)# service password-encryption``

### Banner/MOTD
Belangrijk voor legaal hackers aan te klagen

``Sw-Floor-1# configure terminal``
``Sw-Floor-1(config)# banner motd #Authorized Access Only#``

### Configuratie opslaan
``Sw-Floor-1# copy running-config startup-config``
<div class="two-column-layout">

<h4>Startup-config</h4>
<p>* Opstart commando's</p>
<p>* NVRAM</p>
<p>* Content blijft behouden na reboot</p>    
<h4>Running-config</h4>
<p> * Aanpassingen worden meteen toegepast</p> 
<p> * RAM</p> 
<p> * Content gaat verloren na reboot</p> 
</div>

---

### VLAN configuratie
``Sw-Floor-1# configure terminal``
``Sw-Floor-1(config)# interface vlan 1``
``Sw-Floor-1(config-if)# ip address 192.168.1.20    255.255.255.0``
``Sw-Floor-1(config-if)# no shutdown``
``Sw-Floor-1(config-if)# exit``
``Sw-Floor-1(config)# ip default-gateway 192.168.1.1``
<div style="text-align:center;">
    <img src="https://hackmd.io/_uploads/r1Vr5oe9kl.png">
</div>

<div style="text-align:center;">
    <img src="https://hackmd.io/_uploads/SJx_9jxcJl.png">
</div>

<div style="text-align:center;">
    <img src="https://hackmd.io/_uploads/SJNnMg991l.png">
</div>

## Subinterfaces Router-On-A-Stick
<div style="text-align:center;">
    <img src="https://hackmd.io/_uploads/ByMMmecqkl.png">
</div>
