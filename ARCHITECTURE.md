# Nyay Setu - Architecture Guide

## Overview
Nyay Setu is a digitalization platform for the Indian Judiciary System. 
This document helps new contributors understand how the project is structured.

## Project Structure

nyay-setu-working/
├── frontend/          # React.js frontend application
├── backend/           # Node.js backend API
├── nlp-orchestrator/  # NLP and AI services
├── docs/              # Documentation files
├── assets/            # Images and static files
└── infra/             # Infrastructure and deployment scripts

## Three Main Services

### 1. Frontend (frontend/nyaysetu-frontend)
- Built with React.js
- User interface for citizens and lawyers
- Connects to backend via REST API

### 2. Backend (backend/)
- Built with Node.js and Spring Boot
- Handles all business logic
- REST API endpoints

### 3. NLP Orchestrator (nlp-orchestrator/)
- Handles AI and language processing
- Connects legal queries to relevant information

## Getting Started
For local setup, refer to LOCAL_RUN.md
For contribution guidelines, refer to CONTRIBUTING.md