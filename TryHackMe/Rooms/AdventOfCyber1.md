# Advent of Cyber 1 - Easy

1. [Inventory Management](#inventory-management)
2. [Arctic Forum](#arctic-forum)
3. [Evil Elf](#evil-elf)
4. [Training](#training)
5. [Ho-Ho-Hosint](#ho-ho-hosint)
6. [Data Elf-iltration](#data-elf-iltration)
7. [Skilling Up](#skilling-up)
8. [SUID Shenanigans](#suid-shenanigans)
9. [Requests](#requests)
10. [Metasploit-a-ho-ho-ho](#metasploit-a-ho-ho-ho)
11. [Elf Applications](#elf-applications)
12. [Elfcryption](#elfcryption)
13. [Accumulate](#accumulate)
14. [Unknown Storage](#unknown-storage)
15. [LFI](#lfi)
16. [File Confusion](#file-confusion)
17. [Hydra-ha-ha-haa](#hydra-ha-ha-haa)
18. [ELF JS](#elf-js)
19. [Commands](#commands)
20. [Cronjob Privilege Escalation](#cronjob-privilege-escalation)
21. [Reverse Elf-ineering](#reverse-elf-ineering)
22. [If Santa, Then Christmas](#if-santa-then-christmas)
23. [LapLANd (SQL Injection)](#lapland-sql-injection)
24. [Elf Stalk](#elf-stalk)

## Inventory Management

```markdown
This involves the usage of Developer tools and cookies.

First, we have to go to the page and register by creating a new account.

Then, after logging in using the same credentials, we get login access.

Using developer tools, we can view the cookie name 'authid'.

The cookie value can be decoded from Base64 to give us 'v4er9ll1!ss7' as the fixed part of the cookie.

Using this, we infer that the cookie value for authentication is the username appended by the fixed part, converted to Base64.

So we get mcinventory's login access; the item ordered was 'firewall'.
```

## Arctic Forum

```markdown
This challenge involves finding hidden directories and web enumeration.

Firstly, we have to use ffuf to find hidden directories. The /sysadmin directory, in this case, is the required one.

With the help of the comments in the page source, we get to know that the credentials are 'admin:defaultpass'.

Therefore, after logging in, we get the final flag 'eggnog'.
```

## Evil Elf

```shell
```

## Training

```shell
```

## Ho-Ho-Hosint

```shell
```

## Data Elf-iltration

```shell
```

## Skilling Up

```shell
```

## SUID Shenanigans

```shell
```

## Requests

```shell
```

## Metasploit-a-ho-ho-ho

```shell
```

## Elf Applications

```shell
```

## Elfcryption

```shell
```

## Accumulate

```shell
```

## Unknown Storage

```shell
```

## LFI

```shell
```

## File Confusion

```shell
```

## Hydra-ha-ha-haa

```shell
```

## ELF JS

```shell
```

## Commands

```shell
```

## Cronjob Privilege Escalation

```shell
```

## Reverse Elf-ineering

```shell
```

## If Santa, Then Christmas

```shell
```

## LapLANd (SQL Injection)

```shell
```

## Elf Stalk

```shell
```