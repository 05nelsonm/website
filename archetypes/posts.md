+++
title = "{{ replace .Name "-" " " | title }}"
type = "posts"
date = "{{ now.Format "2006-01-02" }}"

url = "/posts/{{ now.Format "2006" }}/{{ .Name }}"

categories = ["Kotlin Multiplatform", "Android", "Software Development"]
tags = ["Kotlin"]

draft = false
+++

