---
title: "{{ replace .Title "-" " " | title }}"
name: "{{ replace .Params.Name "-" " " | name }}"
email: "{{ replace .Params.Email "-" " " | email }}"
github: "{{ replace .Params.Github "-" " " | github }}"
twitter: "{{ replace .Params.Twitter "-" " " | twitter }}"\
linkedin: "{{ replace .Params.Linkedin "-" " " | linkedin }}"
avatar: "{{ replace .Params.Avatar "-" " " | avatar }}"
date: {{ .Date }}
draft: true
---

