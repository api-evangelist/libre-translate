---
title: "LTEngine - LLM powered local machine translation"
url: "https://community.libretranslate.com/t/ltengine-llm-powered-local-machine-translation/1862?page=3#post_48"
date: "2026-08-12"
author: "@NicoLe Nicolas Lecoq"
feed_url: "https://community.libretranslate.com/posts.rss"
---
You do not need that much VRAM. With quantization to 8 bits and enough kvcache for 10 workers and a 32k token context, Mistral-24b consumes around 30GB VRAM.
