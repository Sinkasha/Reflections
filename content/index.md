---
title: Reflections Campaign
publish: true
---
# Reflections Campaign Index
[[Session Notes - Reflections|Session Notes]]
```dataviewjs
for (let group of dv.pages('-"Templates" and -"Session Notes - Reflections" and -"Bloo" and -"index.md" and -"Session Notes - Reflections.md"').groupBy(a => a.Type)) {
	dv.header(2, group.key);
	dv.table(["Name", "Blurb"], group.rows.sort(a => a.title).map(a => [a.file.link, a.blurb]))
}
```

## Random Stuff
There is political tension between Dagdra and Fusilla, and the people aren't happy with the fact that Fusilla is sticking with the status quo, complaining about the state, a gap in economics, Ashfall being rundown while Parli is a fancy and renovated city. The Hyritian Alliance trades with Fusilla anyways for the profit. 

Also the Holy State are assholes apparently. 

##### Notes
- Fish related economics at ports Half Moon and Trinity Bay