---
title: "User-Agent header is required for API calls"
url: "https://community.libretranslate.com/t/user-agent-header-is-required-for-api-calls/2147"
date: "2026-03-13"
author: "stokito"
feed_url: "https://community.libretranslate.com/latest.rss"
---
I’m using the unofficial Java API client dynomake/libretranslate-java and years ago it stopped working. The API server closes a connection if the User-Agent header is empty and this results in “java.net.SocketException: Connection reset” Are any reasons why the UA is required? The UA should be just deprecated on the HTTP spec level because it was needed only in old times to add IE specific quirks.
