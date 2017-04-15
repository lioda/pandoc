# Pandoc

A Docker wrapping of pandoc to use in CI.

Usage:
```
docker run --rm -ti -v $(pwd):/text lioda/pandoc pandoc /text/*.md
```
