---
title: A1-Injection
date: 1624016976
description: Injection flaws, such as SQL, NoSQL, OS, and LDAP injection, occur when untrusted data is sent to an interpreter as part of a command or query. The attacker’s hostile data can trick the interpreter into executing unintended commands or accessing data without proper authorization.
---

## Summary

A1:2017-Injection can target every source of data like environment variables, parameters, external and internal web serives. Injection vulnerabilities are often found in SQL, LDAP, XPath or NoSQL queries, OS commands,... This can result in data loss, corruption, or disclosure to unauthorized parites,... Application can be vulnerable to attack when user-supllied data is not validated, filter or sanitized; dynamic queries or non-parameterized calls without context-aware escaping are used directly in the interpreter; hostile data is used within object-relational mapping (ORM) search parameters or is directly used or concatenated. This can be prevent by using a safe API or migrate to se Pbject Relational Mapping Tools(ORMS).