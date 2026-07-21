---
title: "Document Directory & Architectural Index"
version: "0.3"
domain: "System Architecture & Document Mapping"
---

# Document Inventory & Directory Index

This document serves as the central index for the **CXO-as-a-Service (Personal C-Suite)** framework. It details the purpose, lifecycle, location, and operational usage for every template, system file, and directory in your Personal C-Suite vault.

---

## 1. Core Orientation & Rules

### `README.md` (Repository & Vault Setup Guide)
* **Purpose:** High-level project entry point outlining repository setup, badges, and quick onboarding instructions.
* **Location:** Vault Root (`/README.md`)
* **Lifecycle:** Static reference. Refer to this when initializing a new vault instance or repository fork.

### `00-start-here.md` (Executive Orientation)
* **Purpose:** Soft landing onboarding guide defining the Chairman vs. Personal Executive partnership model and quick-start steps.
* **Location:** Vault Root (`/00-start-here.md`)
* **Lifecycle:** Static reference guide for onboarding or resuming operations.

### `01-foundational-requirements.md` (Rules of Engagement)
* **Purpose:** Master system instructions for your AI assistant. Defines the CXO persona, direct communication constraints, decision-support rules, the 3-Strike Deferral Rule, and C-Suite role mappings (CEO, CFO, COO, CHO, CTO).
* **Location:** Vault Root (`/01-foundational-requirements.md`)
* **Lifecycle:** Core system instructions. Upload or copy this file into your AI assistant's context as your master prompt.

### `02-document-inventory.md` (This Index)
* **Purpose:** Architectural overview explaining what every document in the vault is for, when to edit it, and how the AI interacts with it.
* **Location:** Vault Root (`/02-document-inventory.md`)
* **Lifecycle:** Static reference. Updated if new templates or system directories are added to the framework.

---

## 2. Core Operational Tracking & Diagnostics

### `03-onboarding-survey-stage-1.md` (Stage 1 Discovery Intake)
* **Purpose:** Initial intake survey filled out when first spinning up your CXO-as-a-Service system. Captures your current career vehicle, financial baseline, key projects, and holistic health metrics.
* **Location:** Vault Root (`/03-onboarding-survey-stage-1.md`)
* **Lifecycle:** One-time intake template. Used during setup to generate your custom C-Suite Role Mapping Matrix and initialize your `living-ledger.md`.

### `04-living-ledger-template.md` (Master Dashboard Template)
* **Purpose:** Template used to instantiate your permanent `living-ledger.md`. Tracks critical escalations (Section 0 Radar), active/pending projects, cash runway & financial operations, stakeholder CRMs, 1-to-3-year strategic horizons, and holistic capacity (Mind, Body, Spirit).
* **Location:** Vault Root (`/04-living-ledger-template.md`)
* **Lifecycle:** Template file. Copied to vault root as `living-ledger.md` and updated continuously by the AI during check-ins.

### `05-user-survey-template.md` (Diagnostic Survey Template)
* **Purpose:** Blueprint used by the AI to generate point-in-time diagnostic check-in surveys.
* **Location:** Vault Root (`/05-user-survey-template.md`)
* **Lifecycle:** Template file. Copied by the AI into `archives/user-surveys/` with dated filenames (`user-survey-YYYYMMDD.md`).

---

## 3. Operational Archives & Repositories

### `archives/user-surveys/` (Diagnostic Survey Repository)
* **Purpose:** Directory holding all dated diagnostic survey files (`user-survey-YYYYMMDD.md`). Allows you to respond to probing questions and keep a historical audit trail of your planning sessions.
* **Location:** Subfolder (`/archives/user-surveys/`)
* **Lifecycle:** Active archive. Unanswered questions automatically roll forward into the newest file so you only ever fill out a single active survey.

### `archives/feedback-logs/` (Speech-to-Text & Dictation Archive)
* **Purpose:** Permanent storage folder for raw voice or text updates (e.g. `YYYYMMDD-HHMM-update.md` submitted via Wispr Flow, speech-to-text, or quick notes).
* **Location:** Subfolder (`/archives/feedback-logs/`)
* **Lifecycle:** Move destination. Once the AI reads and reconciles raw update files into `living-ledger.md` and the active survey, it moves the raw file here to keep the vault root clean.

### `archives/misc/` (Reference & Prompt Sandbox)
* **Purpose:** Storage for experimental prompts, one-off test files, research notes, and non-operational reference materials.
* **Location:** Subfolder (`/archives/misc/`)
* **Lifecycle:** Passive storage. Keeps experimental or temporary files out of main tracking directories.

---

## Quick Reference Table: Which File Do I Use When?

| Goal | Target Document | Action |
| :--- | :--- | :--- |
| **Initial System Setup** | `README.md` & `00-start-here.md` | Follow 3-step setup guide and complete Stage 1 survey. |
| **Give Instructions to AI** | `01-foundational-requirements.md` | Upload/paste into AI context as system prompt. |
| **Complete Stage 1 Intake** | `03-onboarding-survey-stage-1.md` | Fill out open-ended discovery questions for AI. |
| **Check Project / Financial Status** | `living-ledger.md` | Open to view master dashboard, active tasks, and runway. |
| **Perform a Diagnostic Check-in** | `archives/user-surveys/user-survey-YYYYMMDD.md` | Fill out answers directly in the newest dated survey. |
| **Submit Quick Voice / Text Notes** | `YYYYMMDD-HHMM-update.md` in root | Drop raw dictation file into root; AI processes & moves to `archives/feedback-logs/`. |
