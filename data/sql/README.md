# SQL Schema

## Overview

This directory contains the database schema used to support the CHO SDL Platform.

The schema was designed to organize synthetic clone data, biological metadata, process information, and SDL workflow outputs.

---

## Files

### create_cld_schema.sql

Defines the SQLite database structure used for:

- Clone metadata
- Productivity metrics
- Quality attributes
- Stability measurements
- Process information
- SDL workflow outputs

The schema provides a reproducible foundation for the synthetic CHO clone database used throughout the project.

---

## Purpose

The database layer enables:

- Structured data storage
- Reproducible analysis
- Feature generation
- Model training
- SDL workflow integration

This database serves as the data backbone of the CHO SDL Platform V1 prototype.