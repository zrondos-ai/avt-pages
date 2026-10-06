# AVT project snapshots

Static seed-view HTML exported from the local agentic-video-testing app.

- Site: https://zrondos-ai.github.io/avt-pages/
- Generate UI snapshot (design feedback): https://zrondos-ai.github.io/avt-pages/generate/5iek4jluvBC8krJrkM0aF1/450/
- P0 image grid (181402Z + 183838Z + 200558Z): https://zrondos-ai.github.io/avt-pages/evals/p0-grids/20260928-suite537-536/
- Grok upsampler eval (Grok Upsampler · transform P0 → P1 (suite 540)): https://zrondos-ai.github.io/avt-pages/evals/grok-upsampler/20260928T200558Z/
- Grok upsampler eval (Grok Upsampler · transform P0 → P1 (suite 536)): https://zrondos-ai.github.io/avt-pages/evals/grok-upsampler/20260928T183838Z/
- Grok upsampler eval (Grok Upsampler · transform P0 → P1 (suite 537)): https://zrondos-ai.github.io/avt-pages/evals/grok-upsampler/20260928T181402Z/
- Grok upsampler eval (Grok Upsampler · 20260928T034134Z): https://zrondos-ai.github.io/avt-pages/evals/grok-upsampler/20260928T034134Z/
- Grok upsampler eval (Grok Upsampler · 20260926T212804Z): https://zrondos-ai.github.io/avt-pages/evals/grok-upsampler/20260926T212804Z/
- Grok upsampler eval (Grok Upsampler · 20260924T230037Z): https://zrondos-ai.github.io/avt-pages/evals/grok-upsampler/20260924T230037Z/
- Images load from the original CDN (not bundled in these files)
- This site is **public**

Refresh / add a project from the AVT repo:

```bash
avt export-pages --project-id <id> --out ~/Desktop/avt-pages
cd ~/Desktop/avt-pages && git add -A && git commit -m "Export project <id>" && git push
```

Publish a Grok Upsampler eval share table from the AVT UI (**Export to GitHub Pages**), or:

```bash
python scripts/export_grok_upsampler_xlsx.py --eval-id <eval_id> --html-only
# then use the UI button, or copy share.html + _share_thumbs into avt-pages
```
