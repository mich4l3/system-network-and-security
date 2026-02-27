Questo repository contiene il progetto d'esame relativo alla trasformazione dell'infrastruttura IT di BIGBANK.LOCAL secondo i paradigmi della Zero Trust Architecture (ZTA). Il lavoro si focalizza sulla transizione da un modello di sicurezza perimetrale tradizionale a una strategia "Never Trust, Always Verify".

Obiettivi del Progetto
L'obiettivo principale è mitigare i rischi di movimenti laterali e accessi non autorizzati all'interno di un dominio Active Directory complesso, garantendo al contempo la conformità con gli standard internazionali di cybersecurity.

AS-IS Analysis: Valutazione delle vulnerabilità correnti tramite tecniche di Network Scanning e Privilege Escalation.

Zero Trust Design: Implementazione di micro-segmentazione e controlli basati sull'identità.

Compliance: Allineamento con i framework ISO/IEC 27001:2022, ISO 27002 e la direttiva NIS2.

Stack Tecnologico e Metodologie
Network Analysis & Scanning: Nmap, Wireshark.

Identity Management: Active Directory Hardening, GPO (Group Policy Object) management.

Threat Modeling: Framework STRIDE per l'identificazione delle minacce architetturali.

Governance Frameworks: NIST Cybersecurity Framework (CSF), ISO 27001.

Architettura Proposta
La soluzione si basa sui pilastri fondamentali della Zero Trust:

Micro-segmentazione: Suddivisione della rete in zone a fiducia zero per limitare il raggio d'azione di una potenziale compromissione.

Explicit Verification: Ogni richiesta di accesso viene verificata in base all'identità dell'utente, al device e al contesto.

Least Privilege Access: Implementazione di policy restrittive per ridurre la superficie di attacco.

Compliance & Auditing
Il progetto include una mappatura dettagliata dei controlli tecnici rispetto ai requisiti normativi:

NIS2 (Articolo 21): Gestione dei rischi e obblighi di reporting.

ISO 27001: Implementazione dei controlli di sicurezza delle informazioni e gestione della documentazione (Clause 7.5).

Auditability: I controlli sono verificabili tecnicamente tramite test automatizzati (query SIEM, export GPO).
