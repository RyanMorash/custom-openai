# Azure OpenAI Conversation

This is a custom Home Assistant integration based on the OpenAI Conversation core integration. It adds the ability to specify a custom API URL and enables you to us Azure AI.

## Features

- All the functionality of the original OpenAI Conversation integration
- Ability to set a custom API URL endpoint

## Installation

### HACS (Recommended)

1. Make sure [HACS](https://hacs.xyz/) is installed in your Home Assistant instance
2. Go to HACS > Integrations
3. Click the three dots in the top right corner and select "Custom repositories"
4. Add the URL of this repository and select "Integration" as the category
5. Click "Add"
6. Find "Azure OpenAI Conversation" in the list and click "Download"
7. Restart Home Assistant

### Manual Installation

1. Download the latest release from the repository
2. Copy the `azure_openai` folder to your `config/custom_components` directory
3. Restart Home Assistant

## Configuration

After installation, go to Settings > Devices & Services > Add Integration, and search for "Azure OpenAI Conversation".

Configuration options:

- **Name**: A name for this conversation agent
- **API Key**: Your Azure API key
- **Custom API URL**: The URL endpoint for your API (e.g., Azure AI endpoint)
- **Model**: The AI model to use (e.g., gpt-4, gpt-3.5-turbo)
- Additional options match the core OpenAI integration

## Usage

Once configured, you can use this integration exactly like the built-in OpenAI Conversation integration. The conversation agent will appear in your list of available assistants. For more info, see the [Home Assistant documentation](https://www.home-assistant.io/integrations/openai_conversation/)

## License

This project is licensed under the Apache License 2.0 - see the LICENSE file for details.
