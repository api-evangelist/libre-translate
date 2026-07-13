---
title: "Introducing MiniSBD: Fast sentence boundary detection"
url: "https://community.libretranslate.com/t/introducing-minisbd-fast-sentence-boundary-detection/2118"
date: "2026-01-04"
author: "pierotofy"
feed_url: "https://community.libretranslate.com/latest.rss"
---
Continuing the discussion from Sentence Boundary Detection for Machine Translation - #55 by pierotofy , I’m happy to share MiniSBD, a subset port of Stanza’s tokenizer models that uses 8-bit quantized ONNX models for inference, making it extremely lightweight and fast. It only depends on onnxruntime (or onnxruntime-gpu for GPU inference), which means this paves the way for potentially removing argos-translate’s dependency on pytorch (more on this below). Code: GitHub - LibreTranslate/MiniSBD: Free and open source library for fast sentence boundary detection Installation: pip install minisbd Us
