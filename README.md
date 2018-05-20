# AssignmentWeek7
Codepath/Facebook Course
# Project 7 - WordPress Pentesting

Time spent: **X** hours spent in total

> Objective: Find, analyze, recreate, and document **five vulnerabilities** affecting an old version of WordPress

## Pentesting Report

1. (Required) Privilege Escalation
  - [ ] Summary: 
    - Vulnerability types: User Authentication
    - Tested in version:4.1.2
    - Fixed in version: 4.4.1.8
  - [ ] GIF Walkthrough: 
  - [ ] Steps to recreate: 
        1. Reply to the comments. 
        2. Comment is sent to the approver for approval. 
        3. Log into the admin account. 
        4. Go to the comments section for viewing. 
        5. Approve comment. 
        6. Go back to the website. Refresh the page. 
        7. Other comments that weren't approved bypass approval moderation. 
  - [ ] Affected source code:
    - [Link 1]: Demo was shown in class. Recreated the same demo.  
1. (Required) Authenticated ShortCode Tags Cross Site Scripting
  - [ ] Summary: 
    - Vulnerability types:XSS
    - Tested in version:4.1.2
    - Fixed in version: 4.4.1.8
  - [ ] GIF Walkthrough: 
  - [ ] Steps to recreate: 
        1. Add a new post. 
        2. Enter the payload in the post that was created. ("TEST!!...")
        3. Refresh the page. 
        4. Hover over the link and you should receive an alert message. 
  - [ ] Affected source code:
    - [Link 1]:https://wpvulndb.com/vulnerabilities/8186
1.  Stored Cross Site Scripting
  - [ ] Summary: 
    - Vulnerability types:XSS
    - Tested in version:4.1.2
    - Fixed in version: 4.4.1.8
  - [ ] GIF Walkthrough: 
  - [ ] Steps to recreate: 
        1. Add a new Post. 
        2. Post the link in the fill text box. 
        3. Refresh the page. 
        4. Hover over the link and you should receive an alert message.("<a ref....") 
  - [ ] Affected source code:
    - [Link 1]:https://klikki.fi/adv/wordpress3.html

## Assets

None

## Resources

- [WordPress Source Browser](https://core.trac.wordpress.org/browser/)
- [WordPress Developer Reference](https://developer.wordpress.org/reference/)

GIFs created with [LiceCap](http://www.cockos.com/licecap/).

## Notes

There was one cross site scripting vulnerability I was having difficult with the code when publishing. 

## License

    Copyright [yyyy] [Alicia Silva]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
