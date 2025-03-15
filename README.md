# Linux Assistant - AI-Powered Linux Command Line Assistant

## Overview

Linux Assistant is an advanced AI-powered command-line tool designed to assist users in navigating and managing Linux systems more efficiently. By leveraging the Google Gemini API, this tool provides intelligent responses to user prompts, making it easier to execute commands, troubleshoot issues, and learn more about Linux.

The tool is built using Node.js and integrates with the Google Generative AI library to deliver a seamless and interactive experience. It is particularly useful for both beginners and advanced users who want to streamline their workflow and enhance their Linux expertise.

## Features

- **AI-Powered Responses**: Utilizes the Google Gemini API to generate intelligent and context-aware responses to user prompts.
- **Interactive CLI**: Provides an interactive command-line interface for easy input and output.
- **Customizable Prompts**: Users can input any Linux-related query or command, and the AI will provide a detailed response.
- **Figlet and Lolcat Integration**: Displays a stylized "Linux" banner using `figlet` and `lolcat` for a visually appealing start.
- **Continuous Interaction**: After each response, the tool prompts the user for another query, enabling a continuous feedback loop.

## Installation

To install Linux Assistant, follow these steps:

1. **Download the Debian Package**:
   Use `wget` to download the `.deb` package from the repository:
   ```bash
   wget https://github.com/linuxfanboy4/linuxassistant/blob/7eb1ab4f44040dd82fdd99b766327287bcd1fc13/linuxasistant.deb
   ```

2. **Install the Package**:
   Install the downloaded package using `apt`:
   ```bash
   sudo apt install ./linuxasistant.deb
   ```

3. **Verify Installation**:
   Once installed, you can run the tool by executing the appropriate command (e.g., `linuxassistant`).

## Usage

After installation, launch the Linux Assistant from your terminal. The tool will display a stylized "Linux" banner and prompt you to enter your query.

### Example Workflow

1. **Start the Tool**:
   ```bash
   linuxassistant
   ```

2. **Enter Your Prompt**:
   The tool will ask:
   ```
   Enter your prompt:
   ```
   You can input any Linux-related question or command, such as:
   - "How do I check disk usage?"
   - "What is the command to list all running processes?"
   - "Explain how to set up a cron job."

3. **Receive AI-Generated Response**:
   The tool will process your input using the Google Gemini API and display a detailed response in the terminal.

4. **Continue Interaction**:
   After receiving a response, the tool will prompt you for another query, allowing for continuous interaction.

## Dependencies

Linux Assistant relies on the following dependencies:
- **Node.js**: The runtime environment for executing the tool.
- **Google Generative AI Library**: Used to interact with the Google Gemini API.
- **Figlet and Lolcat**: For generating the stylized "Linux" banner.
- **Child Process Module**: For executing shell commands within the Node.js environment.
- 
## Contributing

Contributions to Linux Assistant are welcome! If you have suggestions, bug reports, or feature requests, please open an issue or submit a pull request on the [GitHub repository](https://github.com/linuxfanboy4/linuxassistant).

### Steps to Contribute:
1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Commit your changes with clear and descriptive messages.
4. Submit a pull request detailing the changes and their purpose.

## License

Linux Assistant is released under the MIT License. See the [LICENSE](https://github.com/linuxfanboy4/linuxassistant/blob/main/LICENSE) file for more details.

## Disclaimer

This tool is not officially affiliated with Google or the Gemini API. It is an independent project designed to assist Linux users. The accuracy of the AI-generated responses depends on the Google Gemini API and the quality of the input prompts.

## Support

For support or questions, please open an issue on the [GitHub repository](https://github.com/linuxfanboy4/linuxassistant) or contact the maintainer directly.
