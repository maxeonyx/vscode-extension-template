# VS Code Extension Template

![VS Code Extension Template icon](./icon.png)

A template for creating VS Code extensions with webviews.

This extension provides a basic structure for a VS Code extension, including:

- A "Hello World" command.
- A sidebar webview.
- A custom editor webview.

Use this as a starting point for your own VS Code extension development.

## Features

- **Hello World Command**: A simple command accessible from the command palette (`VS Code Extension Template: Hello World`).
- **Sidebar Webview**: A basic webview displayed in the activity bar.
- **Custom Editor Webview**: A webview that opens for files with the `.template` extension.

## Getting Started

1. Clone this repository.
2. Open the repository in VS Code.
3. Press `F5` to run the extension in a new Extension Development Host window.

## Project Structure

- `src/extension.ts`: The main extension file where activation and contributions are registered.
- `src/sidebarWebview.ts`: Implements the `WebviewViewProvider` for the sidebar webview.
- `src/customEditor.ts`: Implements the `CustomEditorProvider` for the custom editor webview.
- `media/index.html`: The HTML content for the webviews.
- `package.json`: The extension manifest.

## Building and Packaging

- Compile the TypeScript source code: `npm run compile`
- Watch for changes and compile automatically: `npm run watch`
- Run tests: `npm test`
- Package the extension: `vsce package`
- Publish the extension: `vsce publish`

## Release Notes

### 0.1.0

Initial release of the VS Code Extension Template.

- Basic "Hello World" command.
- Sidebar webview example.
- Custom editor webview example.
- Cleaned up from the original 'better-replace-on-save' extension.

---

**Enjoy!**
