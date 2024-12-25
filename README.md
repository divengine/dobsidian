# Dobsidian

Dobsidian is an open-source tool designed to generate entire interactive documentation as Obsidian vaults. It automates the creation of interconnected notes from your codebase, providing a visual map of relationships between classes, methods, and more.

## Features

- Generate a fully-structured Obsidian vault directly from your code.
- Automatically install required plugins and themes for seamless usage.
- Create interactive visualizations of connections between code elements.
- Support for multiple programming languages and platforms.

## Installation

### Prerequisites

- [Obsidian](https://obsidian.md/) installed on your system.
- Language-specific tools (e.g., .NET SDK for C#, Python environment, etc.).

### Steps

1. Clone this repository:

<pre><code>
git clone https://github.com/divengine/dobsidian.git
cd dobsidian
</code></pre>

2. Build and run the tool:

<pre><code>
dotnet build
dotnet run -- --help
</code></pre>

For other languages, refer to the documentation in their respective folders.

## Usage

Run the tool with your project directory as input:

<pre><code>
./dobsidian --source /path/to/your/code --output /path/to/vault
</code></pre>

Options:

- `--source`: Path to your source code directory.
- `--output`: Path to the output directory where the Obsidian vault will be created.
- `--config`: (Optional) Path to a configuration file for customization.

For language-specific usage, refer to the documentation in the respective folder.

## License

This project is licensed under the GNU General Public License v3.0. See the [LICENSE](./LICENSE) file for details.

## Status

Dobsidian is currently in its early stages and may be subject to significant changes. Feedback and contributions are welcome!

## Contributing

Contributions are welcome! Please fork the repository, make your changes, and submit a pull request. For more details, see the [CONTRIBUTING.md](./CONTRIBUTING.md) file.

## Acknowledgments

Special thanks to the Obsidian community for creating an amazing tool that inspired this project.
