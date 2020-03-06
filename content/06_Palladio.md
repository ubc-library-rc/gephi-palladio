---
layout: default
title: Let’s try a Dataset in Palladio (Hands-on activity)
nav_order: 6
parent: Outline
published: true
---

# Palladio

[Palladio](palladio.designhumanities.org), developed by Stanford’s Humanities + Design Lab, is a web-based visualization tool for complex humanities data. Think of Palladio as a sort of Swiss Army knife for humanities data. It’s one package that includes a number of tools, each of which allows you to get a different angle on the same data.

Palladio is relatively new and still under active development which means that you will almost certainly encounter bugs! Still, it’s a very useful tool for getting a handle on a complicated dataset.


### Go to [Palladio](https://hdlab.stanford.edu/palladio/) and click on Start.

![Palladio step 1](palladio-start.png)

Download the <a href="/gephi-palladio/blob/master/Cushman-Collection.csv" download>Cushman-Collection.csv</a> file to your computer. Click on its icon and drag the file directly onto the blank box that appears under the words Load CSV or spreadsheet. Then press Load.


![Palladio step 2](palladio-1.png)


Network diagrams show the relationships among entities. To view your data as a network diagram, click on **Graph**. (Palladio is using the term "Graph" the way computer scientists do, to mean exclusively a network graph.)

![Palladio step 3](palladio-2.png)

In order to create a network diagram, you need to tell Palladio which two attributes of your data you want to explore. For Source, choose Genre 1; for Target, choose Genre 2. Now you can see which genres tend to co-occur in Cushman's photographs. You can click and drag the nodes (the circles) to explore your diagram.

![Palladio step 4](palladio-3.png)

To highlight one kind of node in order to distinguish between the two, click on the Highlight checkbox. To size nodes according to the number of objects they represent, click on the Size nodes checkbox.

![Palladio step 5](palladio-4.png)

Palladio doesn't save your data, but you can export your data model — the way you configured your data — and upload it again later. This will save you the trouble of configuring your dataset the next time you want to work with it.

	- To do this, click on **Download**. This will download a file with the extension .json. The next time you         use Palladio, you can upload this file (on the Palladio homepage) in order to open your project where       you left off.

![Palladio step 6](palladio-t.png)

## Bonus Activity

Try working with a version of the Les Mis dataset that we looked at in Gephi.

<a href="https://github.com/ubc-library-rc/gephi-palladio/blob/master/les-mis-for-palladio.csv" download>Download the les mis dataset for Palladio here.</a>
