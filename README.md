# FOREIGN COLORS

John Gates’s graduate research hub about American soccer fandom, MLS and the Premier League.

## Deploy
Render Static Site, branch `main`, build command `test -f dist/index.html`, publish directory `dist`, environment `SKIP_INSTALL_DEPS=true`. The committed distribution is prebuilt and needs no server, authentication or ChatGPT dependency.

## Edit and rebuild
Node >=22.13.0. Install dependencies, edit `app/page.tsx`, `app/data.ts` or `app/globals.css`, then run `npm run build`. Commit both source and the regenerated `dist` directory. Keep the package lock created by installation.

## Research status
The project uses secondary research on American soccer fandom. RQ3 compares documented quality perceptions with observable soccer characteristics; it does not propose a blind-evaluation experiment. Interactive prompts are conceptual applications, not validated diagnostics or original findings. No participant data is collected. Existing evidence, contextual sources, personal motivation and applications are labeled separately.

Photography attribution and licenses appear in the site’s Image Credits. Adapted STL image remains CC BY-SA 4.0.
