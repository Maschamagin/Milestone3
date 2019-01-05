/*

Wichtige Notizen zum Projekt. 

Was macht die Aktivierungsfunktion ? -- Bestimmt die Ausgabe des Neurons. 

Wichtige Aufgaben: 
Das Eingabe Layer : anfangs mit dem startvektor und einer Matrix, in dem die Gewichte von Layer i zu Layer i + 1 gespeichert werden. 
Eingabeaggregation: bestimmt den neuen Ausgabevektor.

----------------------------------------------------------------------------------------------------------------------------------------------------------------
Berechnung des Hidden Layers:
F�r jedes Layer entsteht ein neues Ausgabenvektor pvec. Die Eintr�ge in pvec sind die neuen koeffizienten zur bestimmung der neuen gewichte.
Wie wird dieses neue pvec bestimmt ? pvec(i) = f(xi) (die Berechnung des neuen Vektors entsteht koeffizient f�r koeffizient.
Bestimmung der neuen Gewichte f�r Layer i + 1 : Hierzu wird der Ausgabevektor aus Layer i mit der Matrix von Layer i multipliziert. 

----------------------------------------------------------------------------------------------------------------------------------------------------------------
Output des Neuronalen Netzes: 

Der Outpout des neuronalen Netzes ist ein Vektor !. 
*/