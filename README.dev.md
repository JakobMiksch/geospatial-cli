# README development

This repo uses the GitHub Action [markdown-link-check](https://github.com/marketplace/actions/markdown-link-check) for finding dead links. 

It can be run a locally with: (see [markdown-link-check](https://github.com/tcort/markdown-link-check) for details)
```shell
docker run -v ${PWD}:/tmp:ro --rm -i ghcr.io/tcort/markdown-link-check:stable /tmp/README.md
```
