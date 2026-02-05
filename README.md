# IPR Capability Stack
Architettura Operativa Modulare dell’Identity Primary Record

UE-first · Audit-first · Fail-closed · Hash-only · Nessuna custodia identitaria

## Cos’è
L’IPR Capability Stack definisce un’architettura operativa modulare in cui un Identity Primary Record abilita azioni digitali e fisiche solo se i moduli di capacità richiesti risultano attivi e verificabili ex-ante.

Questo repository non introduce una nuova autorità.
Introduce una capacità tecnica:
l’esecuzione è ammessa solo quando responsabilità e tracciabilità esistono prima dell’azione.

## Principio fondamentale
Nessun modulo attivo → nessuna esecuzione ammessa.

## Panoramica architettura
IPR Core
│
├── IPR-UNEBDO — Opponibilità e prova  
├── IPR-OPC — Controllo operativo ex-ante  
├── IPR-CYBERGLOBAL — Interoperabilità  
├── IPR-METAEXCHANGE — Scambi verificabili  
├── IPR-NEUROLOOP — Evoluzione e audit  
└── IPR-IOSPACE — Estensione fisica e robotica  

Ogni modulo attiva specifiche capacità operative.

## Logica operativa
Richiesta azione → verifica IPR → verifica moduli attivi → PASS / FAIL → esecuzione o blocco → evidenza.

Il sistema opera in modalità fail-closed.

## Allineamento europeo
AI Act — supervisione umana ex-ante  
NIS2 — prevenzione prima dell’esecuzione  
GDPR — minimizzazione dati e hash-only  
Principi eIDAS — tracciabilità e opponibilità nel tempo  

## Stato
Architettura definita e in attivazione modulare nell’ecosistema Hermeticum.

## Funzione del repository
Questo repository rappresenta la mappa architetturale ufficiale dei moduli operativi IPR e delle loro capacità.
