---
Name: Ashfangs Family
Leader:
  - "[[4. NPCs & Organizations/NPCs/Bruce.md|Bruce]]"
Member:
  - "[[4. NPCs & Organizations/NPCs/Bruce.md|Bruce]]"
  - "[[1. Player Characters/Shannon.md|Shannon]]"
Subsidiary:
  - "[[4. NPCs & Organizations/Organizations/Ashfang Steelworks.md|Ashfang Steelworks]]"
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
> |Ownership | `=this.Subsidiary`| 
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