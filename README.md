# Nextra Docs on Fleek

This is a Next.js application generated with
[Create Nextra](https://github.com/shuding/nextra-docs-template).
Nextra is a minimalist, fully customizable documentation site built for easy deployment on Fleek. Perfect for showcasing project documentation, this template uses Next.js to deliver a smooth experience.

## Prerequisites 
- Node 18+
- Fleek Account
- [Fleek CLI](https://www.npmjs.com/package/@fleek-platform/cli)
- [Fleek Next Adapter](https://www.npmjs.com/package/@fleek-platform/next)

## Getting Started
1. Fork the repository
2. Clone the repository by running the following command:
```bash
git clone https://github.com/<your-id>/nextra-on-fleek.git
```
3. Enter the correct directory, install dependencies and run locally:
```bash
cd nextra-on-fleek
pnpm i
pnpm run dev
```
3. Ensure that you install the Fleek CLI and the Fleek Next Adapter:
```bash
// local installation
npm i @fleek-platform/cli
npm i @fleek-platform/next

// global installation
npm i -g @fleek-platform/cli
npm i -g @fleek-platform/next
```
💡: you can check the Fleek CLI version by running fleek -v. Any version >= 2.10.1 should be good. As for the Fleek Next adapter, you can check the Fleek Next Adapter version by running fleek-next -v. Any version >= 1.0.6 should be good.

## Building and Deploying on Fleek

Get a PAT (Personal Access Token). Run `fleek PAT create`, give it a name, login in to the platform, and copy your PAT.

Then run `export FLEEK_TOKEN=<your personal access token>` in your terminal to set your environment variables.


Then create a project ID. Run `fleek projects create`, give it a name, and copy your ID.

Then create a `fleek.json` file. Paste this in:

```bash
{
    "FLEEK_PROJECT_ID": "<project_id>"
}
```

Then run `fleek-next deploy`


[**Live Demo →**](https://old-russia-early.functions.on-fleek.app/)

[![](.github/screenshot.png)](https://old-russia-early.functions.on-fleek.app/)

## License

This project is licensed under the MIT License.
