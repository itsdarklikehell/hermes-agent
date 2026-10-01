# hermes-agent

<img src="https://img.shields.io/github/stars/itsdarklikehell/hermes-agent?style=flat-square&color=blue" alt="Stars">
<img src="https://img.shields.io/github/forks/itsdarklikehell/hermes-agent?style=flat-square&color=green" alt="Forks">
<img src="https://img.shields.io/github/license/itsdarklikehell/hermes-agent?style=flat-square" alt="License">
<img src="https://img.shields.io/github/actions/workflow/status=itsdarklikehell/hermes-agent/ci.yml?branch=main&label=CI&style=flat-square" alt="CI Status">

The self-improving AI agent built by [Nous Research](https://nousresearch.com). It's the only agent with a built-in learning loop — it creates skills from experience, improves them during use, nudges itself to persist knowledge, searches its own past conversations, and builds a deepening model of who you are across sessions.

## Installatie

### Linux, macOS, WSL2, Termux

```bash
curl -fsSL https://hermes-agent.nousresearch.com/install.sh | bash
```

### Windows (PowerShell)

```powershell
iex (irm https://hermes-agent.nousresearch.com/install.ps1)
```

After installation:

```bash
source ~/.bashrc    # reload shell
hermes              # start chatting!
```

## Gebruik

```bash
hermes              # Interactive CLI — start a conversation
hermes model        # Choose your LLM provider and model
hermes tools        # Configure which tools are enabled
hermes config set   # Set individual config values
hermes config get   # Print individual config values
hermes gateway      # Start the messaging gateway (Telegram, Discord, etc.)
hermes setup        # Run the full setup wizard
hermes claw migrate # Migrate from OpenClaw
hermes update       # Update to the latest version
hermes doctor       # Diagnose any issues
```

## Bijdragers

- [Nous Research](https://nousresearch.com) — Creator
- [itsdarklikehell](https://github.com/itsdarklikehell) — Fork maintainer
- Community contributors via [GitHub](https://github.com/NousResearch/hermes-agent/graphs/contributors)

## Licentie

MIT — zie [LICENSE](LICENSE) voor details.

## Documentation

📖 **[Full documentation →](https://hermes-agent.nousresearch.com/docs/)**

## Community

- 💬 [Discord](https://discord.gg/NousResearch)
- 📚 [Skills Hub](https://agentskills.io)
- 🐛 [Issues](https://github.com/NousResearch/hermes-agent/issues)
