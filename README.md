# Demonstration for houdini + svelte type export syntax bug

Error occurs in `src/lib/test/index.ts` on `export { type TestTypeExport } from "./test.svelte";`

Remove the houdini plugin from `vite.config.ts` to resolve and demonstrate that the houdini plugin causes the issue.