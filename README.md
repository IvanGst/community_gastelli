# Community Recensione Stadi

Progetto PHP avviabile localmente con Docker Compose, con MySQL e phpMyAdmin.

## Avvio

1. Copia `.env.example` in `.env`.
2. Sostituisci le password di esempio in `.env` con password sicure.
3. Avvia i servizi:

   ```sh
   docker compose up --build
   ```

Il sito sara' disponibile su `http://localhost:8081` e phpMyAdmin su
`http://localhost:8083`. Se queste porte sono gia' occupate, modifica
`WEB_PORT` e `PHPMYADMIN_PORT` nel file `.env`.

Il file `.env` contiene configurazioni locali e non va condiviso o caricato
su GitHub.
