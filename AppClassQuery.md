```dataview
TABLE
	parent as "Parent",
	liked AS "Liked",
	last-reviewed AS "Date"
FROM "AppSecTools/Products" 
	WHERE contains(class, link("{{title}}"))
SORT liked DESC

```