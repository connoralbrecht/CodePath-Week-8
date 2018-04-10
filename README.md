Project 8 - Pentesting Live Targets

Time spent: 8 hours spent in total

    Objective: Find, analyze, recreate, and document three vulnerabilities affecting an old version of WordPress

Pentesting Report

Blue:
  1. SQLi salesperson id URL
    -GIF Walkthrough:
  2. Session Hijacking copying and using ppersons session id to get their login access privledges
    -GIF Walkthrough:
Red:
  1. Username Enumeration: "Log in unsuccessful" only bolded for real users with wrong password
    -GIF Walkthrough:
  2. Cross-Site Scripting: Alert message submitted in Feedback on Contact us page
    -GIF Walkthrough:
Green:
  1. IDOR: Change Salesperson ID in URL to '11' which is not linked to on the salesperson page (fired)
    -GIF Walkthrough:
  2. CSRF: submit link to edit_salesperson.html script in Feedback that changes salesperson info with id=5 when clicked on by admin. 
    -GIF Walkthrough:
    
Assets

edit_salesperson.html link: 


GIFs created with LiceCap.
