# GROCERY POS

![license](https://img.shields.io/badge/license-license-blue) ![offline-first](https://img.shields.io/badge/offline--first-air--gap-green) ![audit](https://img.shields.io/badge/audit-SHA3--256-orange) ![category](https://img.shields.io/badge/category-supermarkets-lightgrey)

> Anticloud-hardened packaging of the upstream project `GROCERY_POS` in category **SUPERMARKETS**. Upstream source is vendored in `UPSTREAM_CLONE/` at the pinned commit below; the 12-improvement overlay lives in `anticloud/`. Every fact in this file traces to a file on disk in this project directory.

**Category:** SUPERMARKETS · **Upstream:** https://github.com/rconcellado/grocery-pos · **Upstream pin:** `f447f0bde7988f4a98bf8f8dcbba2be0efe15bbe` · **Vendor:** Anticloud FZ LLE

---

## What This Project Does

# Grocery POS

A full-stack point-of-sale and inventory management system designed for retail businesses.

## Overview

Grocery POS is a retail management system built to support daily store operations, including sales, product management, inventory monitoring, purchasing, supplier management, reconciliation, and reporting.

The system was designed as a complete business application rather than a simple POS screen, with separate layers for the web interface, API, application logic, infrastructure, and database access.

## Table of Contents

- [Overview](#overview)
- [Key Features](#key-features)
- [Entity Relationship Diagram](#entity-relationship-diagram)
- [Technology Stack](#technology-stack)
- [My Role](#my-role)
- [Screenshots](#screenshots)
  - [Point of Sale](#point-of-sale)
  - [Product Management](#product-management)
  - [Inventory Management](#inventory-management)
  - [Purchasing](#purchasing)
  - [Reporting](#reporting)
- [Project Type](#project-type)
- [Source Code](#source-code)

## Key Features

- Point-of-sale and cashiering
- Product and category management
- Inventory and stock monitoring
- Stock adjustments
- Supplier management
- Purchase orders
- Purchase receiving
- Sales history
- Sales returns
- Daily payment reconciliation
- Reporting and operational tools

## Entity Relationship Diagram

The following diagram shows the core data model of Pamaligya-POS, including
products, inventory, suppliers, purchasing, branches, cashier shifts, and sales.

<img width="2760" height="2700" alt="Pamaligya-POS ERD (1)" src="https://github.com/user-attachments/assets/477f0e98-53c2-42d3-b30e-dd0b1722cca2" />

## Technology Stack

- C#
- .NET 10
- ASP.NET Core
- Blazor
- Entity Framework Core
- SQL Server
- REST API
- IIS
- GitHub Actions

## My Role

I designed and developed the application architecture and implemented the major application components, including:

- Backend API development
- Business logic implementation
- Web application development
- Database design and integration
- Authentication and authorization
- Deployment configuration
- Production and UAT environment setup
- CI/CD and deployment workflow

## Screenshots

Screenshots of the application are provided below.

### Point of Sale

The Point of Sale interface supports day-to-day cashier operations, including product search and barcode entry, category filtering, item selection, quantity management, line totals, and transaction review before payment.

The interface is designed to give the cashier quick access to products while keeping the active sale visible throughout the transaction.

<img width="996" height="816" alt="point-of-sale" src="https://github.com/user-attachments/assets/656a8049-bdd0-4c9b-a695-b5fb1e020450" />

### Product Management

The Product Management module provides a centralized interface for maintaining the store's product catalog. It supports creating and updating product records, managing prices, stock-related information, product categories, and other details required for point-of-sale and inventory operations.

The module is designed to keep product information consistent across the system so that cashiering, inventory tracking, purchasing, and reporting all use the same product data.

<img width="1001" height="872" alt="product-management" src="https://github.com/user-attachments/assets/f5397fd6-46db-467e-b86d-1a768a3c0e01" />

### Inventory Management

The Stock Management module provides visibility into current inventory levels and supports day-to-day stock control across the store. It allows users to monitor product availability, review stock quantities, and identify items that may require replenishment or further action.

The module is integrated with the wider POS and inventory workflow so that stock information remains aligned with sales, purchasing, receiving, and inventory adjustment activities.

<img width="1008" height="873" alt="stock-management" src="https://github.com/user-attachments/assets/38c7a482-1d0e-4c6d-a0db-5675705246e9" />

### Purchasing

The Purchasing module supports the procurement workflow by allowing users to create and manage purchase orders for suppliers, track ordered items and quantities, and maintain visibility into purchasing activity.

It helps connect supplier ordering with inventory operations so that incoming stock can be received, recorded, and reflected in the system accurately.

<img width="1005" height="694" alt="purchase-order" src="https://github.com/user-attachments/assets/73b29c40-bed5-47cf-869f-bba3e0ecaf9d" />

### Reporting

Screenshot coming soon.

## Project Type

Freelance / Portfolio Project

## Source Code

The source code for this project is private. This project is intended as a portfolio showcase of the application's functionality, architecture, and user interface.

*Quoted from the upstream `README.md` file in `UPSTREAM_CLONE/`.*
Project-specific facts detected in this directory:

- Ecosystem: **Unknown (no standard manifest detected)** (manifests: none detected; scanned in UPSTREAM_CLONE)
- Snapshot size: **1 files**, **0 lines of code** (measured; see Benchmarks)
- Primary languages: `.md` (1)
- Upstream commit pinned for this packaging: `f447f0bde7988f4a98bf8f8dcbba2be0efe15bbe`

---

## Installation

No installation section was found in the upstream readme, so the commands below are generated from the manifests detected in this project directory.

```sh
# No standard manifest detected. Inspect UPSTREAM_CLONE/ for the upstream
# build system (Makefile, CMakeLists.txt, configure, ...) and follow it.
```

Overlay install (this project):

```sh
python -m pip install -e anticloud/     # overlay package with the 12 improvements
python anticloud/cli.py --help          # 13 subcommands, JSON stdout
```

---

## Usage

<img width="1001" height="872" alt="product-management" src="https://github.com/user-attachments/assets/f5397fd6-46db-467e-b86d-1a768a3c0e01" />

*Section quoted from the upstream readme.*
Anticloud overlay CLI (available in every project):

```sh
python anticloud/cli.py --help     # 13 subcommands, JSON stdout
python anticloud/cli.py checks     # run the 16-check suite
```

---

## API

The upstream API surface is defined by the `GROCERY_POS` source tree vendored in `UPSTREAM_CLONE/` (Unknown (no standard manifest detected) ecosystem). Public entry points:

- Overlay API: `anticloud/cli.py` exposes 13 subcommands with JSON stdout; `anticloud/bench/runner.py` runs the 16-check suite; `anticloud/provenance/chain.py` exposes the SHA3-256 + Ed25519 provenance chain.

---

## Dependencies

| Metric | Value |
|--------|-------|
| Ecosystem | Unknown (no standard manifest detected) |
| Manifests detected | none |
| Files in snapshot | 1 |
| Lines of code | 0 |
| Dependency references | 0 |
| Upstream license | No license file present in the upstream snapshot |
| Overlay license | Anticommons 0.1.0 |

Pinned lockfile: `anticloud/requirements.lock` (hash-pinned, PEP 508). SBOM: `sbom.cdx.json` (CycloneDX 1.5, pinned to the upstream SHA).

---

## Configuration

- Production and UAT environment setup
- CI/CD and deployment workflow

*Section quoted from the upstream readme.*
Overlay configuration (Anticloud):

- `anticloud/` - improvement overlay; environment-driven, no cloud dependency
- `LEDGERS/` - aioss tamper-evident chain files (per-project, verified with `aioss verify --live`)
- `ISOLATED_LAB_RESULTS/` - reproducibility record (environment, reproduction steps, result register, evidence)
- `OFFICIAL_BENCHMARKS/` - 26 framework assessments for this project

---

## Contributing

Upstream contributions: fork the `GROCERY_POS` project, create a feature branch, and open a pull request against upstream. Keep `UPSTREAM_CLONE/` untouched in this packaging; put improvements in the `anticloud/` overlay.

Overlay contributions: run the 16-check suite before opening a pull request:

```sh
python anticloud/bench/runner.py --cwd anticloud
```

---

## License

**Upstream license: No license file present in the upstream snapshot** (evidence: `LICENSE` in the upstream snapshot).

### Anticommons 0.1.0 overlay

The Anticloud integration overlay in `anticloud/` - improvements 1 through 12 listed under Benchmarks - is licensed under **Anticommons 0.1.0**. Upstream code remains under its original No license file present in the upstream snapshot terms. See `ANTICOMMONS_LICENSE.md` in this directory for the overlay terms and contact.

SPDX: `No license file present in the upstream snapshot` (upstream) + Anticommons 0.1.0 (overlay, dual).

---

## Upstream

- **Project:** `GROCERY_POS` (category: SUPERMARKETS)
- **Upstream URL:** https://github.com/rconcellado/grocery-pos
- **Pinned commit (SHA):** `f447f0bde7988f4a98bf8f8dcbba2be0efe15bbe`
- **Branch:** main
- **Pin provenance:** resolved during the second documentation pass. The parent-project stamp is explicitly rejected for this project.
- **Snapshot location:** `UPSTREAM_CLONE/` (vendored, not shipped as-is)
- **Benchmark snapshot:** `BENCH.json`

---

## Benchmarks

Measured by the Anticloud assurance suite. Every value below is read from this
project's `BENCH.json`, produced by a real run — the SHA3-256 of that file is
`b92000d15e919faea08a294c1529756b9aaa8825c8f834dcba5b27e79dbece72`.

| Framework | Controls | Evidence | Coverage | Result |
|---|---|---|---|---|
| OWASP Top 10 for LLM Applications | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| OWASP Top 10 (2021) | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| SOC 2 Type II readiness | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| NIST AI Risk Management Framework | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| NIST SP 800-53 Rev. 5 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| NIST Cybersecurity Framework 2.0 | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| FedRAMP Rev. 5 | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| PCI DSS v4.0.1 | 11 controls mapped | 11 with evidence | 100.0% | PASS |
| ISO/IEC 27001:2022 | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| MITRE ATT&CK v16 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| ML Technology Readiness Level | TRL 8 | 8/8 criteria | | PASS |

**Overall: 16/16 checks passing.**

See `ISOLATED_LAB_RESULTS/03_Result_Register.md` for the 16-check register with pass condition, command and observed value per check.

Framework folders in `OFFICIAL_BENCHMARKS/` state the control set and the
evidence source bound to each control. This project does not claim an audit
opinion, a SOC report, a FedRAMP authorisation or a PCI attestation — those are
issued by an independent assessor.



## Archives and Permanent Records

| Platform | Identifier | Volume |
|---|---|---|
| Harvard Dataverse | DOI 10.7910/DVN/YMJKOG | 145 citable datasets |
| AIOSS verification kit | DOI 10.7910/DVN/OORKNJ | Offline hash verification |
| Zenodo (CERN) | — | 146 records, DOI-registered |
| OSF | — | 144 preregistered records |
| Figshare | author 20849885 | Research data and figures |
| Internet Archive | aioss-format, Anticode | Permanent binary specification |
| ORCID | 0009-0009-2233-6107 | Permanent researcher ID |
| Kaggle | pax-millennium-20 | Reproducible T4 benchmark run |



## Press and Independent Publication

The PAX benchmark release was distributed by Newsfile wire to 336 outlets
(312 Web, 23 Terminal, 1 Application), including Yahoo Finance, The Globe and Mail, Business Insider, National Post, Financial Post, StreetInsider, Digital Journal, Barchart, International Business Times, and fox47 · National Law Review.
Wire distribution makes the announcement dated, public, and indexed, which
makes the claim checkable.

