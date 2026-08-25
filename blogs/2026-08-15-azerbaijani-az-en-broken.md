---
title: "Azerbaijani AZ_EN broken?"
url: "https://community.libretranslate.com/t/azerbaijani-az-en-broken/2268"
date: "2026-08-15"
author: "reverse-blade"
feed_url: "https://community.libretranslate.com/latest.rss"
---
django@server:~/server/src$ argospm update django@server:~/server/src$ argospm install translate-az_en django@server:~/server/src$ argospm install translate-en_az django@server:~/server/src$ argos-translate --from az --to en “Pücün Azərbayzan medeniyatinin azərbayzın dilinine gədə önəmli olduğu hətk mesyəddəyir.” 2026-08-15 13:21:25 WARNING: Unsupported language: az If trying to add a new language, consider using allow_unknown_language=True Traceback (most recent call last): File “/home/django/server/bin/argos-translate”, line 8, in sys.exit(main()) ^^^^^^ File “/home/django/server/lib/python3
