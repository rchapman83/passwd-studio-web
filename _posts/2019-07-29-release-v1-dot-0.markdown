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

Version 1 of my password generator API aka passwd.studio has been release. There are only two endpoints as the moment; root `/` will generated a random complex password 22 characters long and `/key` will generate a 64 character random base64 string which can be used for secret keys or tokens.  
`code test`
> curl http://api.studio.passwd/
or 
> curl http://api.studio.passwd/key