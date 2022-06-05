# Packet sniffer
 
### Preklad:
projekt sa prelozi prikazom **make**

### Spustenie projektu:
**./ipk-sniffer [-i rozhraní | --interface rozhraní] {-p ­­port} {[--tcp|-t] [--udp|-u] [--arp] [--icmp] } {-n num}**

kde: <br>
  **i** alebo **interface** je nazov rozhrania na ktorom sa bude posluchat <br>
  **p** je port podla ktoreho sa bude filtrovat <br>
  **tcp** alebo **t** bude zobrazovat iba TCP pakety <br>
  **udp** alebo **u** bude zobrazovat iba UDP pakety <br>
  **arp** bude zobrazovat iba ARP ramce <br>
  **icmp** bude zobrazovat iba ICMP a ICMPv6 pakety <br>
  **n** pocet paketov, ktore sa maju zobrazit <br>
  **h** alebo **help** vypise napovedu
