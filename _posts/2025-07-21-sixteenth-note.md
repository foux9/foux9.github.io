---
layout: default
title: "|-- GOOGLE_DORK_LIST"
date: 2026-05-05
tags: [osint, recon, google-dorks]
---

# GOOGLE DORK LIST

---

## Open:

"first last" AND "state"  
"first last" AND "location"  - cities  
"first last" AND "location"  - counties  
"first last" AND "business/employer"  
"first last" AND "position/role"  
"first last" AND "username"  

("first last" AND "state" OR "first last" AND "location" OR "first last" AND "business/employer" OR "first last" AND "position/role" OR "first last" AND "username")

---

## Open Username:

"username"  
intext:"username"  
inurl:username  
"username" AND "location"  
"first last" AND "username"  

("username" OR intext:"username" OR inurl:username OR "username" AND "location" OR "first last" AND "username")

---

## Files & Docs:

filetype:pdf "first last"  
filetype:pdf "first last" AND "location" - city  
filetype:pdf "first last" AND "location" - state  
filetype:docx "first last" AND "location" - city  
filetype:docx "first last" AND "location" - state  
filetype:csv "first last" AND "location" - city  
filetype:csv "first last" AND "location" - state  

(filetype:pdf OR filetype:docx OR filetype:csv) "first last" AND "location"

---

## SM DORKS:

### Facebook:

site:facebook.com "first last"  
site:facebook.com "first" AND "last"  
site:facebook.com "first last" AND "location"  
site:facebook.com "username"  
site:facebook.com "first last" AND "business/employer"  
site:facebook.com "first last" AND "position/role"  

site:facebook.com ("first last" OR ("first" AND "last") OR "first last" AND "location" OR "username" OR "first last" AND "business/employer" OR "first last" AND "position/role")

---

### Instagram:

site:instagram.com "first last"  
site:instagram.com "first" AND "last"  
site:instagram.com "first last" AND "location"  
site:instagram.com "username"  
site:instagram.com "first last" AND "business/employer"  
site:instagram.com "first last" AND "position/role"  

site:instagram.com ("first last" OR ("first" AND "last") OR "first last" AND "location" OR "username" OR "first last" AND "business/employer" OR "first last" AND "position/role")

---

### X (Twitter):

site:x.com "first last"  
site:x.com "first" AND "last"  
site:x.com "first last" AND "location"  
site:x.com "username"  
site:x.com "first last" AND "business/employer"  
site:x.com "first last" AND "position/role"  

site:x.com ("first last" OR ("first" AND "last") OR "first last" AND "location" OR "username" OR "first last" AND "business/employer" OR "first last" AND "position/role")

---

### TikTok:

site:tiktok.com "first last"  
site:tiktok.com "first" AND "last"  
site:tiktok.com "first last" AND "location"  
site:tiktok.com "username"  
site:tiktok.com "first last" AND "business/employer"  
site:tiktok.com "first last" AND "position/role"  

site:tiktok.com ("first last" OR ("first" AND "last") OR "first last" AND "location" OR "username" OR "first last" AND "business/employer" OR "first last" AND "position/role")

---

### LinkedIn:

site:linkedin.com "first last"  
site:linkedin.com "first" AND "last"  
site:linkedin.com "first last" AND "location"  
site:linkedin.com "username"  
site:linkedin.com "first last" AND "business/employer"  
site:linkedin.com "first last" AND "position/role"  

site:linkedin.com ("first last" OR ("first" AND "last") OR "first last" AND "location" OR "username" OR "first last" AND "business/employer" OR "first last" AND "position/role")

---

### GitHub:

site:github.com "first last"  
site:github.com "first" AND "last"  
site:github.com "first last" AND "location"  
site:github.com "username"  
site:github.com "first last" AND "business/employer"  
site:github.com "first last" AND "position/role"  

site:github.com ("first last" OR ("first" AND "last") OR "first last" AND "location" OR "username" OR "first last" AND "business/employer" OR "first last" AND "position/role")

---

### Reddit:

site:reddit.com "first last"  
site:reddit.com "first" AND "last"  
site:reddit.com "first last" AND "location"  
site:reddit.com "username"  
site:reddit.com "first last" AND "business/employer"  
site:reddit.com "first last" AND "position/role"  

site:reddit.com ("first last" OR ("first" AND "last") OR "first last" AND "location" OR "username" OR "first last" AND "business/employer" OR "first last" AND "position/role")

---

### PicsArt:

site:picsart.com "first last"  
site:picsart.com "first" AND "last"  
site:picsart.com "first last" AND "location"  
site:picsart.com "username"  
site:picsart.com "first last" AND "business/employer"  
site:picsart.com "first last" AND "position/role"  

site:picsart.com ("first last" OR ("first" AND "last") OR "first last" AND "location" OR "username" OR "first last" AND "business/employer" OR "first last" AND "position/role")

---

### MeWe:

site:mewe.com "first last"  
site:mewe.com "first" AND "last"  
site:mewe.com "first last" AND "location"  
site:mewe.com "username"  
site:mewe.com "first last" AND "business/employer"  
site:mewe.com "first last" AND "position/role"  

site:mewe.com ("first last" OR ("first" AND "last") OR "first last" AND "location" OR "username" OR "first last" AND "business/employer" OR "first last" AND "position/role")

---

### Fiverr:

site:fiverr.com "first last"  
site:fiverr.com "first" AND "last"  
site:fiverr.com "first last" AND "location"  
site:fiverr.com "username"  
site:fiverr.com "first last" AND "business/employer"  
site:fiverr.com "first last" AND "position/role"  

site:fiverr.com ("first last" OR ("first" AND "last") OR "first last" AND "location" OR "username" OR "first last" AND "business/employer" OR "first last" AND "position/role")

---

### Linktree:

site:linktr.ee "first last"  
site:linktr.ee "first" AND "last"  
site:linktr.ee "first last" AND "location"  
site:linktr.ee "username"  
site:linktr.ee "first last" AND "business/employer"  
site:linktr.ee "first last" AND "position/role"  

site:linktr.ee ("first last" OR ("first" AND "last") OR "first last" AND "location" OR "username" OR "first last" AND "business/employer" OR "first last" AND "position/role")

---

### Truth Social:

site:truthsocial.com "first last"  
site:truthsocial.com "first" AND "last"  
site:truthsocial.com "first last" AND "location"  
site:truthsocial.com "username"  
site:truthsocial.com "first last" AND "business/employer"  
site:truthsocial.com "first last" AND "position/role"  

site:truthsocial.com ("first last" OR ("first" AND "last") OR "first last" AND "location" OR "username" OR "first last" AND "business/employer" OR "first last" AND "position/role")

---

### Goodreads:

site:goodreads.com "first last"  
site:goodreads.com "first" AND "last"  
site:goodreads.com "first last" AND "location"  
site:goodreads.com "username"  
site:goodreads.com "first last" AND "business/employer"  
site:goodreads.com "first last" AND "position/role"  

site:goodreads.com ("first last" OR ("first" AND "last") OR "first last" AND "location" OR "username" OR "first last" AND "business/employer" OR "first last" AND "position/role")

---

### Bluesky:

site:bsky.app "first last"  
site:bsky.app "first" AND "last"  
site:bsky.app "first last" AND "location"  
site:bsky.app "username"  
site:bsky.app "first last" AND "business/employer"  
site:bsky.app "first last" AND "position/role"  

site:bsky.app ("first last" OR ("first" AND "last") OR "first last" AND "location" OR "username" OR "first last" AND "business/employer" OR "first last" AND "position/role")

---

### Medium:

site:medium.com "first last"  
site:medium.com "first" AND "last"  
site:medium.com "first last" AND "location"  
site:medium.com "username"  
site:medium.com "first last" AND "business/employer"  
site:medium.com "first last" AND "position/role"  

site:medium.com ("first last" OR ("first" AND "last") OR "first last" AND "location" OR "username" OR "first last" AND "business/employer" OR "first last" AND "position/role")


