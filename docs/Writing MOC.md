```dataview
table
file.size as "Size" from #randomThought 
where file.name != "Template, Random Memory"
sort file.size desc
```