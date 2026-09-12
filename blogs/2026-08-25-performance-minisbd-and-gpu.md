---
title: "Performance, MiniSBD and GPU"
url: "https://community.libretranslate.com/t/performance-minisbd-and-gpu/2279"
date: "2026-08-25"
author: "fluchtkapsel"
feed_url: "https://community.libretranslate.com/latest.rss"
---
I am using LibreTranslate on a 12-core Epyc VM with Nvidia A4000 GPU. I tested the translation from German to English by pasting the wiki source of the German language Wikipedia article on the Riemannsche Vermutung ( https://de.wikipedia.org/w/index.php?title=Riemannsche_Vermutung&action=edit ) into the web UI. With ARGUS_DEVICE_TYPE=cpu it takes 4.3 minutes while with ARGUS_DEVICE_TYPE=cuda it takes about 2.5 minutes.
