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

## Non-SQL query tools

What are the different query tools avalable to query and manupulate non-SQL style data?

* [XPath](https://en.wikipedia.org/wiki/XPath) - XPath (XML Path Language) is a query language for selecting nodes from an XML document. [Using Xpath Exploration](https://www.distilled.net/blog/distilled/guide-to-google-docs-importxml/#chapter2)
* [LINQ](https://en.wikipedia.org/wiki/Language_Integrated_Query) - Language Integrated Query (LINQ, pronounced "link") is a Microsoft .NET Framework component that adds native data querying capabilities to .NET languages.

Dealing with these structures in Grasshopper can be difficult.  Many plugins have given this a try (Ghowl, Lunchbox, Elefront, GH Key/Value component, Visual Arq 2, Geometry Gym IFC, Archicad plugins). While each has some good ideas, the various plugins do not seem to work well together.  

What does it take to have a minimal Key Value command set?

Here are some ideas on a Hierarchical Value pair set in Grasshopper might look like:
