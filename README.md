# PrivateInvest Documentation

This is the Mintlify documentation site for the PrivateInvest platform.

## Setup

1. Install Mintlify CLI globally:
```bash
npm i -g mint
```

2. Navigate to this directory:
```bash
cd mintlify-docs
```

3. Start the development server:
```bash
mint dev
```

4. View your documentation at `http://localhost:3000`

## Structure

The documentation is organized into the following sections:

- **Getting Started**: Setup guides, database configuration, user credentials
- **Architecture & Design**: PRD, tech stack, design system, implementation plan
- **API Documentation**: API overview and troubleshooting
- **Agent System**: Complete agent system documentation
- **Development**: Setup status and completion guides

## Publishing

Changes are automatically deployed to production when you push to the default branch (main) if you have the Mintlify GitHub app installed from your dashboard.

## Updating Documentation

1. Edit the `.mdx` files in the appropriate directories
2. Test locally with `mint dev`
3. Commit and push to the repository
4. Changes will be automatically deployed

## File Locations

- Main configuration: `docs.json`
- Homepage: `index.mdx`
- Documentation files: Organized in subdirectories by topic
