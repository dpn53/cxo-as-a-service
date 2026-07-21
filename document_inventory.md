# Document Inventory & Directory

This document serves as the central index for the **CXO-as-a-Service (Personal C-Suite)** framework. It details the purpose, lifecycle, location, and operational usage for every template, system file, and directory in your Personal C-Suite vault.

---

## 1. System Orientation & Rules

### `README.md` (Setup & Onboarding Guide)
* **Purpose:** Quick-start guide outlining vault initialization, system priming prompts, and the multi-stage onboarding workflow.
* **Location:** Vault Root (`/README.md`)
* **Lifecycle:** Static reference. Refer to this when setting up a new vault or re-orienting an AI model.

### `document_inventory.md` (This Index)
* **Purpose:** Architectural overview explaining what every document in the vault is for, when to edit it, and how the AI interacts with it.
* **Location:** Vault Root (`/document_inventory.md`)
* **Lifecycle:** Static reference. Updated if new templates or system directories are added to the framework.

### `foundational_requirements.md` (Rules of Engagement)
* **Purpose:** Master system instructions for your AI assistant. Defines the CXO persona, direct communication rules, decision-support logic, the 3-Strike Deferral Rule, and C-Suite role mappings (CEO, CFO, COO, CHO, CTO).
* **Location:** Vault Root (`/foundational_requirements.md`)
* **Lifecycle:** Core instructions. Upload or copy this file into your AI assistant's context at the start of sessions or project spaces.

---

## 2. Core Operational Tracking

### `living_ledger.md` (Single Source of Truth)
* **Purpose:** The central dashboard for your entire life and career. Tracks critical escalations (Section 0 Radar), active/pending projects, cash runway & financial operations, stakeholder CRMs, 1-to-3-year strategic horizons, and holistic capacity (Mind, Body, Spirit).
* **Source Template:** `living_ledger_template.md` (renamed to `living_ledger.md` during setup).
* **Location:** Vault Root (`/living_ledger.md`)
* **Lifecycle:** Active document updated continuously by the AI during check-ins and survey reconciliations.

---

## 3. Onboarding & Diagnostic Surveys

### `onboarding_survey_stage1.md` (Stage 1 Discovery Intake)
* **Purpose:** The initial intake survey filled out when first spinning up your CXO-as-a-Service system. Captures your current career vehicle, financial baseline, key projects, and holistic health metrics.
* **Location:** Vault Root (`/onboarding_survey_stage1.md`)
* **Lifecycle:** One-time template. Used during initial setup to generate your custom C-Suite Role Mapping Matrix and initialize `living_ledger.md`.

### `user_survey_template.md` (Diagnostic Survey Template)
* **Purpose:** Blueprint used by the AI to generate point-in-time diagnostic check-in surveys.
* **Location:** Vault Root (`/user_survey_template.md`)
* **Lifecycle:** Template file. Copied by the AI into `user_survey_archive/` with dated filenames (`user_survey_YYYYMMDD.md`).

---

## 4. Operational Directories & Archives

### `user_survey_archive/` (Diagnostic Survey Repository)
* **Purpose:** Directory holding all dated diagnostic survey files (`user_survey_YYYYMMDD.md`). Allows you to respond to probing questions and keep a historical audit trail of your planning sessions.
* **Location:** Subfolder (`/user_survey_archive/`)
* **Lifecycle:** Active archive. Unanswered questions automatically roll forward into the newest file so you only ever fill out a single active survey.

### `feedback_archive/` (Speech-to-Text & Dictation Archive)
* **Purpose:** Permanent storage folder for raw voice or text updates (e.g. `YYYYMMDD_HHMM Update.md` submitted via Wispr Flow, speech-to-text, or quick notes).
* **Location:** Subfolder (`/feedback_archive/`)
* **Lifecycle:** Move destination. Once the AI reads and reconciles raw update files into `living_ledger.md` and the active survey, it moves the raw file here to keep the vault root clean.

### `misc_archive/` (Reference & Prompt Sandbox)
* **Purpose:** Storage for experimental prompts, one-off test files, research notes, and non-operational reference materials.
* **Location:** Subfolder (`/misc_archive/`)
* **Lifecycle:** Passive storage. Keeps experimental or temporary files out of the main tracking directories.

---

## Quick Reference Workflow: Which File Do I Use When?

| Goal | Target Document | Action |
| :--- | :--- | :--- |
| **Initial System Setup** | `README.md` & `onboarding_survey_stage1.md` | Follow 3-step setup guide and complete Stage 1 survey. |
| **Give Instructions to AI** | `foundational_requirements.md` | Upload/paste into AI context as system prompt. |
| **Check Project / Financial Status** | `living_ledger.md` | Open to view master dashboard, active tasks, and runway. |
| **Perform a Diagnostic Check-in** | `user_survey_archive/user_survey_YYYYMMDD.md` | Fill out answers directly in the newest dated survey. |
| **Submit Quick Voice / Text Notes** | `YYYYMMDD_HHMM Update.md` in root | Drop raw dictation file into root; AI processes & moves to `feedback_archive/`. |
