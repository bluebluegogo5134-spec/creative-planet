# Hero V3 QA Gate

This file defines the release gate for the Home V2 hero preview. Do not move to the next homepage section until all checks pass on a 402px-wide iPhone Safari viewport.

## Engineering / static-layout checks

- [x] 0 broken images in local static render
- [x] Background asset exists and renders locally
- [x] Stars layer asset exists and renders locally
- [x] Character layer asset exists and renders locally
- [x] Glass rose asset exists and renders locally
- [x] Left flower layer asset exists and renders locally
- [x] Right flower layer asset exists and renders locally
- [x] Quote is exactly two visual lines: `慢一点也没关系，` / `但不要离自己的星球太远`
- [x] No image placeholder borders or missing-image icons in local static render
- [x] Character / rose / flowers form one coherent composition in local static render
- [x] No Hero overflow into the next section in local static render

## Final device gate

- [ ] Hero remains correct and legible on actual 402px-class iPhone Safari/PWA viewport

Status: READY FOR ISOLATED DEVICE QA — engineering/resource checks passed. Do not advance to section 2 until the iPhone Safari/PWA check passes.
