# GitHub Gist Documentation Uploader

This tool helps you upload Markdown documentation to a GitHub Gist and provides a URL for use with AI assistants like Cursor. It can handle both local directories and GitHub repository URLs.

## Features

- Upload Markdown files from local directories
- Fetch and upload Markdown files from GitHub repositories
- Update existing Gists or create new ones
- Secure GitHub token storage using .env file

## Prerequisites

- Python 3.6+
- GitHub account
- GitHub Personal Access Token with Gist permissions

## Installation

1. Clone this repository:
   ```
   git clone https://github.com/ranamzes/github-gist-docs-uploader-for-AI.git
   cd github-gist-docs-uploader-for-AI
   ```

## Usage

1. Run the Jupyter Notebook:
   ```
   jupyter notebook github_gist_docs_uploader.ipynb
   ```
	Or use extension for Jupyter

2. Follow the prompts in the notebook:
   - Enter your GitHub Personal Access Token (first time only)
   - Specify the source of your documentation (local path or GitHub URL)
   - Provide a name for your Gist

3. The tool will upload your documentation to a GitHub Gist and provide you with the Gist URL.

## Creating a GitHub Personal Access Token

1. Go to https://github.com/settings/tokens
2. Click 'Generate new token' (classic)
3. Give your token a descriptive name
4. Set the following permissions:
   - In the 'Repository permissions' section:
     * Contents: Read-only
     * Metadata: Read-only
   - In the 'Account permissions' section:
     * Gists: Read and write
5. Click 'Generate token' at the bottom of the page
6. Copy the created token and use it in the tool when prompted

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Thanks to the creators and maintainers of PyGithub, python-dotenv, and other dependencies.
- Inspired by the need for easy documentation sharing with AI assistants.

## Support

If you encounter any problems or have any questions, please open an issue in this repository.
