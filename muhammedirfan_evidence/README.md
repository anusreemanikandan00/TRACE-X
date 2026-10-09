# TRACE-X — Member 1: Evidence Data Processing

## Overview

This module prepares and organizes synthetic digital evidence for the TRACE-X AI-powered cyberattack reconstruction platform.

## Objectives

* Process evidence from multiple sources.
* Normalize evidence into a common event format.
* Generate SHA-256 hashes for evidence integrity verification.
* Create an evidence manifest and scenario summary.
* Provide structured evidence for Member 3's attack reconstruction module.

## Input Files

* `users.csv`
* `devices.csv`
* `emails.csv`
* `login_logs.csv`
* `network_logs.csv`
* `file_access.csv`
* `url_data.csv`

## Main Outputs

* `normalized_events.csv` — unified event records for timeline reconstruction.
* `evidence_integrity.csv` — evidence integrity information.
* `evidence_manifest.csv` — inventory of processed evidence.
* `scenario_summary.csv` — summary of the synthetic demo scenarios.

## How to Run

1. Open `TRACEX_Member1_Evidence_Data_Processing_V2.ipynb` in Google Colab or Jupyter Notebook.
2. Upload or provide the required input CSV files.
3. Run the notebook cells in order.
4. Check that all four output CSV files are generated.

## Integration

The main output, `normalized_events.csv`, is passed to Member 3 for evidence correlation, timeline generation, and attack-story reconstruction.

## Data Note

The included demo data should be synthetic and used for testing. Predictions and reconstructed attack stories should be treated as evidence-based assessments, not definitive proof of an attack.
