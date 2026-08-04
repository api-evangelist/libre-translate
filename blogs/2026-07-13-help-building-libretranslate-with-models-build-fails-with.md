---
title: "Help building LibreTranslate with models: Build fails with timeout error"
url: "https://community.libretranslate.com/t/help-building-libretranslate-with-models-build-fails-with-timeout-error/2251"
date: "2026-07-13"
author: "Samapol"
feed_url: "https://community.libretranslate.com/latest.rss"
---
Update : See second post first, might have solved a lot already. Hi everyone, I’m trying to build LibreTranslate with specific models preloaded for offline use but keep hitting a build timeout error. Here’s what I’ve done so far: Attempted the official guide : The build command from the Github’s LibreTranslate CONTRIBUTING.md help file, but fails with: ERROR: docker: 'docker buildx build' requires 1 argument After researching, I used docker buildx but the build times out during the model installation step: docker buildx build -f docker/Dockerfile \ --build-arg with_models=true \ -t libretransl
