---
title: "Status badges"
description: "Add a deploy status badge to repository READMEs, documentation, or a web page to show the status of a site's most recent production or branch deploy."
---

Status badges are visual representations of your site's status, served as image files you can add to repository READMEs, documentation, or any other web page.

The **deploy status badge** automatically updates to show the status of a site's most recent [production or branch deploy](/deploy/deploy-overview#definitions):

![badges indicating deployment statuses: success, building, canceled, or failed.](/images/monitor-sites-status-badges.png)

## Add status badges

Follow these steps to get a specific image URL for your site's status badge and add it to a repository README, your documentation, or any other web page.

1. In the Netlify UI, select a specific site, then go to 
### NavigationPath Component:

Project configuration > General > Status badges
.

2. Copy the automatically generated markdown snippet and paste it into your repository README or markdown source for any website.

3. Optionally, to create a status badge for a deployed branch, add the `?branch=` query parameter to the badge image URL. For example, if the branch name is `dev`, the image URL would end with `/deploy-status?branch=dev`.

4. Commit the changes to your README or deploy the website containing the markdown snippet.

When a user encounters the status badge in your README or website, the badge will reflect the current status of your site's most recent production or branch deploy. Selecting the status badge takes a user to your site's **Deploys** page.
