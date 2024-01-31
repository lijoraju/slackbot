# Mini Slack Bot Age Calculator

This is a simple Slack bot written in Go that calculates the age based on the year of birth provided by the user. It utilizes the Slacker library for easy Slack bot development.

## Prerequisites
Before running the bot, ensure you have the following:
1. Go installed on your machine
2. A Slack workspace
3. Slack Bot Token and App Token for authentication
4. Set necessary bot scopes under OAuth & Permissions tab
5. Subscribe to bot events under Event Subscriptions

## Setup
1. Clone this repository to your local machine.
    ```
    git clone https://github.com/lijoraju/slackbot.git
    cd your-repository
    ```
2. Set the environment variables for your Slack Bot Token and App Token. Open the main.go file and replace the empty strings with your tokens.
   ```
   os.Setenv("SLACK_BOT_TOKEN", "your_slack_bot_token")
   os.Setenv("SLACK_APP_TOKEN", "your_slack_app_token")
   ```

3. Build and run the bot.
   ```
   go build
   go run main.go
   ```
   
## Usage
The bot responds to a command in the following format.
```
my yob is <year>
```
Example:
```
@age-bot my yob is 1994
```

### Notes
- Ensure that the Slack Bot Token and App Token are valid and have the necessary permissions.
- Customize the code as needed for your specific use case or add additional functionality.

