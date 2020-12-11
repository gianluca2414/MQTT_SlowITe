Prova per vedere quanto tempo rimane attiva la connessione con un keep alive di 60 secondi.

i risultati sono stati validati, rimane aperta per 90 secondi circa. Calcoli precisi sul foglio


tempi:

	SYN - CONNECT :          		2.55591 * 10^-4

	CONNECT - CONNACK :      		4.0412 * 10^-5

	CONNACK - FIN :          		90.73028705
	
	CONNACK - ACK (del FIN) : 		90.7730097

	DURATA_TOT -> 1° SYN - ACK (del FIN) :  90.77330577

	
dimensioni:
	
	BYTE TOT: 629 [ dipendenti dal client_id utilizzato, nel nostro caso dim(client_id) = 1 byte ]

banda usata:
	
	bps: (629*8)/90.77330577 = 55.435





Hardware:
	Intel(R) Core(TM) i5-6267U CPU @ 2.90GHz (with SSE4.2)
OS:
	Linux 4.15.0-108-generic
Application:
	Dumpcap (Wireshark) 2.6.10 (Git v2.6.10 packaged as 2.6.10-1~ubuntu18.04.0)
