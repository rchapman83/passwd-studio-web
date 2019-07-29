---
title: Release [v1.0]
date: 2019-07-29 18:01:00 +10:00
categories:
- release notes
tags:
- how to
- guide
- release notes
---

Version 1 of my password generator API (passwd.studio) has been released. It is a very simple project, there are only two endpoints as this moment; root `/` will generated a random complex password 22 characters long and `/key` will generate a 64 character random base64 string which can be used for secret keys or tokens. My intention is to add additional endpoints and features over time. 

You can hit the API using your favorite API Development tool (IE PostMan) or simply use cURL via the CLI. 

> curl http://api.studio.passwd/

> curl http://api.studio.passwd/key