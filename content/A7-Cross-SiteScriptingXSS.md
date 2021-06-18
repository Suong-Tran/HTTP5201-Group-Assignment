---
title: A7-Cross Site Scripting XSS
description: XSS flaws occur whenever an application includes untrusted data in a new web page without proper validation or escaping, or updates an existing web page with user-supplied data using a browser API that can create HTML or JavaScript. XSS allows attackers to execute scripts in the victim’s browser which can hijack user sessions, deface web sites, or redirect the user to malicious sites.
---

## Summary

There are mainly 3 types of XSS that is used by attackers.
- <strong>Reflected XSS</strong>: Reflected attacks only require that the malicious script to be embedded into a link. The script is embedded into a link, and is executed everytime the same is clicked. This can avoided by vigilant users.
- <strong>Stored XSS</strong>: Stored XSS follows the attack method like Reflected, but the difference is that the attacker finds a website that has injection vulnerability. Attacker embeds his external code into the page and everytime a user accesses the page, the script will execute. This is because the external script is now part of the vulnerable website, and is rendered on the user's browser.
- <strong>DOM XSS</strong>: DOM-based XSS vulnerabilities usually arise when JavaScript takes data from an attacker-controllable source, such as the URL, and passes it to a sink that supports dynamic code execution, such as eval() or innerHTML.