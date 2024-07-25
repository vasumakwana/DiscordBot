# Discord Bot Template

This is a template for creating a customizable Discord bot using Python and Pycord. It includes basic setup instructions and example code to get you started.

## Requirements

- **Python 3**
- **pip**
- **Pycord** (Python library for interacting with the Discord API)

### Optional but Recommended

- **python-dotenv** (for managing environment variables)

## Getting Started

Follow these steps to set up and run your Discord bot:

1. **Create a Bot:**

   - Visit the [Discord Developer Portal](https://discord.com/developers/applications).
   - Create a new application and navigate to the "Bot" section to add a bot to your application.
   - Under the "OAuth2" tab, select the permissions your bot needs and generate an invite link to add the bot to a server.

2. **Install Dependencies:**

   - Ensure Python 3 is installed on your system.
   - Install the required libraries using pip:
     ```bash
     pip install py-cord
     pip install python-dotenv
     ```

3. **Secure Your Token:**

   - For local development or if the code will not be uploaded to a public repository, you can place your bot token directly in your `main.py` file.
   - For better security, especially when uploading code to a repository, store your token in a `.env` file. Create a `.env` file in the root of your project directory with the following content:
     ```env
     TOKEN=your-bot-token-here
     ```
   - Ensure you add the `.env` file to your `.gitignore` to prevent it from being uploaded to GitHub.

4. ## Run Your Bot

   - To run your bot, execute the following command in your terminal:
	 ```bash
	 python main.py
	 ```
