---
Status: Active
Name: Hunter's Guild
Leader:
  - "[[4. NPCs & Organizations/NPCs/Vancent.md|Vancent]]"
Member:
  - "[[4. NPCs & Organizations/NPCs/Vancent.md|Vancent]]"
parent:
  - "[[4. NPCs & Organizations/Organizations/Kingdom of Fimore.md|Kingdom of Fimore]]"
Designation: Guild
Homebase:
  - "[[3. Locations/Bliurica/Fimore.md|Fimore]]"
---
	"It's DnD Monday my dudes." 
	- Dude

> [!infobox]
> # `=this.Name`
> ![[shady.jpg|cover hsmall]]
> ###### Basic Information [[orgs-db|Edit]]
> | Type | Stat |
> | ---- | ---- |
> |Designation|`=this.Designation`|
> | Leader | `=this.Leader` |
> | Homebase | `=this.Homebase` |
> | Status | `=this.Status` |
> ##### Relationships
> | Relation| Name |
> | ---- | ---- |
> |Part of|`=this.parent`|
> |Subsidiary | `=this.Subsidiary`| 
> |Partnership|`=this.Partnership`|
> |Enemies|`=this.Enemies`|
> ##### Members
> ```dataview
table Race, status as Status
where contains(Member, [[]])
sort file DESC

# `=this.Name`
text
## Members
```dataview
list without id 
Member
where file = this.file
```
## Holdings
## Story
## Notable Powers & Equipment
## Trivia

## Gallery
>[!cards]
>![[shady.jpg|banner]]
>[[shady.jpg|Sample Image]]
>

## Tags
#organization