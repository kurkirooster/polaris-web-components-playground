# Approosters - Polaris web components playground

Approosters's Polaris web components playground is a lightweight, standalone playground designed for experimenting with [Shopify's Polaris web components](https://shopify.dev/docs/api/app-home/polaris-web-components). It provides a streamlined environment to write code, see live results, and reference documentation all in one window.

**[Live demo](https://kurkirooster.github.io/polaris-web-components-playground/)**

## Features

- **Live editor**: Integrated CodeMirror editor with syntax highlighting for HTML and Polaris components.
- **Real-time preview**: Instantly view the rendered output of your Polaris code. The preview updates automatically as you type.
- **Integrated documentation**: Built-in pane showing the official Polaris Web Components documentation for quick reference.
- **Flexible layout**:
  - Resizable panes allowing you to adjust the ratio between the editor and preview, and between the workspace and documentation.
  - Toggle controls to show or hide the Editor, Preview, and Documentation panes to suit your workflow.
- **Zero setup**: A single HTML file with no build process or server requirements.
- **Dark mode UI**: A comfortable dark interface for the workspace.

## Getting started

Since this is a standalone HTML application, there is no installation required.

1.  Clone this repository or download the `index.html` file.
2.  Open `index.html` in any modern web browser (Chrome, Firefox, Safari, Edge).
3.  Start coding!

## Usage

- **Editor**: Write your HTML and Polaris Web Component tags (e.g., `<s-page>`, `<s-button>`) in the left pane.
- **Preview**: See the rendered components in the right pane.
- **Documentation**: Refer to the bottom pane for API details and component examples.
- **Resizing**: Drag the borders between panes to resize them.
- **Toggles**: Use the checkboxes in the header to show/hide specific sections.

## Technologies used

- **HTML5 & CSS3**
- **Vanilla JavaScript**
- **[CodeMirror](https://codemirror.net/)**: For the code editing experience.
- **[Shopify Polaris](https://polaris.shopify.com/)**: The underlying design system and web components (loaded via CDN).

## License

This project is available under the MIT License.
