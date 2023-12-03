# Go Chat Bot

This Go project implements a chat bot integrated with Slack, Wit.ai, and Wolfram Alpha. It allows users to ask questions, and the bot utilizes Wit.ai for natural language processing and Wolfram Alpha for answering queries.

## Table of Contents

- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Configuration](#configuration)
- [Usage](#usage)
  - [Query for Bot](#query-for-bot)
- [Contributing](#contributing)
- [License](#license)

## Prerequisites

Make sure you have the following tools installed:

- [Go](https://golang.org/dl/)
- [Slack Bot Token](https://api.slack.com/bot-users)
- [Slack App Token](https://api.slack.com/authentication/basics#bot_token)
- [Wit.ai Token](https://wit.ai/)

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/Mayejacob/go-chat-bot.git
    ```

2. Change to the project directory:

    ```bash
    cd go-chat-bot
    ```


## Configuration

Configure the project by creating a `.env` file in the project directory with the following variables:

```env
SLACK_BOT_TOKEN=your_slack_bot_token
SLACK_APP_TOKEN=your_slack_app_token
WIT_AI_TOKEN=your_wit_ai_token
WOLFRAM_APP_ID=your_wolfram_alpha_app_id
```

## Usage

### Query for Bot

- **Command**: `query for bot - <message>`
- **Description**: Send any question to Wolfram Alpha.
- **Examples**:
  - `query for bot - Who is the president of Nigeria?`
