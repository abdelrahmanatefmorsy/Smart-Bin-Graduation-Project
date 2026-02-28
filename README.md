# Smart Waste Management System

A professional monorepo for the Smart Waste Management System graduation project.

## Overview

This system integrates embedded firmware for smart bins, multiple AI models, a backend API, a web dashboard, a mobile application, a database schema, and full documentation and deployment configuration into a single, well-organised repository.

## Repository Structure

| Folder | Role in System Architecture |
|---|---|
| `docs/` | Central documentation hub — contains the SRS, diagrams, and presentations that define and communicate the full system design. |
| `hardware/` | Embedded layer — firmware running on each smart bin, including sensor drivers, camera integration, and PCB/schematic files. |
| `ai/` | Intelligence layer — trained models and inference code for material classification, crowd-density estimation, and surrounding-waste detection. |
| `backend/` | Service layer — REST/GraphQL API that connects all subsystems, handles business logic, and persists data to the database. |
| `dashboard/` | Operator interface — web-based UI for monitoring bin status, viewing analytics, and managing the system. |
| `mobile-app/` | Citizen interface — cross-platform mobile application for end-users to interact with the system. |
| `database/` | Data layer — SQL schema, migrations, and seed data that define the persistent data model. |
| `deployment/` | Infrastructure layer — Docker, Nginx, and environment configuration for consistent, reproducible deployments. |
| `.github/` | CI/CD and collaboration — automated workflows and issue templates that enforce quality gates on every contribution. |

## Getting Started

Refer to the README.md file inside each top-level folder for setup instructions specific to that component.