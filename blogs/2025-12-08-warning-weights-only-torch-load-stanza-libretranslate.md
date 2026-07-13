---
title: "Warning: weights_only, torch.load, stanza, libretranslate"
url: "https://community.libretranslate.com/t/warning-weights-only-torch-load-stanza-libretranslate/2093"
date: "2025-12-08"
author: "Bredordom"
feed_url: "https://community.libretranslate.com/latest.rss"
---
FYI. There is a following warning in the libretranslate:v1.8.3 container log during every translation attempt: /app/venv/lib/python3.11/site-packages/stanza/models/tokenize/trainer.py:85: FutureWarning: You are using torch.load with weights_only=False (the current default value), which uses the default pickle module implicitly. It is possible to construct malicious pickle data which will execute arbitrary code during unpickling (See pytorch/SECURITY.md at main · pytorch/pytorch · GitHub for more details).
