# RDX File to Link Bot

A Telegram bot that generates direct download and streaming links for Telegram files.

## Branding

- Bot name: **RDX File to Link Bot**
- Channel: **RDX MOVIE HD**
- Telegram: https://t.me/rdxmovie_hd
- Generated routes: `/watch/rdxbot-...` and `/rdxbot-...`

## Deployment

Configure the variables in `config_sample.env`, then deploy with Docker, Heroku, or a VPS. Keep all secrets in environment variables and never commit them to GitHub.

> The internal Python package remains named `KPS` to preserve imports and startup compatibility. This internal name is not shown to users.
