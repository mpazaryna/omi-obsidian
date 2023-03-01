---
aliases: Dataviews
tags: 
date created: 2023-02-17
date modified: 2023-02-19
---

Examples of data views.  There are numerous sites and YouTube videos to review to get started and familiar.

- https://willcodefor.beer/posts/dataview

## Type: Companies

```dataview  
table symbol as "Symbol", aliases as "Company"
from "10-companies"  
where type="company"
sort file.ctime desc  
```

Type: Organizations

```dataview  
table aliases, url
from "30-orgs"  
where type="organization"
sort file.ctime desc  
```



## Tag: Software

```dataview  
table symbol, aliases
from #software 
sort file.ctime desc  
```