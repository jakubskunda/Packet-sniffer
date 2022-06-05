# Packet sniffer
 
### Preklad:
projekt sa prelozi prikazom **make**

### Spustenie projektu:
**./ipk-sniffer [-i rozhraní | --interface rozhraní] {-p ­­port} {[--tcp|-t] [--udp|-u] [--arp] [--icmp] } {-n num}**

kde:
**i** alebo **interface** je nazov rozhrania na ktorom sa bude posluchat
**p** je port podla ktoreho sa bude filtrovat
**tcp** alebo **t** bude zobrazovat iba TCP pakety
**udp** alebo **u** bude zobrazovat iba UDP pakety
**arp** bude zobrazovat iba ARP ramce
**icmp** bude zobrazovat iba ICMP a ICMPv6 pakety
**n** pocet paketov, ktore sa maju zobrazit
**h** alebo **help** vypise napovedu
