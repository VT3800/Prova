# STRINGHE 
Per scrivere una stringa vengono utilizzati i doppi apici (“ ”) o quelli singoli (‘ ’). Con le stringhe si possono utilizzare differenti comandi:
* **Downcase**, converte la stringa in minuscolo;

	## >> 'PIPPO'.downcase 
	## => "pippo
* **Upcase**, converte la stringa in maiuscolo;


	## >> 'pippo'.upcase
	## => "PIPPO" </li>
* **Capitalize**, restituisce una capia della stringa con il primo carattere maiuscolo;
	## >> 'pippo'.capitalize <br>
	## => "Pippo"
* **Swapcase**, restituisce una stringa con i caratteri invertiti, minuscole al posto di maiuscole e viceversa;
	## >> 'PiPpO'.swapcase <br>
	## => "pIpPo" </li>
* **Chop**, elimina l’ultimo carattere della stringa; <br>
	## >> 'pippo'.chop 
	## => 'pipp'		
* **Split(delimitatore)**, divide la stringa in sottostringhe in base al delimitatore passato come argomento;
				>> 'ciao mondo'.split <br>
				=> ["ciao", "mondo"] <br>
				>> 'ciao mondo'.split('o') <br>
				=> ["cia", "m", "nd"] </li>
			<li> <b> “stringa1”+” stringa2” </b>, concatena le stringhe; <br>
				>> 'ciao ' + 'Pippo' <br>
				=> "ciao Pippo" </li>
			<li> <b> Reverse </b>, inverte la stringa(non utilizzabile con i numeri); <br>
				>> 'pippo'.reverse <br>
				=> "oppip" </li>
			<li> <b> Length </b>, mostra a video la lunghezza della stringa; <br>
				>> 'ciao Pippo'.length <br>
				=> 10 </li>
		</ul>
		---

		<ul>
			<li> <b> “stringa”*num </b>, replica la stringa per il numero di volte indicato da num; <br>
				>> 'pippo '*4 <br>
				=> "pippo pippo pippo pippo" </li> <br>
			<li> <b> \ </b>, è il carattere di escape, che trasforma il segno successivo in un carattere di tipo stringa e
			non viene visto come un simbolo di chiusura: es. ‘pippo è andato dall\’altra parte’, non visualizza errore se viene inserito un apice che funge da apostrofo; 
			Un altro utilizzo per non incappare in un errore è: “pippo  è andato dall’altra parte”, 
			dove vengono utilizzate le doppie virgolette in modo che se all’interno della frase viene messo un apice, quest’ultimo verrà visto come un carattere normale; <br> 
			<br>
				>> 'Pippo è andato dall\'altra parte' <br>
				=> "Pippo è andato dall'altra parte" <br>
				>> "Pippo è andato dall'altra parte" <br>
				=> "Pippo è andato dall'altra parte" </li>
		</ul>
		
