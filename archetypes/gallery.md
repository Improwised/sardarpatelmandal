---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: true
width: 12
image: ""
---

{{< load-photoswipe >}}
{{< gallery dir="/images/" />}}
