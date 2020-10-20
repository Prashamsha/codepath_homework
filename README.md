# codepath_homework
# Assignment 7-8: WordPress Pentesting 
Time spent- 24 hrs

Objective: Find, analyze, recreate, and document three vulnurabilities affecting an older versions of WordPress.

## Pentesting Report
1. USer vulnurability

- Summary:Checked logging in different username.

   - Vulnerability types: User enumeration.
   - Tested in version: 4.2 
    
GIF Walkthrough:
![username vulnerability](https://user-images.githubusercontent.com/65010114/96622362-77100180-12cf-11eb-8052-f45d583e3b8e.gif)


2. Authenticated Stored Cross-Site Scripting (XSS) in YouTube URL Embeds

- Summary: An authenticated user can perform a XSS attack by adding JavaScript to a Youtube URL in an embed tag when editing the content of a post. 

    - Vulnerability types: XXS
    - Tested in version: 4.2
    
GIF Walkthrough:
![Embeded link](https://user-images.githubusercontent.com/65010114/96622392-7d05e280-12cf-11eb-9d1b-3910f7e90030.gif)


3. Authenticated Stored Cross-Site Scripting (XSS)

- Summary: An authenticated user can make an attack by inserting HTML that contains malicious JavaScript into a WordPress page or post.

    - Vulnerability types: XXS
    - Tested in version: 4.2
    
GIF Walkthrough:
![XSS through caption](https://user-images.githubusercontent.com/65010114/96622402-80996980-12cf-11eb-81cb-428250903006.gif)
