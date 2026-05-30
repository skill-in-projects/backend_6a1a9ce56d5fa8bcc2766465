# FoodRoute - Backend API

## Application Database

**Application DB Connection String:** `postgresql://db_appdb_6a1a9ce56d5fa8bcc2766465_user:N%40oeHTwDTfOZqGrm%23AmXEIGF6LmeeM%2Ab@ep-old-rice-akk9mqxm.c-3.us-west-2.aws.neon.tech:5432/AppDB_6a1a9ce56d5fa8bcc2766465?sslmode=require`

**Swagger API Tester URL:** /swagger

## Google APIs (Gemini, Maps, Speech-to-Text)

The backend can use a Google API key provided via the **GOOGLE_API_KEY** environment variable (set on Railway). Use it for Gemini LLM, Maps, and Speech-to-Text. Check **GET /api/google/status** and **GET /api/google/health** to verify the key is set and reachable.

## Recommended Tools

**Recommended SQL Editor tool (Free):** [pgAdmin](https://www.pgadmin.org/download/)

## Deployment

This backend is configured for Railway deployment using nixpacks.toml.
