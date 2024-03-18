+++
title = '{{ replace .File.ContentBaseName "-" " " | title }}'
date = {{ .Date }}
year = {{ time.Format "2006" .Date }}
draft = true
+++
