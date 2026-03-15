# NIOM Documentation

The official documentation for [NIOM](https://github.com/niomstack/niom) — a local-first AI agent that lives on your desktop.

Built with [Mintlify](https://mintlify.com).

## Development

```bash
# Install Mintlify CLI
npm i -g mintlify

# Start local dev server
mintlify dev
```

The docs will be available at `http://localhost:3000`.

## Structure

```
├── index.mdx                # Landing page
├── quickstart.mdx           # Installation + first steps
├── configuration.mdx        # Settings, providers, Ollama
├── guides/                  # Core feature guides
│   ├── memory.mdx           # Persistent memory system
│   ├── skill-routing.mdx    # Intelligent tool routing
│   ├── background-tasks.mdx # Autonomous task execution
│   ├── tools.mdx            # Built-in tool reference
│   ├── project-awareness.mdx # Workspace auto-detection
│   ├── keyboard-shortcuts.mdx # Hotkeys and shortcuts
│   ├── ollama.mdx           # Local model setup
│   └── privacy.mdx          # Privacy & security model
├── architecture/            # Technical deep dives
│   ├── overview.mdx         # System architecture
│   ├── context-engine.mdx   # NCF tiered memory design
│   ├── skill-tree.mdx       # Hierarchical routing algorithm
│   └── task-system.mdx      # Background task orchestration
└── docs.json                # Mintlify configuration
```

## License

MIT — same as NIOM itself.
