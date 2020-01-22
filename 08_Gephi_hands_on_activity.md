## Let’s try a Dataset in Gephi (Hands-on activity)

[GML file](https://gephi.org/datasets/lesmiserables.gml.zip). _Les Miserables: coappearance weighted network of characters in the novel Les Miserables_. D. E. Knuth, The Stanford GraphBase: A Platform for Combinatorial Computing, Addison-Wesley, Reading, MA (1993).

**download a network file**

download this zip file and unzip it on your computer.

-You should find the file miserables.gexf in it.

-Save it in a folder you will remember (or create a folder specially for this small project).

**description of the file / the network**

This file contains a network representing "who appears next to whom" in the 19th century novel Les Misérables by Victor Hugo[1].

A link between characters A and B means they appeared on the same page or paragraph in the novel.

The file name ends with ".gexf", which just means this is a text file where the network information is stored (name of the characters, their relations, etc.), following some conventions.

**open the network in Gephi**

open Gephi. On the Welcome screen that appears, click on Open Graph File

find miserables.gexf on your computer and open it

**read the report after opening a file**

A report window will open, giving you basic info on the network you opened:

_This tells us a few things:_

- the network comprises 74 characters, and they're all connected by 248 links.

- Links are undirected, meaning that if A is connected to B, then it is the same as B connected to A.

- The report also tells us the graph is not dynamic: it means there is no evolution or chronology, it won’t "move in time".

- Click on **OK** to see the graph in Gephi.

**Initial view**

project initial view

Figure 4. initial view when opening a graph
 
This is how the network appears in Gephi. Not very useful! Let’s examine what we have here.

**basic view of Gephi’s interface**
the 3 main screens in Gephi
Figure 5. the 3 main screens in Gephi
 

Gephi has 3 main screens:

Overview: where we can explore the graph visually

Data Laboratory: provides an "Excel" table view of the data in network

Preview: where we polish the visualization before exporting it as a pictue or pdf

What we see here is the Overview.

Filters and statistics panels in Gephi
Figure 6. Filters and statistics panels in Gephi
 

In the Overview, the graph is shown at the center. Around it, several panels help us fine tune the visualization.

"Filters", where we can hide different parts of the network under a variety of conditions

"Statistics", where we can compute metrics on the network

Appearance and layout panels in Gephi
Figure 7. Appearance and layout panels in Gephi
 

"Appearance", where we can change colors and sizes in interesting ways

"Layouts", where we can apply automated procedures to change the position of the network

3 groups of icons
Figure 8. 3 groups of icons
 

A series of icons to add / colorize nodes and links manually, by clicking on them

Options and sliders to change the size of all nodes, links, or labels

More options become visible if we click on this little arrow head pointing up
