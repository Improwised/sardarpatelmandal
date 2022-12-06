---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: true
width: 12
image: ""
metaTitle: "Gallery | Shree Sardar Patel Employees Group, Rajkot"
metaDes: ""
---

{{< load-photoswipe >}}
{{< gallery dir="/images/" />}}
