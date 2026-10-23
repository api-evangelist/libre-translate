---
title: "Update language models (Docker)"
url: "https://community.libretranslate.com/t/update-language-models-docker/412#post_3"
date: "2026-08-26"
author: "@laughlaugh Arthro Timber"
feed_url: "https://community.libretranslate.com/posts.rss"
---
Does install_models.py get run from within the libretranslate container, or in the outer server? When I run it within the container I get this error trace: > Traceback (most recent call last): > File "/app/scripts/./install_models.py", line 8, in > from libretranslate.init import check_and_install_models > File "/app/libretranslate/__init__.py", line 2, in > from .main import main > File "/app/libretranslate/main.py", line 6, in > from libretranslate.app import create_app > File "/app/libretranslate/app.py", line 14, in > import argostranslatefiles > ModuleNotFoundError: No module named 'argos
