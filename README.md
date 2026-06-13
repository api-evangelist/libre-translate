# LibreTranslate

Free and open-source machine translation REST API supporting 30+ languages with self-hostable deployment and no third-party service dependency.

## Overview

LibreTranslate is powered by the open-source [Argos Translate](https://github.com/argosopentech/argos-translate) library and provides a REST API for:

- Text translation between 30+ languages
- Language detection
- File translation
- Translation suggestions

Unlike proprietary translation APIs, LibreTranslate can be fully self-hosted for offline use with no data leaving your infrastructure, or used via the managed hosted service at [portal.libretranslate.com](https://portal.libretranslate.com).

## API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| POST | /translate | Translate text |
| POST | /detect | Detect source language |
| GET | /languages | List supported languages |
| POST | /translate_file | Translate a file |
| POST | /suggest | Submit a translation suggestion |
| GET | /health | Service health check |
| GET | /frontend/settings | Frontend configuration |

## Authentication

- **Self-hosted**: Optional API key support via `--api-keys` flag
- **Managed service**: API key required, obtained at [portal.libretranslate.com](https://portal.libretranslate.com)

## Resources

- **Website**: https://libretranslate.com
- **Documentation**: https://docs.libretranslate.com
- **GitHub**: https://github.com/LibreTranslate/LibreTranslate
- **Portal / API Keys**: https://portal.libretranslate.com
- **Status**: https://status.libretranslate.com
- **Community**: https://community.libretranslate.com

## APIs.json

This repository contains an [APIs.json](https://apisjson.org) 0.19 profile for LibreTranslate maintained by [API Evangelist](https://apievangelist.com).

- `apis.yml` — Primary APIs.json index
- `plans/plans.yml` — Service plan details
- `rate-limits/rate-limits.yml` — Rate limiting policies
- `finops/finops.yml` — Cost model and financial operations details
