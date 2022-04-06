# SupplyFrame


## Supplyframe Fullstack Challenge 
Create a Node app that shows projects from the Hackaday.io API. This page should show many projects, their respective metadata, owner information, and have pagination. 

### Requirements 
Node.js 
Use Git (or Bitbucket) 
SASS 
Vanilla Javascript

### Suggestions 
Express 
EJS 
Nightwatch

### Setup 
Create an account at hackaday.io 
Log in to dev.hackaday.io and create an application 

### Objectives 
Project List Page 
- Render a page that shows a list or grid of projects (using GET /projects). 
- This page should be initially rendered server-side. 
- Display each project's metadata, including the owner. 
- Show a tooltip presenting the owner's metadata when hovering over a project owner's name (using the Hackaday API). 
- Tooltip data should be loaded dynamically, client-side. 
- Tooltip data should be loaded only once per browsing session. 

Implement pagination 
- When going to next/previous project pages, the page should not reload. 
- When going to next/previous project pages, the browser bar should display a unique/permanent URL. 
- Visiting the permanent URL should load the same page of projects as if the visitor navigated using the next/previous links. 

Project Detail Page 
- When a project is clicked, server-side render a page that shows the clicked project's metadata (using GET /projects/:id)
- Show "recommended projects" and/or "recommended users" by comparing the selected project's tags with tags of other projects/users. 

Implement Testing 
- Implement your favorite test framework/tool to check your work as you go - the level of detail is up to you. 

### More Suggestions 
- Commit often! 
- How you present the data matters. Your design can be simple/minimal, but we still consider design. 
- If using a CSS framework as a base, try only including the files you need. 
- If you tried something new doing this challenge, point it out!
