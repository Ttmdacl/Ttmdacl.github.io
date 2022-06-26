---
title:  "HTML에서 Jinja 주석 처리 할 때"
date: 2022-06-27. 07:45
categories: Programming Normal
---

HTML 파일에서 Jinja 코드를 주석처리 할 때

```html
<!-- Jinja Code -->
```

 같이 HTML 주석안에 Jinja 코드를 넣으면 주석처리 되지 않는다.

```html
{# Jinja Code #}
```

처럼 Jinja 주석안에 넣어줘야 한다.
