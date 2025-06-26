# ChronicleCore API Tools

This repo contains everything needed to manage and extend the ChronicleCore RPG system using Supabase and GPT.

## Contents

- `openapi/` – JSON schema for integrating Supabase with GPT actions
- `postman/` – Collection for testing requests
- `supabase/` – (Optional) Database schema and rules tracking

## Usage

### For GPT
Import `openapi/chroniclecore_openapi_schema.json` via "Import from URL" in your custom GPT builder.

### For Testing
Open Postman and import the collection from `postman/chroniclecore_postman_collection.json`.
