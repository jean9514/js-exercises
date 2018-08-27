# js-exercises
Back-to-school project

Dette er js-øvelser der skal vække vores hjerne efter en lang sommerferie. 


Hjælpe funktioner:

PS! husk at brug din comnsol.log.

funktioner til sammenlækning af tekst:

let tekst = "Eksempel på en tekst";
let len = tekst.length; // tekstens længde (20)
tekst=text.toUpperCase(); //teksten nu “EKSEMPEL PÅ TEKST”
tekst=text.toLowerCase(); //teksten nu “eksempel på tekst”
let sub = tekst.substring(0,7); // de første 7 tegn af teksten (“Eksempel”)
let pos = tekst.indexOf("på"); // position af “på” i tekst (9)


funktioner til taludregninger:

let tal = 3.5;
tal = Math.round(tal); // tal er nu afrundet til (4)
tal=Math.pow(tal,2); // tal opløftes til 2. potens (16)
tal =Math.random(); // tal er et tilfældigt tal mellem 0 og 1 (fx. 0.843219827740112)
tal= Math.round(Math.random()*10); // tal er nu et heltal mellem 0 og 10
erTal = Number(tal); // erTal er sand, hvis tal er et tal - eller falsk

Logiske operatore:

== 	Er lig med 
!= 	Ikke er lig med			
> 	Er større end			 
>= 	Er større end eller lig med	
< 	Er mindre end 			
<= 	Er mindre end eller lig med	
&& 	Og (mellem to betingelser, begge betingelser skal være opfyldte)			
|| 	Eller (mellem to betingelser, en af betingelserne skal være opfyldt )				
! 	Ikke (foran en betingelse)


Tal operatorer:

+ Addition 
eks: 		pris = indkobsPris + moms;
- Subtraction
eks: 		indkobsPris = pris - moms;
* Multiplication
eks: 		totalPris = antal * pris;
/ Division
eks: 		pris = totalPris/antal;

++ Increment
eks: 		antal++;
-- Decrement
eks: 		antal--;