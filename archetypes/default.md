+++
date = '{{ .Date }}'
draft = true
title = '{{ replace .File.ContentBaseName "-" " " | title }}'
author = '{{ site.Params.author.name }}'
tags = []
+++
