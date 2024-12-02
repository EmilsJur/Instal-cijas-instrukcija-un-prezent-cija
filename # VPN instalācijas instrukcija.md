# VPN instalācijas instrukcija

## VPN sistēmu prasības
### Pirms VPN servisa izmantošanas ir jāparliecinās vai jūsu izmantotā ierīce nodrošina notieiktas prasības:
- Operētājsistēma - Windows, MacOS, Linux, Android, iOS
- Interneta pieslēgums - ir, un tas ir stabils
- Admin tiesības: jābūt adminstrātora piekļuve operētājsistēmā, dažos gadijumos varbūt nav vajadzīgs

## Servisa instalācijas paskaidrojums un soļi

## **! Jaizvēlās sev piemērots VPN serviss no vairākiem kuri ir pieejami, šī instrukcija būs domāta tiem, kas ir izvēlējušies OpenVPN un izmanto Windows operētājsistēmu. !**

### OpenVPN instalācijas soļi - Windows
 1. Apmeklēt OpenVPN mājaslapu un instalēt servisu pēc jūsu vajadzībām nepieciešamo versiju, ieteicams lādēt jaunāko un pārliecināties par savas ierīces 32 vai 64 bitu prasībām
- https://openvpn.net/community-downloads/
 2. Atverot .msi failu kuru jūs nolādējāt no mājaslapas, palaižot to, nākamais solis ir sekot līdzi ekrānā redzamajiem norādījumiem un apsverot savas vajadzības izvēlēties opcijas kas panāks to.
 3. Kad instalācija ir pabeigta, restartējiet jūsu ierīci, lai visi komponenti būtu ielādēti pareizi.
 4. Nākamais ir pieveinot VPN konfigurācijas failu lai mums būtu serveris pie kā pievienoties.
 #### 4.1 Ja jums ir jau VPN konfigurācijas fails, izmantojot labo pelītes taustiņu uz OpenVPN iconu uzdevumajoslā izvēlēties Import -> Konfigurācijas fails -> Open - Atļaujiet procesam beigties, ja ir nepieciešams ievadīt lietotājvardu un paroli izdariet to.
 #### 4.2. Gadijumā ja jums nav konfigurācijas fails, varat nolādēt bezmaksas variantus https://www.vpnbook.com/ mājaslapā sadaļā OpenVPN, iegaumējot arī doto lietotājvārdu un paroli. Sekojiet līdzi instalācijas procesam, kas ir jau minēts 4.1 punktā.
 5. Izdarot visus iepriekšos soļus servisam vajadzētu būt veiksmīgi ielādētam, lai palaistu un izveidotu savienojumu atveriet servisu un izvēlieties servera konfigurāciju kā arī nospiežiet pieslēgšanās pogu.
 6. Apsveicu! Esat veiksmīgi ielādējis OpenVPN servisu.
  
## OpenVPN testēšanas soļi
- Lai notestētu vai viss strādā kā paredzēts pēc servisa palaišanas varat pārbaudīt savu šobrīdējo IP adresi, piemēram, apmeklējot WhatIsMyIP mājaslapu - https://www.whatismyip.com
- Varat pielāgot VPN iestatījumus atbilstoši jūsu vajadzībām, piemēram, izvēlieties dažādus pieejamos protokolus, kā OpenVPN, IKEv2, WireGuard
- Ja nepieciešams, konfigurējiet DNS aizsardzību un automātisko vpn savienojumu.
