# FOREIGN COLORS

John Gates’s graduate research hub about American soccer fandom, MLS and the Premier League.

## Deploy
Render Static Site, branch `main`, build command `test -f dist/index.html`, publish directory `dist`, environment `SKIP_INSTALL_DEPS=true`. The committed distribution is prebuilt and needs no server, authentication or ChatGPT dependency.

## Edit and rebuild
Node >=22.13.0. Install dependencies, edit `app/page.tsx`, `app/data.ts` or `app/globals.css`, then run `npm run build`. Commit both source and the regenerated `dist` directory. Keep the package lock created by installation.

## Research status
Foreign Colors: Following the Money is an optional companion to the proposed 50–70-page thesis. Three pillars cover global commercial networks, league financial structures and American consumer behavior. The working argument is untested. Part A is a documentary comparison; Part B proposes a 15–20-question consumer survey after committee and IRB authorization.

The Fan Economics Explorer is educational only. Choices stay in React memory; no research responses are collected or persisted. The Research Survey section is informational and closed to participation. Update its status in `app/research-study.tsx` only when authorized. No survey endpoint or storage exists.

## Maintaining the research tools
Business comparison periods and official source links are in `app/color-tools.tsx`. Financial totals remain unavailable until units, currencies, periods and accounting scope can be reconciled. Existing bibliography attribution is retained; full-text verification and the novelty comparison with Su et al. (2025) remain pending. Historical sporting datasets remain in source for traceability but are not used to support the economic argument.

Conditional commercial scenarios and local-only action-plan downloads live in `app/explorations.tsx`. They are not proven recommendations. Photography attribution and licenses remain in Image Credits; image assets and the original palette are unchanged.

Regenerate and commit `dist/` using `npm run build`; the Render service serves that prebuilt directory directly. No new dependencies were added.
