# Sistem inteligent casa

## **1. Scop proiect**

Sistem inteligent pentru casă care monitorizează **siguranța și confortul ambiental**, detectând zgomot, gaz, mișcare, temperatură și umiditate, și reacționând prin actuatori corespunzători.

---

## **2. Senzori + scop**

| Senzor             | Funcție                                    |
| ------------------ | ------------------------------------------ |
| Microfon           | Detectează zgomot mare/neașteptat          |
| Senzor gaz         | Detectează concentrație periculoasă de gaz |
| Senzor mișcare     | Detectează mișcare în casă                 |
| Senzor temperatură | Monitorizează temperatura mediului         |
| Senzor umiditate   | Monitorizează umiditatea mediului          |

---

## **3. Blocuri analogice / prelucrare**

| Senzor         | Bloc analogic / prelucrare  | Funcție                                     |
| -------------- | --------------------------- | ------------------------------------------- |
| Microfon       | Amplificator + Filtru RC/AO | Amplifică și filtrează semnalul audio       |
| Senzor gaz     | Comparator                  | Detectează prag periculos, aprinde LED roșu |
| Senzor mișcare | Comparator                  | Detectează prag mișcare, aprinde LED roșu   |
| Temperatură    | Filtrare / AO               | Semnal stabil pentru Arduino                |
| Umiditate      | Filtrare / AO               | Semnal stabil pentru Arduino                |

---

## **4. Actuatori și afișare**

| Actuator / Afișare             | Funcție                                                        |
| ------------------------------ | -------------------------------------------------------------- |
| LED roșu (gaz)                 | Alertă imediată la depășirea pragului de gaz                   |
| LED roșu (mișcare)             | Alertă vizuală la detectarea mișcării                          |
| Servo motor                    | Închide teava de gaz în caz de pericol                         |
| Ventilator                     | Reglare temperatură / răcire conform senzorului de temperatură |
| Umidificator / Dezumidificator | Menținere umiditate optimă conform senzorului de umiditate     |
| Piezo buzzer                   | Alarmă sonoră dacă se detectează mișcare în casă               |
| LCD / Serial Monitor           | Afișează valorile senzorilor: temperatură, umiditate, zgomot   |

---
