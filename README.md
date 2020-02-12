oe-methoden-lievelingsstad-opgave2
# Methoden gebruiken van het return type void met parameters
Maak de volgende methoden die parameters vragen, m.a.w. er wordt een bevel gegeven waarbij er meegegeven wordt waarop de methode zich moet baseren om het bevel uit te voeren.

## Methode WijzigBeschikbaarheidTaalKnoppen
Deze methode zorgt ervoor dat er altijd maar één button beschikbaar (enabled) is.
De parameter isNlBeschikbaar duidt aan of de btnNL al dan niet beschikbaar is. Voor de btnENG geldt steeds het tegenovergestelde.

De methode wordt gecalled bij het opstarten (btnENG beschikbaar) en bij btnNL_Click en btnENG_Click.

## WijzigZichtbaarheid
ToonKnoppen en VerbergKnoppen wordt gereduceerd tot één methode.

Deze methode ontvangt een parameter zichtbaarheid van het type Visibility en zal dus de waarde Visibility.Visible of Visibility.Hidden moeten ontvangen.

Verwijder nadien ToonKnoppen en VerbergKnoppen en pas de calls aan.
