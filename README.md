# Scripts Collection

This repository houses assorted utility scripts for various purposes, open sourced for the greater good.

## Getting Started

To install dependencies:

```bash
bun install
```

To run a script:

```bash
bun src/scriptName.ts
```

Some scripts may require environment variables to be set. These can be set in a `.env` file in the root of the project.

Scripts may also read and write data from the Git submodule `private-data`. This is done to house sensitive data for my use only -- feel free to clone the repo and update the file paths in scripts to point to your own data inputs and outputs.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
