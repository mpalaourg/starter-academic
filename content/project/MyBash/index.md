---
title: Bash-ic shell
summary: My version of Linux Bash Shell.
tags:
- bash
- terminal
- linux-unix
- C
date: "2016-04-27T00:00:00Z"

image:
  caption: ""
  focal_point: Smart

url_code: "https://github.com/mpalaourg/OperatingSystems_MyBash"
url_pdf: ""
url_slides: ""
url_video: ""
---

The goal is to create my own simplistic Unix shell in C. Where,

- cd, help and quit are handled as Built-In functions.
  - For other functions type ```@function_name @arguments```. If you need more info, type ```man @function_name```.
- **Improper space handle**.
- **Redirection with > handle**.
- **Redirection with < handle**.
- Two modes supported:
  - **Interactive**, when no arguments are given.
  - **Batch**, when 1 (one) argument (file) is given.

For a more detailed description of the functionality check [here](https://github.com/mpalaourg/OperatingSystems_MyBash#operating-systems-final-assignment-auth-2018).
