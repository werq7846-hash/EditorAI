# Editor AI

Describe the level you want in natural language and EditorAI uses your selected AI model to generate it. Results are placed in a separate preview layer, where you can accept, edit, or deny them.

## Opening the panel

On desktop, press the default hotkey <cg>E</c>. On mobile, tap the on-screen <cg>AI</c> button. The panel lets you start generation, monitor progress, chat with the AI, and change settings.

## Choosing an AI provider

Open <cy>Settings</c> in the panel and choose a provider.

- <cy>Platinum</cy>: Set the provider to <cg>ollama</c> and enable <cg>Use Platinum</c>. This uses a community-operated server; do not enter personal information in prompts.
- <cy>Ollama</c>: Run a model locally. Install Ollama, download a model, then set the provider to <cg>ollama</c>.
- Hosted services such as Gemini, Claude, and OpenAI may require their own API keys. OpenRouter and Hugging Face also support browser sign-in from the panel.

## Usage

1. Select <cy>Chat</c> → <cg>+ new chat</c> in the panel.
2. Choose a target level: the current editor level, a new level, or an existing level.
3. Enter your prompt, configure difficulty, style, and length, then select <cg>Generate</cg>.
4. Monitor generation. Work may continue if you close the panel or editor.
5. Review the result in the preview layer and select <cg>Accept</cg>, <cy>Edit</cy>, or <cr>Deny</cr>.
6. Continue the conversation to request small changes, a full rewrite, a plan, or answers. Chats persist across restarts.
7. Submit a rating when prompted.

Each setting has a tooltip explaining its function.

Report bugs and suggest features through issues in the GitHub repository.
