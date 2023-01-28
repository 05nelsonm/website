+++
title: "{{ replace .Name "-" " " | title }}"

date: {{ now.Format "2006-01-02" }}
url: /{{ .Name }}/
image: images/2023-thumbs/{{ .Name }}.jpg
categories:
  - KotlinMultiplatform
  - Android
  - Linux
  - Networking
tags:
  - Software
draft: false
+++

