# sse-client

A simple static page that allows you to POST to an HTTP endpoint and stream Server-Sent Events (SSE) responses.

## Usage

1. Open `index.html` in a modern browser.
2. Enter the request URL, token (optional) and JSON body template. Use `{{prompt}}` in the body to insert the message from the chat input.
3. Type a message in the bottom input and click **Send**. The SSE response will stream into the chat window and render as Markdown.
