# web-secruity-week7

1. Authenticated Cross-Site Scripting (XSS) via Media File Metadata
Summary:
  Vulnerability types: XSS
  Tested in version: 4.0
  Fixed in version: 4.1.16

GIF Walkthrough: 

![some alt tag](https://media.giphy.com/media/3ohs7QP1YYZVFeTGY8/giphy.gif)

Steps to recreate:

  You must give javascript code as the name of the file. When the Administrator uploads it to wordpress it initiates a stored xss attack. If you know the url of the image you can then share the link with others who will get affected as well.
Affected source code: https://github.com/WordPress/WordPress/commit/28f838ca3ee205b6f39cd2bf23eb4e5f52796bd7

2. Genericons Cross-Site Scripting (XSS)

Summary:
  Vulnerability types: XSS
  Tested in version: 4.0
  Fixed in version: 4.1.5
  
GIF Walkthrough: 

![some alt tag](https://media.giphy.com/media/xUOxfpDjW0kGgjAsRG/giphy.gif)

Steps to recreate:

This vulnerability is not on wordpress itself but an example package called "Genericons". So by using the url to this file You can create DOM based XSS attacks. Since the actions take place on each indivual browser instead of attacking wordpress page directly, it makes it hard for a server to prevent this attack. As long you can entice a user to click you can exploit the user.

Affected source code: https://codex.wordpress.org/Version_4.2.2

3. XSS-Comment
Summary: 

  Vulnerability: XSS
  Tested in version: 4.0
  Fixed in version: 

GIF Walkthrough: 

![some alt tag](https://media.giphy.com/media/xUOxf1XOSnRvK2jk2I/giphy.gif)




