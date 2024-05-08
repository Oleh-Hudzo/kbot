# kbot

kbot is a Telegram bot designed to provide a simple interaction with users. It responds to a specific command and introduces itself with its current version.

## Features

- Responds to user greetings and identifies its version.

## Bot Link

[kbot on Telegram](https://t.me/panflet_kbot)

## Installation

To run kbot locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/oleh-hudzo/kbot.git
   cd kbot
   ```

2. Build the executable using Go:

   ````bash
   go build -o kbot cmd/kbot/main.go
   ```bash

   ````

3. Run the bot:
   ```bash
   ./kbot start
   ```

`/start hello` - Initiates the bot which responds with:

```css
Hello! I am kbot v1.0.2!
```
