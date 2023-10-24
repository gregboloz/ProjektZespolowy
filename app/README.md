1. Logika aplikacji - tabele
		a. Użytkownik
			i. Identyfikator użytkownika
			ii. Imię
			iii. Nazwisko
			iv. DOB
			v. Konto
			vi. Hasło
			vii. E-mail
		b. Konto
			i. Numer konta
			ii. Waluta
		c. Waluty
			i. Waluta podstawowa (np USD)
			ii. Waluty obce (kurs wobec waluty podstawowej - ale to pewnie będzie zaciągane z 

	2. Okna aplikacji
		a. Login
			i. (text box) Identyfikator użytkownika
			ii. (text box) Hasło
			iii. (button) Zaloguj się
			iv. (opcjonalnie) Reset hasła
		b. (opcjonalnie) Reset hasła
			i. Identyfikator użytkownika
			ii. Adres e-mail
			iii. (button) Resetuj hasło
		c. (po zalogowaniu) Pulpit
			i. Tekst box: "Witaj *nazwa użytkownika*"
			ii. (button) Przelew
			iii. (button) Kantor
			iv. (button) Saldo
			v. (button) Historia
		d. Przelew
			i. (text box) Podaj imię I nazwisko odbiorcy
			ii. (text box) Podaj numer konta
			iii. (text box) Kwota
			iv. (text box) Waluta
			v. (button) Wykonaj przelew
			vi. (button) Powrót
			vii. (note) Na tym etapie będzie weryfikowany:
				1) Stan konta w danej walucie. Jeżeli na koncie nie ma danej ilości waluty na przelew, pojawia się error pt: "nie masz tyle środków na koncie"
				2) Numer rachunku odbiorcy. Jeżeli jest błędny to pokaże się error, jeżeli poprawny to user zostanie przeniesiony do następnego okna
		e. Okno po przelewie
			i. (text box) "Dziękujemy, przelew został wykonany na następujące dane:
			ii. (text box) *numer konta*
			iii. (text box) *kwota* I *waluta*
			iv. (button) Powrót
		f. Kantor
			i. (text box) Sprzedaję:
			ii. (text box) Waluta
			iii. (text box) Kwota
			iv. (text box) Kupuję:
			v. (text box) Waluta
			vi. (text box) Kwota
			vii. (button) Wymień walutę
			viii. (note) Tutaj będzie następowała weryfikacja czy użytkownik ma wystarczająco dużo środków aby dokonać konwersji waluty. Jeżeli nie, pokazuje error
		g. Okno po Kantorze
			i. (text box) "Dziękujemy, wymieniłeś *kwota* *waluta* na *kwota* *waluta*
			ii. (button) Powrót
		h. Historia
			i. (text box) Data
			ii. (text box) Typ przelewu (wychodzący/przychodzący)
			iii. (text box) Numer konta
			iv. (text box) Kwota
			v. (button) Powrót
		i. Saldo 
			i. (text box) Numer rachunku
			ii. (text box) Kwota
			iii. (text box) Waluta
			iv. (button) Powrót
			v. (note) Po otwarciu okna zaciąga wszystkie salda I prezentuje w widoku - forma przedstawienia do ustalenia
			
			
		
			
			
		