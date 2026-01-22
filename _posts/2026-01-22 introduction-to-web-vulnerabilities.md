---
title: Introduction to web Vulnerabilities
date: 2026-01-22 17:50:00
categories: [cybersecurity, web]
tags: [xss, sql-injection,csrf]
---
Web Valnerabilities and common entry points for attackers. In this topic I will explore **sql-injection**  and **xss** ---two of owasp top 10.

## SQL-injection
SQL Injection (SQLi) is a web vulnerability that arises in case the input by users is not appropriately handled and embedded in database queries. Attackers will have the ability to inject malicious SQL to either overcome authentication, scrape sensitive information, alter data, or destroy databases altogether. SQL injection is mostly aimed at login forms, search forms, URL parameters, and APIs and is mainly as a result of the lack of input validation and the utilization of parameterized queries.


## xss
Cross-Site scripting (XSS) vulnerability occurs when a Web application permits untrusted input to run as script code in a user browser. This allows an attacker to steal session cookies, steal user accounts, defame a web page, or send users to rogue sites. XSS usually gets its way in comment forms, comment boxes, user profiles, and search results, where applications do not encode or sanitize user provided information prior to display.



