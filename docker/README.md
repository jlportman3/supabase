# Supabase Docker

This is a minimal Docker Compose setup for self-hosting Supabase. Follow the steps [here](https://supabase.com/docs/guides/hosting/docker) to get started.

For an even lighter stack you can use `docker-compose.minimal.yml` which only includes the core services (database, API gateway, authentication and REST API). Run it with:

```sh
docker compose -f docker-compose.minimal.yml up
```

Uncomment the optional services in the file if you need realtime or storage support.
