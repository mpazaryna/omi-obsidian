---
aliases: Company Master List
tags: companies
date created: 2023-02-17
date modified: 2023-02-19
---

## Master List

- [[delcf]]
- [[ehave]]
- [[havlf]]

## Type: Companies Data table

```dataview  
table symbol as "Symbol", aliases as "Company"
from "10-companies"  
where type="company"
sort file.ctime desc  
```

## Tag: Software Data table

```dataview  
table symbol, aliases
from #software 
sort file.ctime desc  
```