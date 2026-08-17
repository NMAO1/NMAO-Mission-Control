# NMAO Mission Control — mc.nmao.us
Static GitHub-Pages host for the tournament staff operator console (round launcher + live pipeline
board + config + judges). Files are the NMAO-Tournament `mission-control/` build; the Supabase URL +
**anon** key are baked in and every page self-gates on staff login, so the public URL is safe.

**Publish (GitHub Desktop):** Add Local Repository → this folder → Publish (Private is fine) →
then Settings → Pages: Source = deploy from branch (root), custom domain = `mc.nmao.us`, Enforce HTTPS.
DNS `mc → nmao1.github.io` is already set.
