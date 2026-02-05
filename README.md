# IPR Capability Stack
Modular Operational Architecture of the Identity Primary Record

EU-first · Audit-first · Fail-closed · Hash-only · No identity custody

## What this is
The IPR Capability Stack defines a modular operational architecture where an Identity Primary Record enables real-world actions only if specific capability modules are active and verifiable ex-ante.

This repository does not introduce a new authority.
It introduces a technical capability:
execution is allowed only when responsibility and traceability exist before the action.

## Core Principle
No capability active → no execution allowed.

## Architecture Overview
IPR Core
│
├── IPR-UNEBDO — Opposability & Evidence  
├── IPR-OPC — Operational Control (ex-ante)  
├── IPR-CYBERGLOBAL — Interoperability  
├── IPR-METAEXCHANGE — Verified exchange  
├── IPR-NEUROLOOP — Evolution & audit  
└── IPR-IOSPACE — Physical & robotic extension  

Each module activates specific operational capabilities.

## Operational Logic
Request → IPR verification → Module verification → PASS / FAIL → Execution or block → Evidence.

Fail-closed by design.

## EU Alignment
AI Act — human oversight ex-ante  
NIS2 — prevention before execution  
GDPR — minimization & hash-only  
eIDAS principles — traceability & opponibility  

## Status
Architecture defined and active in modular development across the Hermeticum ecosystem.

## Function
This repository acts as the architectural map of all IPR operational modules.
