# Puppeteer
Be able to mirror one of the many powers that teachers have over you, but now, you can use it on yourself! By using some grey magic, I've created a website where you can trick your web filter extension into blocking any site of your choosing!

> [!WARNING]
> Blocksi Puppeteer only works when system (Blocksi) administration have dynamic proxy page detection enabled and if they haven't manually blocked the blocking token being used. **If you have any issues, create a GitHub issue** with a screenshot of what your screen shows when you test it.
>
> For some school districts, if you spam puppeteer on a site like Google, and every google search becomes temporarily blocked, it might get flagged to the system (Blocksi) administration team as a spam of false positive requests; they might disable their dynamic proxy detection and filtering because of such to avoid false positives, leading back to the issue in the above text.

> [!IMPORTANT]
> The current default proxy token host is broken, so you will have to find and use your own. The details on how to do that are listed below.

## How to use your own proxy token host:

**First, you need to check if your device has dynamic proxy page detection filter enabled:**

There are some proxy URLs that don't have the usual `blocklist`, `proxy avoidance` or `url filter` Blocksi response. 

If you stumble upon a block response of proxy page detected, you've hit a goldmine! That means two things:
1. Your school district has dynamic proxy filtering enabled
2. You can use that URL to puppeteer Blocksi

**Using the Puppeteer:**
1. Once you've found your URL which gives you the `proxy page detected` response, paste the URL which you used in the Proxy token host input, and type whichever URL you want to block in the primary host box.
2. Press compose URL, and boom. You have your puppeteer link.
<img width="436" height="393" alt="image" src="https://github.com/user-attachments/assets/15171da1-836f-41bb-ac22-181711540e6c" />
