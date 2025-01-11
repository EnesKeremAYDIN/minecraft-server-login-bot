# Minecraft Server Login Bot

A Node.js bot that automates logging into a Minecraft server. This tool can be configured to handle multiple accounts and perform repeated logins.

## Features

- Automates login to specified Minecraft servers.
- Supports multiple account configurations.
- Simple setup and deployment, compatible with Heroku.

## Installation and Setup

### Prerequisites

- **Node.js** installed on your machine.
- Valid **Minecraft account credentials**.

### Installation

1. **Clone or Download** this repository:
   ```bash
   git clone https://github.com/EnesKeremAYDIN/minecraft-server-login-bot.git
   cd minecraft-server-login-bot
   ```

2. **Install Dependencies**:
   ```bash
   npm install
   ```

### Configuration

1. **Set Up Account and Server Details**:
   - Open `config.json` and enter your Minecraft login details and server IP.
   - Adjust other settings as needed for specific server requirements.

2. **Optional - Configure Multiple Accounts**:
   - Modify `launcher_accounts.json` if you plan to automate logins for multiple accounts.

### Running the Bot

Start the bot locally:
```bash
node bot.js
```

### Deploying to Heroku

1. Make sure you have a Heroku account and the [Heroku CLI](https://devcenter.heroku.com/articles/heroku-cli) installed.
2. Run these commands to set up and deploy:
   ```bash
   heroku create
   git push heroku main
   ```

## Files

- **`bot.js`**: Main script to automate Minecraft server logins.
- **`config.json`**: Configuration file for account and server settings.
- **`launcher_accounts.json`**: Optional file for managing multiple accounts.
- **`Procfile`**: Used for deployment to Heroku.
- **`package.json`**: Lists dependencies and metadata for the Node.js project.

## Disclaimer

This tool is intended for personal use. Ensure compliance with the Minecraft server’s rules and policies when using automated login systems.
