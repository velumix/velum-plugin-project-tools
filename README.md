# Project tools for Velum Code

A small plugin by **Velumix** that turns a workspace into a useful starting point for your coding agent.

| Command | What it does |
| --- | --- |
| Create project brief | Lists root files, package details, and available scripts. |
| Prepare review checklist | Creates a review prompt based on the project and your chosen focus. |

## Install

Open **Plugins** in [Velum Code](https://github.com/velumix/VelumCode), paste `velumix/velum-plugin-project-tools`, and choose **Review plugin**. Review the workspace-read permission, then install.

Run a command to see its result. **Add to draft** puts it into your conversation without sending it automatically. The plugin makes no network or AI requests.

## Permissions

`workspace.read` allows reading text files and listing folders in the current workspace. These commands list the root folder and read `package.json` when present. They cannot modify files or run a shell.

## Updates and development

Use **Check for updates** in Velum. Every installed version is pinned to a commit, and each update requires review.

This repository is also a working example for plugin authors. Keep `velum-plugin.json` and built `index.js` at the root of your public GitHub repository. See the [plugin SDK guide](https://github.com/velumix/VelumCode/blob/main/docs/plugins.md) for the API, TypeScript types, and limits.
