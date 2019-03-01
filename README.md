# Regex 1

<b>For</b>: To find attributes in html<br/>
<b>Example</b>: Hello There <
a href="/life">life</a> How are you? **<a href="/work">Work</a>** I am chilling at work. **<a href="/about">about</a>** Dileep.<br/>
<b>Regex</b>: <\s*a[^>]*>(.*?)<\s*/\s*a><br/>
