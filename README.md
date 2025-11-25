# JFrog Fly Documentation

Welcome to the JFrog Fly documentation source. This documentation is built with [Mintlify](https://mintlify.com).

## 🚀 Quick Start

### Prerequisites

- Node.js 18 or higher
- npm or yarn

### Local Development

1. Install the Mintlify CLI:

```bash
npm i -g mintlify
```

2. Run the development server:

```bash
mintlify dev
```

3. Open [http://localhost:3000](http://localhost:3000) in your browser.

## 📁 Documentation Structure

```
docs/
├── introduction.mdx              # Main landing page
├── docs.json                     # Mintlify configuration
├── getting-started/              # Getting started guides
│   ├── overview.mdx
│   ├── account-setup.mdx
│   ├── git-connection.mdx
│   └── desktop-app.mdx
├── developer-workflow/           # Developer workflow guides
│   ├── overview.mdx
│   ├── local-artifact-management.mdx
│   ├── automated-workflows.mdx
│   └── runtime-deployment.mdx
├── desktop-app/                  # Desktop app documentation
│   ├── overview.mdx
│   ├── configuration.mdx
│   └── commands.mdx
├── fly-web/                      # Fly Web interface docs
│   ├── overview.mdx
│   ├── git-repositories.mdx
│   ├── artifacts.mdx
│   ├── releases.mdx
│   ├── workflows.mdx
│   ├── users-access.mdx
│   └── fly-chat.mdx
├── package-managers/             # Package manager configurations
│   ├── overview.mdx
│   ├── containers/
│   │   ├── docker.mdx
│   │   └── podman.mdx
│   ├── javascript/
│   │   └── npm.mdx
│   ├── python/
│   │   ├── pip.mdx
│   │   ├── twine.mdx
│   │   └── pipenv.mdx
│   ├── go/
│   │   └── overview.mdx
│   ├── java/
│   │   ├── maven.mdx
│   │   └── gradle.mdx
│   └── dotnet/
│       ├── nuget.mdx
│       └── dotnet-cli.mdx
├── resources/                    # Help resources
│   ├── faq.mdx
│   ├── troubleshooting.mdx
│   ├── glossary.mdx
│   ├── cli-reference.mdx
│   └── api-reference.mdx
├── images/                       # Image assets
├── logo/                         # Logo assets
│   ├── light.svg
│   └── dark.svg
└── favicon.svg                   # Favicon
```

## ✏️ Contributing

### Adding a New Page

1. Create a new `.mdx` file in the appropriate directory
2. Add frontmatter with title and description:

```mdx
---
title: "Page Title"
sidebarTitle: "Sidebar Title"
description: "Page description"
icon: "icon-name"
---

Your content here...
```

3. Add the page to `docs.json` in the navigation section

### Updating Navigation

Edit the `docs.json` file to modify the navigation structure. The file uses a tab-based navigation with groups and pages.

### Adding Images

Place images in the `images/` directory and reference them:

```mdx
<Frame>
  <img src="/images/my-image.png" alt="Description" />
</Frame>
```

## 🎨 Mintlify Components

This documentation uses various Mintlify components:

- `<Card>` - Clickable cards
- `<CardGroup>` - Group of cards
- `<Accordion>` - Expandable sections
- `<AccordionGroup>` - Group of accordions
- `<Tabs>` - Tabbed content
- `<Tab>` - Individual tab
- `<Steps>` - Step-by-step guides
- `<Step>` - Individual step
- `<Info>` - Info callout
- `<Warning>` - Warning callout
- `<Note>` - Note callout
- `<Tip>` - Tip callout
- `<Frame>` - Image frame
- `<CodeGroup>` - Multiple code blocks

## 📦 Deployment

The documentation is automatically deployed when changes are pushed to the main branch. Mintlify's GitHub App handles the deployment.

## 📝 License

Copyright © JFrog Ltd. All rights reserved.

## 🆘 Support

For documentation issues, please open a GitHub issue or contact [fly-support@jfrog.com](mailto:fly-support@jfrog.com).
