# Regex

For: To find attributes in html<br/>
Example: Hello There **<a><a href="/life">life</a></a>** How are you? **<a href="/work">Work</a>** I am chilling at work. **<a href="/about">about</a>** Dileep.<br/>
Regex: <\s*a[^>]*>(.*?)<\s*/\s*a><br/>
-------------------------------
