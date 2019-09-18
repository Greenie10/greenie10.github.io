---
layout: default
title: Part A&colon; Set up accounts in MongoDB Atlas and ZEIT Now
parent: Full stack app deployment with ZEIT Now
nav_order: 3
---

## Part A: Set up accounts in MongoDB Atlas and ZEIT Now

There will be a number of things you'll need to note down for later, eg, paths, names, connection strings etc. I recommend keeping a running note of these as you go along: all my brain is inside [Evernote](https://www.evernote.com/referral/Registration.action?sig=7a898c0bc86cb052472a52f0c75e8d731bef8d6de0f69d5d07464906496bfe6d&uid=58498943).

### Step 1: Sign up for free account with [MongoDB Atlas](cloud.mongodb.com)

- create and set up a free 'cluster'
- choose Cloud Provider & Region, I chose the Free Tier from Ireland
- choose Cluster Tier, I chose M0 Sandbox (the free forever tier)
- choose Cluster Name, I kept the suggested 'Cluster0'
- finally, click 'Create Cluster' button at the bottom of the page (currently this seems to take a few minutes to create), go and make a cuppa

### Step 2: Sign up for free [ZEIT Now](https://zeit.co) account

- provides very easy deployment process
- can use Github or Gitlab integration, or just an email
- profile settings, choose a \<username>
- Github integration setup - via 'Integrations' top menu
- in terminal, install the Now CLI with `npm install -g now` (any of your repositories will be able to deploy to 'now')
