+++
title = "{{ replace .Name "-" " " | title }}"
type = "blog"
date = "{{ now.Format "2006-01-02" }}"
url = "/blog/{{ now.Format "2006" }}/{{ .Name }}/"
categories = ["Kotlin Multiplatform", "Android", "Software Development"]
tags = ["Kotlin"]
draft = false
+++

