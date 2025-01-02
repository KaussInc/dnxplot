# Tutorial: Setting Up dnxplot on pihole 

Follow these steps to load an adlist, block specific domains, and add them as wildcards to the blacklist.

 (If you would rather not make a pi-hole, just use this 99.95.71.9)

---
## 1. Blocking goguardian
1. Dive into your hole
2. Navigate to the **Adlists** section.
3. Add the following URL as a new adlist: https://raw.githubusercontent.com/KaussInc/dnxplot/refs/heads/main/hosts
4. Save or apply changes to load the adlist.
you are done if you only want to block goguardian if you use blocksi look at step 2
---

## 2. Blocking Blocksi
1. Go to the **Domains** or **Blacklist** section of your adblocker.
2. Click RegEx filter
3. Add the following domains individually:
- `(\.|^)blocksi\.net$`
- `(\.|^)block\.si$`
4. Then click add to Blacklist
   
