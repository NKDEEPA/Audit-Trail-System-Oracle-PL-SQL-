# Audit-Trail-System-Oracle-PL-SQL-
Overview

This project implements a generic audit trail system that captures all INSERT, UPDATE, and DELETE operations on application tables and stores the full change‑history in a centralized AUDIT_LOG table.

Highlights

Generic logging package AUDIT_PKG reused by lightweight row‑level triggers.

Stores old & new row values as JSON for flexible querying.

Autonomous transaction logging to avoid mutating table errors.

Utility view V_AUDIT_HISTORY to parse JSON for reports.

Self‑contained scripts—run them in order and you’re ready to demo.
