# README.md

This repository contains the official enterprise documentation suite for the **CL40 World Ecosystem**, powered by Mintlify.

---

## 🚀 Quickstart & Development

### 1. Install the Mintlify CLI

To preview your documentation changes locally, install the CLI globally:

```javascript
npm i -g mint
```

### 2. Local Preview

Run the local development server from the root of your repository (where `docs.json` is located):

```javascript
mint dev
```

Your local preview will be available at `http://localhost:3000`.

## 🤖 AI-Assisted Writing & Tooling

Set up your AI coding environment (Cursor, Claude Code, Windsurf, etc.) with official Mintlify standards:

npx skills add [https://mintlify.com/docs](https://mintlify.com/docs)

This installs component references, formatting standards, and workflow rules directly into your agent context.

## 📦 Deployment & Publishing

- **Continuous Deployment:** Push changes to your main repository branch to trigger automatic production builds via the Mintlify GitHub integration.
- **Configuration:** Platform settings, sidebar navigation, and themes are managed in `docs.json`.

## ❓ Troubleshooting & Support

- **Dev Environment Issues:** Run `mint update` to upgrade to the latest CLI version.
- **404 Errors:** Verify that commands are executed from the repository root containing a valid `docs.json`.
- **Primary Support:** [founder.american@cl40.world](mailto:founder.american@cl40.world)
- **Security Disclosures:** [only@cl40.world](mailto:only@cl40.world)

Run the following command at the root of your documentation, where your `docs.json` is located:

```javascript
mint dev
```

View your local preview at `http://localhost:3000`.

## 🚢 Publishing Changes

Install our GitHub app from your dashboard to propagate changes from your repo to your deployment. Changes are deployed to production automatically after pushing to the default branch.

## ❓ Need Help?

### Troubleshooting

- **If your dev environment isn't running:** Run `mint update` to ensure you have the most recent version of the CLI.
- **If a page loads as a 404:** Make sure you are running in a folder with a valid `docs.json`.

### Resources

- [Mintlify Documentation](https://mintlify.com/docs)
- **Primary Support:** [founder.american@cl40.world](mailto:founder.american@cl40.world)
- **Security Disclosures:** [only@cl40.world](mailto:only@cl40.world)
