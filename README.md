# git-commit-message-agent

Agent to generate Git Commit messages for you!

1. First, make sure that you [have `uvx` available](https://docs.astral.sh/uv/getting-started/installation/#standalone-installer) (until #[1632](https://github.com/enola-dev/enola/issues/1632))
1. Next, [create a Google Gemini API key](https://aistudio.google.com/apikey)!
1. Finally, [install Enola.dev](https://docs.enola.dev/use/), and now run:

```sh
GOOGLE_AI_API_KEY=... enola ai --http-scheme --agents=https://raw.githubusercontent.com/enola-dev/git-commit-message-agent/refs/heads/main/git-commit-message.agent.yaml --in="Make it so!"
```
