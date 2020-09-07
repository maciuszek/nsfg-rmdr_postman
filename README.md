# NSFG-RMDR_LANGUAGES

NSFG-RMDR_POSTMAN is a customized implemenation of https://github.com/reminder-bot/postman-rs modified for https://github.com/maciuszek/nsfg-rmdr

## Setup

Build: `cargo build --release`

### Configuration

Environemnt variables:
VARIABLE | REQUIRED
------------- | -------------
DISCORD_TOKEN | Y
DATABASE_URL | Y
INTERVAL | Y

## Run

Run: `./target/release/main`
