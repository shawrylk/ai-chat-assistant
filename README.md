# ai-chat-assistant

A Claude Code plugin with guidance for building an in-app chat assistant that uses Claude and calls application tools.

Clone the repository and load the plugin in Claude Code.

```sh
git clone https://github.com/shawrylk/ai-chat-assistant.git
cd ai-chat-assistant
claude --plugin-dir .
```

Ask Claude to help build or extend an in-app chat assistant, or invoke the skill with `/ai-chat-assistant:ai-chat-assistant`.

Run the tests with `npm test` on Node 24. The plugin loads directly from the checkout.

The skill came from [architecture-kit at `7883543`](https://github.com/shawrylk/architecture-kit/tree/7883543f506a93917600f1012605982ae63f8ed5/skills/ai-chat-assistant).
