# AVT project snapshots

Static seed-view HTML exported from the local agentic-video-testing app.

- Site: https://zrondos-ai.github.io/avt-pages/
- Grok upsampler eval: https://zrondos-ai.github.io/avt-pages/evals/grok-upsampler/20260924T230037Z/
- Images load from the original CDN (not bundled in these files)
- This site is **public**

Refresh / add a project from the AVT repo:

```bash
avt export-pages --project-id <id> --out ~/Desktop/avt-pages
cd ~/Desktop/avt-pages && git add -A && git commit -m "Export project <id>" && git push
```
