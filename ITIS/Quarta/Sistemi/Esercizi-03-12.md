1\) Discuti il metodo di comunicazione utilizzato da Internet



Internet usa un metodo di comunicazione a commutazione di pacchetto (packet switching).

Il messaggio viene diviso in pacchetti che viaggiano indipendentemente attraverso la rete, scegliendo ogni volta il percorso più efficiente. Il router decide il cammino sulla base delle tabelle di instradamento.



2\) Quali sono i compiti del protocollo IP?



Il protocollo IP si occupa di:

* Indirizzamento dei dispositivi (IP sorgente e destinazione).
* Instradamento: scelta del percorso tramite router.



3\) Soluzioni per l’esaurimento degli indirizzi IPv4



CIDR (Classless Inter-Domain Routing): uso efficiente dei blocchi di indirizzi.

VLSM (Variable Length Subnet Mask): Subnet mask variabile per ridurre lo spreco.

NAT (Network Address Translation): riutilizzo degli indirizzi privati.

IPv6: nuovo protocollo con indirizzi a 128 bit, praticamente infiniti.



4\) Struttura di una tabella di routing



Ogni riga contiene:

Rete di destinazione

Subnet mask / prefisso

Gateway

Interfaccia di uscita



5\) Differenza tra switch e router



Switch

Lavora a livello 2 (Data Link).

Usa gli indirizzi MAC.

Commutazione all’interno di una LAN.

Non separa reti diverse.



Router

Lavora a livello 3 (Network).

Usa indirizzi IP.

Instrada pacchetti tra reti diverse.



6\) Vantaggi topologia a stella



Facilmente espandibile.

Guasto di un cavo → non influenza gli altri nodi.

Facile da diagnosticare.

Prestazioni elevate.





