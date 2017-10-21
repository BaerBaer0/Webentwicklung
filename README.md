# Webentwicklung
ToDo

- Button ändern mit textfeld - unter benutzernamen (regestrieren)
- Benutzernamen usammegeschrieben und unterstrich farbe ändern  (check)

- Mitarbeiter button farben - rot (#783040)					(Buttons bsp. unten)
- Logout rechts oben
- Logout auf jede seite										(Adminbereich check)
- Button wo man auf Skillprofile wieder kommt
- Button Dropdown

- Projektleiter - Buttonfarbe ändern
- Auf Icons einigen
- "laufende Projekte" - anfertigen (Beispiel ausfüllen)
- Deadline (Countdown) bei laufende Projekte
- Personen - gesichter ändern
- Aufklappen der Personenfotos
- Suchleiste (Mitarbeiter Suchen)
- Filter 
- Kontaktbuttons 
	- bug behaftet farbe geändert

- Admin - links einfärben									(Check)


##Beispiele
Button:

	.btn, .btn-large {
		color: #000;
		background-color: #fff;	
		
	}
	
	.btn:hover, .btn-large:hover {
		background-color: #783040;
		color:#fff;
	}
	
Kontaktbuttons:
	- bug behaftet farbe geändert sich nur durch klicken

	/* label color */
	.input-field label {
		color: #783040;
	}
	/* label focus color */
	.input-field input[type=text]:focus+label {
		color: #783040;
	}
	/* label underline focus color */
	.input-field input[type=text]:focus {
		border-bottom: 1px solid #783040;
		box-shadow: 0 1px 0 0 #783040;
	}
	/* valid color */
	.input-field input[type=text].valid {
		border-bottom: 1px solid #783040;
		box-shadow: 0 1px 0 0 #783040;
	}
	/* invalid color */
	.input-field input[type=text].invalid {
		border-bottom: 1px solid #783040;
		box-shadow: 0 1px 0 0 #783040;
	}
	/* icon prefix focus color */
	.input-field .prefix.active {
		color: #783040;
	}
	
	.a.waves-effect waves-light.btn {
		background-color: #783040;
	}
	
	.input-field{
		color: #000;
	}