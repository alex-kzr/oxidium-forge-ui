# oxidium-forge-ui

The **React management and visualization frontend** for [Oxidium Forge](https://github.com/alex-kzr/oxidium-forge).

Provides a web UI for deploying BPMN processes, monitoring running instances, viewing incidents, managing jobs and manual tasks, and visualizing BPMN diagrams with **bpmn-js**.

## Tech Stack

- **Vite** + **React** + **TypeScript**
- **React Query** for server state management
- **bpmn-js** for BPMN diagram rendering
- Talks to `oxidium-forge-core` REST API at `http://localhost:7700`

## Quick Start

> **[planned]** — Available after Phase 9 (Management UI) lands.

```bash
npm install
npm run dev
# Open http://localhost:5173
```

## Documentation

| Section | Description |
|---------|-------------|
| [REST API](https://github.com/alex-kzr/oxidium-forge/blob/main/docs/api/rest-api.md) | Core API the UI talks to |
| [Architecture](https://github.com/alex-kzr/oxidium-forge/blob/main/docs/architecture/system-design.md) | System overview |
| [BPMN Support Matrix](https://github.com/alex-kzr/oxidium-forge/blob/main/docs/bpmn-elements/README.md) | Supported BPMN elements |

## License

This project is licensed under the MIT License. See [LICENSE.md](./LICENSE.md)