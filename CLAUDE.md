# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Purpose

This repository manages the CAEN (Clasificarea Activităților din Economia Națională) code update process for two Romanian SRL companies owned by the same associates (Ene Alexandrina-Carmen and Ene Marian-Cristi). The goal is to migrate from CAEN Rev.2 to CAEN Rev.3 and restructure the business activity codes to match current and planned business operations.

## Companies

### Sonjaline SRL (`sonjaline/`)
- **Act Constitutiv**: updated March 2021, uses CAEN Rev.2
- **Current main activity**: 1330 – Finisarea materialelor textile (needs changing)
- **Capital**: 400 RON, 50/50 split
- **Administrators**: both associates, unlimited mandate, individual full powers
- Has a very large list of secondary CAEN codes (Rev.2) covering manufacturing, commerce, IT, construction, food, services, etc.

### Inner Shapes Institute SRL (`ISI/`)
- **Act Constitutiv**: July 2024, uses CAEN Rev.2
- **Current main activity**: 8559 – Alte forme de învățământ
- **Capital**: 100 RON, 50 parts each (profit split 50/50 despite text mentioning 70/30 for capital)
- **Administrators**: both associates, 49-year mandate, individual full powers
- Focused secondary codes: software (6201, 6202, 6203, 6209), web/portals (6311, 6312), consulting, health (8690), education support, commerce

## Target Activities (both companies need to invoice for)

1. Psychotherapy / mental health sessions
2. Software services, IT consulting, digital product creation, SaaS (B2B)
3. Web platform/portal creation and licensing to other companies
4. Personal development courses (including online, with invited facilitators)
5. Retreats (multi-day, with trainers/coaches)
6. Projective cards, card-based games, booklets (designed in-house, printed by third parties)
7. Clothing/scarves (own creation) - online and in stores
8. Paintings (own creation) - online and in stores
9. Online sales through own web portal, offered as platform to other companies

## Key Reference Documents

- ONRC CAEN page: https://www.onrc.ro/index.php/ro/caen
- CAEN Rev.3 full structure: https://www.onrc.ro/documente/anunturi/CAEN-Rev.3_structura-completa.pdf
- Local CAEN Rev.3 reference: `CAEN Rev. 3_Ro.docx`

## Work Progress

Overall progress tracked in `step1.md`.

### Sonjaline SRL — COMPLETED
Full analysis in `sonjaline/analiza_CAEN_Rev3_Sonjaline.md`:
- Proposed CAEN Rev.3 codes (principal: 6210, 14 secondary codes)
- Tax optimization analysis (micro regime 2025 vs 2026, 1% vs 3% implications)
- Required permits/licenses per activity (8693 is the only complex one)
- Template documents: AGA decision, updated Art. 5 Act Constitutiv
- Rev.2 → Rev.3 conversion table with official ONRC sources
- Pending decisions: activity principal confirmation, 8693 placement (Sonjaline vs ISI)

### Inner Shapes Institute SRL — TODO
- Needs full CAEN Rev.3 conversion and analysis
- Key question: should 8693 (psychotherapy) go here instead of Sonjaline?
- Already has 8559 (education) as main activity and 8690 (health) as secondary

## Important Context

- CAEN Rev.3 transition is mandatory via ONRC
- Changing the main activity (not just converting codes) requires: AGA decision + Act Constitutiv update + ONRC filing
- Online sales in Rev.3 are classified by product type, not by sales channel
- Activity 8693 (psychotherapy) may require special authorizations/forms of practice
- All output should be in Romanian with legal references and links to source legislation
- Work must be saved incrementally so other agents can continue
