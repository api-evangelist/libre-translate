---
title: "MiniSBD storage directory"
url: "https://community.libretranslate.com/t/minisbd-storage-directory/2188"
date: "2026-04-25"
author: "argosopentech"
feed_url: "https://community.libretranslate.com/latest.rss"
---
@pierotofy I have a question about where MiniSBD stores the packages it downloads (on Linux). Reading the code in argos-translate/package.py it seems like the minisbd packages should be saved to $HOME/.local/share/argos-translate/packages/translate-ar_en/minisbd . Reading the code in minisbd/models.py it seems to want to save them to $HOME/.cache .
