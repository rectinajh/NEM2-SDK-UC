---
layout: post
title:  "Profile"
permalink: /lessons/Usecase_Profile/
---


# Profile

- Language:TypeScript and JavaScript SDK 
- SDK-Version:v0.10.1-beta 
- MODEL:ACOUNT

## Prerequisites
- Finish the getting started section
- Text editor or IDE
- NEM2-SDK or CLI
- Description:profile management



## **1. Create - Configure an account**

- Description: Creates a new profile.
- Code sample:

```javascript
Options

-p, --privatekey <privatekey> - Private key
-n, --network <network>       - Network Type: MAIN_NET, TEST_NET, MIJIN, MIJIN_TEST
-u, --url <url>               - NEM2 Node URL. Example: http://localhost:3000
--profile <profile>           - (Optional) profile name, if not private key will be stored as default
```
### **How to use**

Bash code:

```
nem2-cli profile create -p 206CE7E4B16B48430FD2C216E4BB105564B21E21DEE196267B4B33C54F1023FC -n MIJIN_TEST -u http://localhost:3000
```


## 2.List   - Configure an account


- Description : Gets the list of stored accounts.
-  Code sample 

```javascript
nem2-cli profile list    
```
