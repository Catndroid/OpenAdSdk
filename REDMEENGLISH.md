# OpenAdSdk

## This short article will help you quickly understand OpenAdSdk and master its usage.

## What is OpenAdSdk?
This is a lightweight Android advertising service made with Yu Language v3 (iApp, iYu, v3). It provides advertising push functions for users. With simple configuration, you can use it and greatly reduce the time to go live. It has built-in AdVideoFive, which can quickly display a 5-second advertisement for users, bringing a good experience for you and your employer.

## Its Application Scope
### 1. Static Processing
We can use the static processing method for advertising transmission. For example, there is a static `index.html` web configuration information in `/OpenAdSdk/file/assets/res/demo/`. With just a few simple modifications, you can quickly go live and display static content.
(**Warning**: Cross-border transmission may be involved)

### 2. Dynamic Processing
We can also use the dynamic processing method for advertising transmission. For example, upload the advertising page to a remote server, modify the `index.html` web configuration information in `/OpenAdSdk/file/assets/res/demo/` to display content from the remote server. With just a few simple modifications, you can quickly go live and display dynamic content.
(**Warning**: Cross-border transmission may be involved)

### 3. Backend Interaction
Based on the above two points.

### 4. Simplified Network Architecture
Advertising page → Request handshake → Request to display advertising content → Advertising image → (Advertising content is clicked) → Open browser to visit the employer's URL.
This approach simplifies many steps, not only reducing user traffic but also reducing the possibility of tampering (such as XSS cross-site attacks). However, this does not mean it is completely secure.

## Security and Open Source License
### 1. Except for the key advertising process, we will not conduct network transmission.
### 2. We strictly comply with the Apache License 2.0
Apache License 2.0: Similar to BSD, this license encourages code sharing and respects the original author's copyright. It allows modification and redistribution of the source code (whether as open-source or commercial software). The specific requirements include:
- Provide a copy of the Apache License to the users of the code.
- If you modify the code, you must state this in the modified files.
- In derivative code (including modified code and code derived from the source code), you must retain the original license, trademarks, patent notices, and other statements required by the original author.
- If the redistributed product includes a NOTICE file, you must include the Apache License in the NOTICE file, and you may add your own license to the NOTICE, but you must not modify the Apache License.

Welcome to my personal website: [https://www.1145117.xyz](https://www.1145117.xyz)  
Official Chinese TG: [https://t.me/minopenadsdk](https://t.me/minopenadsdk)  
Official English Telegram: [https://t.me/mjnopenadsdk](https://t.me/mjnopenadsdk)  

This README.md was written by Cat on February 11, 2025.
