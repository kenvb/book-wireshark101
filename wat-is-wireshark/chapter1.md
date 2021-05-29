# Wireshark

## Wat is Wireshark?

Wireshark is een Packet Capture programma. Het geeft ons de mogelijkheid om data die op onze NICs \(Network Interface Cards\) binnenkomen, te bekijken, te filteren en te manipuleren. Zo kunnen we problemen in het netwerk op een andere manier bekijken en misschien zelfs een oplossing formuleren. Wireshark is gratis voor Mac, Linux & Windows te downloaden op [https://www.wireshark.org/](https://www.wireshark.org/) .

## Wat is Wireshark niet?

Wireshark is niet je alles-oplosser: problemen die zich op applicatieniveau bevinden kunnnen we misschien observeren met Wireshark en misschien kunnen we met die informatie een suggestie formuleren, maar verwacht niet alle eigenaardigheden met software hiermee te kunnen oplossen. We kunnen hier wel mee aantonen dat het netwerk niet aan de bron van de problemen ligt.

## Hoe werkt Wireshark?

Dankzij het installeren van een bijkomende driver \(winpcap of npcap voor windows, libpcap voor \*ux\) die zich tussen je tcp/ip stack en de kernel van je OS zet, kunnen we effectief zien wat er op "de draad" zich afspeelt. Gedetailleerde informatie over hoe dit werkt kan je op deze oudere, doch nog steeds relevante website terugvinden: [https://winpcap.org/docs/docs\_412/html/group\_\_internals.html](https://winpcap.org/docs/docs_412/html/group__internals.html). Dit werkt ook voor Wireless NICs, maar dit heeft dan een paar beperkingen afhankelijk van je driver, adapter. Deze kan je oplossen door een Wirless NIC te kopen die actief kan monitoren en de Airpcap driver ondersteunt. Meer informatie over Wireless vind je in de Wireshark FAQ: [https://www.wireshark.org/faq.html\#q9.1](https://www.wireshark.org/faq.html#q9.1)

