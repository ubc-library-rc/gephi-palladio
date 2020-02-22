---
layout: default
title: Palladio
nav_order: 6
published: true
---

# Palladio

[Palladio](palladio.designhumanities.org), developed by Stanford’s Humanities + Design Lab, is a web-based visualization tool for complex humanities data. Think of Palladio as a sort of Swiss Army knife for humanities data. It’s one package that includes a number of tools, each of which allows you to get a different angle on the same data.

Palladio is relatively new and still under active development which means that you will almost certainly encounter bugs! Still, it’s a very useful tool for getting a handle on a complicated dataset.

## When Might Palladio be the Right Tool for You?

**You have structured data.**

   - Here, “structured data” means “data in a spreadsheet”: categorized, sorted, and stored in an Excel document or some other kind of spreadsheet application.

**You’re interested in time, space, and relationships.**

   - That’s where Palladio excels: showing you how various entities are connected across time and space.

**Your data has many attributes.**

- Palladio’s really good at helping you uncover relationships among disparate attributes over time and space for example, it can help you see that a diarist was especially interested in trees as he traveled through North Carolina, and especially interested in bats as he traveled through Arizona. Palladio allows you to drill down through your data using faceted browsing.

A Palladio project begins first with the tabular data you have on your computer. Once you’ve uploaded this data into the Palladio interface, you can then refine it, visualize, and save it back to your computer as a Palladio project.

### Go to [Palladio](https://hdlab.stanford.edu/palladio/) and click on Start.

![]({{site.baseurl}}/content/figures/wpid1798-media_1415771170331.png)

Download the **[Cushman-Collection.csv](https://github.com/ubc-library-rc/gephi-palladio/blob/master/Cushman-Collection.csv)** file to your computer. Click on its icon and drag the file directly onto the blank box that appears under the words Load CSV or spreadsheet. Then press Load.


![palladio1.png]({{site.baseurl}}/palladio1.png)


Network diagrams show the relationships among entities. To view your data as a network diagram, click on **Graph**. (Palladio is using the term "Graph" the way computer scientists do, to mean exclusively a network graph.)

![2.png]({{site.baseurl}}/content/2.png)

In order to create a network diagram, you need to tell Palladio which two attributes of your data you want to explore. For Source, choose Genre 1; for Target, choose Genre 2. Now you can see which genres tend to co-occur in Cushman's photographs. You can click and drag the nodes (the circles) to explore your diagram.

![3.png]({{site.baseurl}}/content/3.png)

To highlight one kind of node in order to distinguish between the two, click on the Highlight checkbox. To size nodes according to the number of objects they represent, click on the Size nodes checkbox.

![4.png]({{site.baseurl}}/content/4.png)

Palladio doesn't save your data, but you can export your data model — the way you configured your data — and upload it again later. This will save you the trouble of configuring your dataset the next time you want to work with it.

	- To do this, click on **Download**. This will download a file with the extension .json. The next time you         use Palladio, you can upload this file (on the Palladio homepage) in order to open your project where       you left off.



![t.png]({{site.baseurl}}/content/t.png)
