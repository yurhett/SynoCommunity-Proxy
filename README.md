# SynoCommunity-Proxy
A cloudflare workers proxy for SynoCommunity, especially for Chinese users. 

This project is a compiled copy of [reflare](https://github.com/xiaoyang-sde/reflare).

## Explanation：

For well-known reasons, China has a very poor internet connection to foreign countries. This is very unfriendly to users of DSM located in China. This project is to solve the problem of connecting to SynoCommunity in places with bad network.

## Installation

1. Copy the content of [index.ts](https://github.com/yurhett/SynoCommunity-Proxy/blob/main/index.ts) to CloudFlare Workers.

2. Fill in <YOUR DOMAIN>:

   ```typescript
     const replace_dict = {
       'packages.synocommunity.com': '<YOUR DOMAIN>',
     }
   ```

3. Enjoy!

## Acknowledgement

@[xiaoyang-sde](https://github.com/xiaoyang-sde)‘s  [reflare](https://github.com/xiaoyang-sde/reflare)
@[SynoCommunity](https://github.com/SynoCommunity)'s [spkrepo](https://github.com/SynoCommunity/spkrepo)

