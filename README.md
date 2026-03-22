Amplificator Audio de Putere - Proiect CAD
Acest proiect reprezintă documentația și simularea unui amplificator audio de putere, realizat ca parte a disciplinei CAD (Computer-Aided Design). Circuitul este proiectat să preia un semnal de intrare de nivel foarte mic și să îl amplifice pentru a conduce o sarcină de joasă impedanță, respectând criterii stricte de filtrare și stabilitate.

📋 Specificații Tehnice
Tensiune de alimentare: ±20V (Simetrică)

Semnal de intrare (Vin): 750 µV

Tensiune de ieșire (Vout): 7V - 10V

Banda de frecvență: 180 Hz - 7500 Hz

Impedanță sarcină: 6 Ω (Ohm)

🏗️ Arhitectura Circuitului
Proiectul este structurat în cinci etaje principale, fiecare având un rol specific în procesarea semnalului:

Filtru Trece-Bandă: Limitează semnalul la intervalul de frecvențe dorit (180 Hz - 7.5 kHz), eliminând zgomotul de joasă și înaltă frecvență.

Etaj de Pre-amplificare: Utilizează un amplificator operațional TL082 pentru o primă treaptă de câștig.

Amplificarea în Tensiune: Realizată prin 5 etaje succesive folosind integrate de înaltă fidelitate OPA134/BB, obținând un câștig total de peste 9000.

Reglaj de Volum: Permite controlul nivelului de ieșire și asigură izolarea între etajele de câștig și cel de putere.

Etaj Final (Darlington): Configurație cu tranzistoare complementare TIP41C și TIP42C pentru a furniza curentul necesar sarcinii de 6 Ω.

🧪 Analize și Simulări (PSpice)
Performanța circuitului a fost validată prin multiple tipuri de simulări în mediul OrCAD:

Analiză Tranzitorie: Verificarea formei de undă la ieșire în raport cu intrarea.

AC Sweep: Determinarea răspunsului în frecvență și verificarea limitelor benzii de trecere.

Analiză Parametrică: Observarea modului în care modificarea anumitor componente influențează câștigul.

Analiza Monte Carlo & Worst Case: Testarea fiabilității circuitului luând în calcul toleranțele reale ale componentelor.

Analiză de Temperatură: Verificarea punctelor de funcționare în intervalul termic de operare.

🛠️ Tehnologii Utilizate
Software: Cadence OrCAD / PSpice

Componente cheie: TL082, OPA134, TIP41C, TIP42C

💡 Cum se utilizează
Descarcă fișierele proiectului (.DSN, .OPJ).

Deschide proiectul în OrCAD Capture.

Rulează profilurile de simulare predefinite pentru a vedea rezultatele analizelor menționate mai sus.

Autor: Isip Alexandru
An de studiu: II, Facultatea de Electronică, Telecomunicații și Tehnologia Informației (ETTI), UTCN.
