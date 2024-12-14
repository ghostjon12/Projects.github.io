---
layout: default
---

Text can be **bold**, _italic_, or ~~strikethrough~~.

[Link to another page](./another-page.html).

There should be whitespace between paragraphs.

There should be whitespace between paragraphs. We recommend including a README, or a file with information about your project.

# Cybersecurity Homelab

*  Successfully configured a homelab using Microsoft Azure equipped with a SIEM tool to monitor all security events.
*  To obtain traffic to monitor I implemented a VM with port 3389 left open to allow users to attempt to connect to the machine and provide data to analyze.
*  I also deployed rules to automate the escalation of certain events such as "Successful Login Attempts".
```js
SecurityEvent
| where Activity contains "success" and Account !contains "system"
```
# Controls Assessment

> This is a blockquote following a header.
>
> When something is important enough, you do it even if the odds are not in your favor.

# Compliance Checklist
