# chatwoot-dev

## Copy .env

```sh
cp .env.example .env
```

## prepare db

```bash
docker compose run --rm rails bundle exec rails db:chatwoot_prepare
```

## Chatwoot Run

```bash
docker compose up -d
```

## Chatwoot is Running on

- http://0.0.0.0:3000/

## First Setup and Add Test website Inbox
- create index.html and website inbox configuration to test inbox
- open in browser
