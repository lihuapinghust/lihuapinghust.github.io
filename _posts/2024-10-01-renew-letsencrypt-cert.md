---
title: Renew LetsEncrypt Certificate
date: 2024-10-01 00:00:00 +0800
categories: [Tech Inteview Prep]
tags: [Fullstack]
pin: false
---

sudo certbot certonly --standalone -d aadmin.focuslife.today

It prints certificate path when finished.

If you are using LNMP, edit /usr/local/nginx/conf/vhost/aadmin.focuslife.today.conf to put certificate path in the corresponding server.