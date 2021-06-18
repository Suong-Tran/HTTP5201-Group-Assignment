---
title: A2-Broken Authentication
date: 1624042000
description: Application functions related to authentication and session management are often implemented incorrectly, allowing attackers to compromise passwords, keys, or session tokens, or to exploit other implementation flaws to assume other users’ identities temporarily or permanently.
---

## Summary
A2-Broken Authentication will let attackers to have access to hundreds of millions of valid username and password combinations. The prevelence is widespread due to the design and implementation of most identity and access controls. With this vulnerability, attackers will only neeed to gain access to only a few accounts, or just the admin account to compromise the system. An application is vulnerable to this when they permit:
    automated attacks such as sredential stuffing
    brute force or other automated attacks,
    weak or well-known passowrd
    plain text or weakly hashed passwords
    Has missing/ineffective multi-factor authentication
    ...
Ways to prevent this are to implement multi-factor authentication or to not ship or deloy with any default credentials, specially for admin users. We can prevent it by implementing weak-password chekcs and align password legnth
