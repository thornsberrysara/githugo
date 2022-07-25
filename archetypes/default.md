---
title: "{{ replace .Title "-" " " | title }}"
name: "{{ replace .Params.Name "-" " " | name }}"
email: "{{ replace .Params.Email "-" " " | email }}"
github: "{{ replace .Params.Github "-" " " | github }}"
twitter: "{{ replace .Params.Twitter "-" " " | twitter }}"\
linkedin: "{{ replace .Params.Linkedin "-" " " | linkedin }}"
avatar: "{{ replace .Params.Avatar "-" " " | avatar }}"
headline: "{{ replace .Params.Headline "-" " " | headline }}"
location: "{{ replace .Params.Location "-" " " | location }}"
company: "{{ replace .Params.Company "-" " " | company }}"
date: {{ .Date }}
draft: true
---

