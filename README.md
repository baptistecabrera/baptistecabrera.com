[![GitHub Release](https://img.shields.io/github/v/tag/baptistecabrera/baptistecabrera.com?logo=github&logoColor=white&label=release)](https://github.com/baptistecabrera/baptistecabrera.com/releases) [![License: MIT](https://img.shields.io/github/license/baptistecabrera/baptistecabrera.com?logo=open-source-initiative&logoColor=white)](https://opensource.org/licenses/MIT)

# Introduction 
This repository contains the sources of [my website](https://www.baptistecabrera.com) and its CI/CD pipelines.

# Technologies
This website uses:
- [Hugo Framework](https://gohugo.io/), that help creating website from markdown files;
- [CloudFlare Workers](https://workers.cloudflare.com/), to host code on a serverless infrastructure.

For more about these, and why, learn more with [this blog post](https://www.florianschmitt.ca/blog/ultra-minimalist-website-with-hugo-and-cloudflare-workers    ).

# Pipelines
## CI
[![Build Status](https://dev.azure.com/baptistecabrera/Bca/_apis/build/status/Build/baptistecabrera.com?branchName=main)](https://dev.azure.com/baptistecabrera/Bca/_build/latest?definitionId=39&branchName=main)

## CD
[![Build Status](https://dev.azure.com/baptistecabrera/Bca/_apis/build/status/Release/baptistecabrera.com?branchName=main)](https://dev.azure.com/baptistecabrera/Bca/_build/latest?definitionId=40&branchName=main)