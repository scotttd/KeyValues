Non-SQL Data
=========

There seems to be a resurgence of non-sql data structures being used.  Whether this is HTML, XML, JSON, .Net Dictionaries and non-SQL databases (ie. Mongodb). While there are some variations between each of these formats, a main characteristic of these structures is the Hierarchical Key-Value structures:

```
<?xml version="1.0" encoding="UTF-8"?>
<menu meal="breakfast">
	<food>
		<name>Belgian Waffles</name>
		<price>$5.95</price>
		<description>Two of our famous Belgian Waffles with plenty of real maple syrup</description>
		<calories>650</calories>
	</food>
	<food>
		<name>Strawberry Belgian Waffles</name>
		<price>$7.95</price>
		<description>Light Belgian waffles covered with strawberries and whipped cream</description>
		<calories>900</calories>
	</food>
</menu>
```

Dealing with these structures in Grasshopper can be difficult.  Many plugins have given this a try (Ghowl, Lunchbox, Elefront, GH Key/Value component, Visual Arq 2, Geometry Gym IFC, Archicad plugins). While each has some good ideas, the various plugins do not seem to work well together.  

What does it take to have a minimal Key Value command set?

Here are some ideas on a Hierarchical Value pair set in Grasshopper might look like: