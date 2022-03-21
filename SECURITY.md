# Security Policy

## Supported Versions


截止2022年02月16日
simpleui支持的django版本如下： 4.xx
simpleui支持的python版本如下： 3.11.x

## Reporting a Vulnerability

POC
```
<iframe src="javascript:document.cookie"></iframe>
<iframe src="javascript:alert(docuemnt.cookie)"></iframe>
<iframe src="javascript:alert(docuemnt.domain)"></iframe>
```

The current vulnerability has occurred because Ueditor does not substitute specific words and special characters.
When using the editor, it is recommended to substitute specific words and special characters.


Impact
This vulnerability is capable of... 
If a URL parameter is sent as content that makes up the content of an HTML page or JavaScript can be used in a user input form, 
a malicious user (an attacker) can steal useful information, such as a user's or administrator's cookie or session value, 
and exploit other vulnerabilities and vulnerabilities. You can attack together.
