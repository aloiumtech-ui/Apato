# Apato
Apato | Protocollo P2P per la compravendita immobiliare automatizzata tra privati. Include moduli per l'audit catastale, legal contract automation e deposito di garanzia (escrow system) centralizzato.


> **Protocollo open-source P2P per la disintermediazione immobiliare automatizzata tra privati.** 
Elimina i costi artificiali e l'opacità dei mediatori tradizionali (0% commissioni percentuali), sostituendoli con un'infrastruttura software centralizzata e protetta.

---

## 🏗️ Core Features & Protocol Architecture

Il sistema automatizza i tre pilastri della compravendita immobiliare tradizionalmente gestiti dalle agenzie:

*   **Scudo Tecnico & Audit Catastale (Vision AI Pre-screening):** Integrazione diretta con i database dell'Agenzia delle Entrate per il recupero istantaneo di planimetrie e visure. Un motore OCR/Vision AI effettua un pre-screening per rilevare difformità urbanistiche macroscopiche prima della validazione della Relazione Tecnica Integrata (RRE).
*   **Legal Contract Automation (Legal Engine):** Compilazione algoritmica e generazione guidata di Proposte d'Acquisto e Contratti Preliminari conformi al Codice Civile italiano. Integrazione nativa con Firma Elettronica Avanzata (FEA) a norma di legge.
*   **Escrow Infrastructure (Deposito Garanzia Segregato):** Gestione sicura delle caparre confirmatorie tramite conti di deposito a garanzia (*Escrow Account*). I fondi degli acquirenti rimangono bloccati in un ambiente finanziario protetto e vengono rilasciati al venditore esclusivamente al momento esatto del rogito notarile, azzerando i rischi di insolvenza o truffe.
*   **Trust Selection Filter:** Accesso alle visite e alle trattative vincolato alla verifica preventiva della capienza finanziaria del compratore (caricamento di pre-delibere bancarie o attestazioni di liquidità).

---

## 💻 Repository Structure & Tech Stack

Questa repository ospita l'asset front-end pubblico utilizzato per la landing page ufficiale e la pipeline di onboarding (smoke test) per il lancio della Beta Privata nell'area metropolitana di Milano.

*   **Front-end:** HTML5 semantico + Tailwind CSS (v4)
*   **Hosting & Deployment:** GitHub Pages
*   **Lead Generation / Data Pipeline:** Webhook asincrono tramite Formspree per la raccolta protetta dei dati delle candidature (senza esposizione di backend o DB in questa fase pubblica).

---

## 🔒 Security & Privacy Disclaimer

Questa è una repository **pubblica** dedicata esclusivamente agli asset statici di marketing e acquisizione lead. Nessuna logica di backend proprietaria, chiave API privata (OpenAI, Stripe, etc.) o credenziale di database è esposta in questo modulo. L'infrastruttura core dell'applicazione risiede in un ambiente separato e protetto.
