---
title: A5-Broken Access Control
date: 1497804944000
description: Restrictions on what authenticated users are allowed to do are often not properly enforced. Attackers can exploit these flaws to access unauthorized functionality and/or data, such as access other users’ accounts, view sensitive files, modify other users’ data, change access rights, etc.
---

## Summary

A5-2017-Broken Access Control-This is caused mainly due to poor configuration of Access Control Rules or the complete absence of the same. If a site or app is not following ACL, authenticated as well as unauthenticated users will be able to access the resource that are only supposed to be accessed by a set of admin users. This injection can be prevented either by securing the code in server side with proper rules and ensuring the APIs requests are authorized as well. 
Some exploits that has been out in the public usually starts by string replacement on the SQL queries so that the attacker gets access to page that is not intended to be viewed by them. Sometimes even if the WebUI is secure, if the API requests are floating around with full access attackers can use the same to gain access and execute CRUD operation on the data.