
# Altus 4 Documentation

This repository contains the official documentation for **Altus 4**, an AI-enhanced MySQL full-text search engine. It provides comprehensive guides, API references, architectural details, and development resources for users and contributors.

## View Documentation

**Live Documentation:** [https://altus4.thavarshan.com/docs](https://altus4.thavarshan.com/docs)

## Auto-Synchronization

This repository is automatically synchronized from the main [altus4/core](https://github.com/altus4/core) repository.

- **Source:** `docs/` directory in the main repository
- **Sync Trigger:** Any push to `main` or `develop` branch that modifies documentation
- **Source Commit:** [5dfe25c](https://github.com/altus4/core/commit/5dfe25c69d6beb3b83bf3cd7ae7152207e8055d3)

## Contributing

**Please do not make direct changes to this repository.**

To contribute to the documentation:

1. Fork the [main repository](https://github.com/altus4/core)
2. Make changes to the `docs/` directory
3. Submit a pull request to the main repository
4. Changes will be automatically synchronized here upon merge

## Local Development

To work with the documentation locally:

```bash
# Clone the main repository
git clone https://github.com/altus4/core.git
cd altus4/docs

# Install dependencies
npm install

# Start development server
npm run docs:dev

# Build for production
npm run docs:build
```

## Documentation Structure

- **[Setup Guide](./setup/)** – Installation and deployment
- **[API Reference](./api/)** – Complete API documentation
- **[Architecture](./architecture/)** – System design and patterns
- **[Services](./services/)** – Service layer documentation
- **[Examples](./examples/)** – Code examples and tutorials
- **[Development](./development/)** – Contributing guidelines
- **[Testing](./testing/)** – Testing strategies and examples

## Automation Details

This repository uses GitHub Actions for:

- **Auto-sync** from main repository
- **Auto-build** documentation site
- **Auto-deploy** to GitHub Pages

## License

This documentation is part of the Altus 4 project. See the [main repository](https://github.com/altus4/core) for license information.
