sono state testate il numero massimo di connessioni simultanee attive sul broker mqtt


Connessioni massime attive sono visibili contando il numero di messaggi CONNACK, che indicano la conferma all'apertura corretta di una connessione MQTT





connessioni simultanee massime
	1015 (numero di CONNACK)


Ntot=1024
Ns=1015
Ne=9


tempi:
	PRIMO PACCHETTO  (primo SYN della prima connessione)			:  4.624798851
	ULTIMO PACCHETTO (ultimo ACK relativo al FIN di chiusura connessione)   : 97.598778540
	
	DURATA ATTACCO: 92.973979689


dimensioni:
	BYTE TOTALI  (dal primo SYN all'ultimo ACK) : 649981

banda: 

	bps = (649981 * 8 ) / 92.974 = 55927.98


