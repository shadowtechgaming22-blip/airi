
## Local Build Notes (shadowtechgaming22-blip fork, 2026-10-06)

This fork has been verified to:
- Fork cleanly from moeru-ai/airi main
- `pnpm install` succeeds (2824 packages)
- `pnpm run build:packages` succeeds (34/34 workspace builds)
- `pnpm -F @proj-airi/stage-web typecheck` passes (vue-tsc --noEmit, no errors)
- `pnpm -F @proj-airi/stage-web build` succeeds (`✓ built in 29.78s`)

Generated 418MB of dist with 700 PWA-precached entries.

To run the web app locally:
```bash
cd /home/rootkit/.openclaw/workspace/airi
pnpm install
pnpm run build:packages  # only needed on fresh checkout
pnpm dev:web             # http://localhost:5173
```
