---
alias: "portfolio" 
alias: "parent company" 
---
# {{title}}
### Description


### Notes


### Products

```dataview
TABLE
	liked AS "Liked",
	last-reviewed AS "Date"
FROM "AppSecTools/Products" 
	WHERE contains(parent, link("{{title}}"))
SORT liked DESC

```