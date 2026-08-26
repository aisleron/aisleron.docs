---
title: Self-managing
parent: Aisleron Sync Service
nav_order: 300
---

# Self-managing the Aisleron Sync Service

You can run your own instance of the Aisleron Sync Service either on your own hardware or by signing up for a free Supabase cloud instance. Follow the instructions below to set up your instance.


Note that, while every effort will be made to prevent braking changes, backwards compatibility cannot be guaranteed, so it is recommended to always keep your instance updated with the latest available schema.

## Prerequisites

Install the [Supabase CLI](https://supabase.com/docs/guides/cli/getting-started#installing-the-supabase-cli):

- **macOS / Linux:** `brew install supabase/tap/supabase`
- **Windows:** `scoop bucket add supabase [https://github.com/supabase/scoop-bucket.git](https://github.com/supabase/scoop-bucket.git)` then `scoop install supabase`
- **npm:** `npm install -g supabase`

## Common Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/aisleron/aisleron.backend.git
   ```

2. Navigate into the project directory:
   ```bash
   cd aisleron.backend
   ```

## Option 1: Self-Hosted Instance

For self-hosting, the recommended approach is to use Docker. Refer to Supabase's instructions for [self-hosting with Docker](https://supabase.com/docs/guides/self-hosting/docker).

Use your PostgreSQL connection string to apply migrations directly to your self-hosted instance.

1. Push the schema directly to your database URL:
   ```bash
   supabase db push --db-url "postgresql://postgres:<PASSWORD>@<HOST>:<PORT>/postgres"
   ```

For details on retrieving connection credentials, see the [Supabase Direct Connections Documentation](https://supabase.com/docs/guides/database/connecting-to-postgres#direct-connections).


## Option 2: Supabase Cloud

To use Supabase cloud for the backend, sign up for a project at https://supabase.com/.

See [Pushing to a remote project](https://supabase.com/docs/guides/local-development/cli-workflows#pushing-to-a-remote-project) for full instructions on how to connect and push database changes to the cloud instance.

1. Authenticate the CLI:
   ```bash
   supabase login
   ```

2. Link your local directory to your remote project:
   ```bash
   supabase link --project-ref <YOUR_PROJECT_REF>
   ```
   *(Find your Reference ID in [Project Settings > General](https://supabase.com/dashboard/project/_/settings/general))*

3. Push the schema:
   ```bash
   supabase db push
   ```

For more details on CLI migrations, check the [Supabase Database Migrations Documentation](https://supabase.com/docs/guides/cli/local-development#deploy-a-migration).

## Adding a User Account

To add a user to your Supabase instance, use the [Supabase project dashboard](https://supabase.com/docs/guides/auth/users#using-the-dashboard).