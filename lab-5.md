---
id: 146
title: Lab 5
date: 2015-12-26T18:54:07+00:00
author: lindsaythomas
layout: page
guid: http://lindsaythomas.net/engl8120/?page_id=146
ample_page_layout:
  - no_sidebar_full_width
---
<a href="http://lindsaythomas.net/engl8120/wp-content/uploads/sites/12/2015/12/Lab-5-ENGL-8120-S16.pdf" rel="">PDF version of this assignment</a>.

### **Lab 5: Network Analysis**

Thanks to Alan Liu for the <a href="http://english197s2015.pbworks.com/w/page/93936740/Practicum%20Assignments#practicum6" target="_blank">original version</a> of this lab.

The goal of Lab 5 as a whole is to experiment with social network analysis using Gephi, a free and powerful network analysis tool. Section 1 of Lab 5 starts that process by having you think through network analysis conceptually.

#### 1: Manual Network Analysis

1.1. Read through sections 1.1 and 1.2 of Martin Grandjean&#8217;s excellent tutorial, <a href="http://www.martingrandjean.ch/gephi-introduction/" target="_blank">&#8220;GEPHI &#8212; Introduction to Network Analysis and Visualization.&#8221;</a> Explore/skim some of the examples Grandjean gives of network analysis.

1.2. Choose a short piece of literature (e.g., an act from a play, a chapter from a novel, a short story &#8212; perhaps something from the mini-corpus you collected in Lab 1) that can be analyzed conceptually in terms of relations between characters. For example, relations can include who talks to whom, who is on the scene at the same time, who is related by family to whom, etc. Based on that work of literature, make a table of the social relations and also a hand-drawn (or otherwise created) social graph that looks something like this (an example from the Grandjean tutorial):

<a href="http://lindsaythomas.net/engl8120/wp-content/uploads/sites/12/2015/12/GraphExample.png" rel="attachment wp-att-147"><img class=" wp-image-147 aligncenter" src="http://lindsaythomas.net/engl8120/wp-content/uploads/sites/12/2015/12/GraphExample-300x162.png" alt="social network graph example" width="357" height="193" srcset="http://lindsaythomas.net/engl8120/wp-content/uploads/sites/12/2015/12/GraphExample-300x162.png 300w, http://lindsaythomas.net/engl8120/wp-content/uploads/sites/12/2015/12/GraphExample-768x414.png 768w, http://lindsaythomas.net/engl8120/wp-content/uploads/sites/12/2015/12/GraphExample-1024x551.png 1024w, http://lindsaythomas.net/engl8120/wp-content/uploads/sites/12/2015/12/GraphExample.png 1300w" sizes="(max-width: 357px) 100vw, 357px" /></a>

Here the left column of the table (Nodes) records an ID number for a character, the name of a character, and then (option) a code for an attribute (e.g., 1 = male, 2 = female). The right column (Edges) records relations between the characters (e.g., 1,2 are the ID numbers showing that John talked to Carla). The graph is a visualization of the table, where characters are &#8220;nodes,&#8221; and relations are &#8220;edges&#8221; (or links between nodes). If you have recorded attributes such as gender, you can use that to color the nodes differently. Don&#8217;t worry about the fact that the nodes are different sizes in the example graph. That represents a weighting factor, e.g., how many relations a character has. You don&#8217;t need to worry about this for your hand-drawn graph.

1.3. Create a post on our course site for Lab 5 (categorize it under &#8220;Lab 5&#8221;). Create two headings in your Lab 5 post (like I have with this page):

  * 1: Manual Network Analysis
  * 2: Network Analysis with Gephi

1.4. Once you&#8217;ve created your graph and corresponding table, take a screenshot, scan, or photograph your work <span style="line-height: 1.5;">and upload your graph and table to that post. Include a brief explanation/description of your graph and table. Make sure to save your work.</span>

#### 2: Network Analysis with Gephi

For much of this lab, you will follow along with Martin Grandjean&#8217;s tutorial, <a href="http://www.martingrandjean.ch/gephi-introduction/" target="_blank">&#8220;GEPHI &#8212; Introduction to Network Analysis and Visualization.&#8221;</a>

Gephi is a difficult program to learn to use, and its interface is not exactly intuitive. I&#8217;m here to help you. Come to my office hours if you need help. The following additional resources may also be helpful as you complete this lab:

  * <a href="http://www.clementlevallois.net/gephi/tuto/en/gephi_cheat%20sheets_en.pdf" target="_blank">Gephi Cheatsheet</a> by Clement Levallois
  * <a href="http://www.kateto.net/wordpress/wp-content/uploads/2012/12/COMM645%20-%20Gephi%20Handout.pdf" target="_blank">Gephi Basics</a>

2.1. Review the different centrality measures discussed in section 1.1 Martin Grandjean&#8217;s tutorial, <a href="http://www.martingrandjean.ch/gephi-introduction/" target="_blank">&#8220;GEPHI &#8212; Introduction to Network Analysis and Visualization.&#8221;</a>

2.2. Read through and follow along with section 2.1 of the tutorial to install <a href="http://gephi.github.io/" target="_blank">Gephi</a> (&#8220;Downloading and installing the software&#8221;). This can be tricky, especially with Macs (because of a Java issue). Here are some additional resources to help you with installation:

  * Troubleshooting Gephi installation on Macs: <a href="http://clementlevallois.net/gephi/tuto/en/How%20to%20install%20Gephi%20on%20Mavericks%20or%20Yosemite.pdf" target="_blank">http://clementlevallois.net/gephi/tuto/en/How%20to%20install%20Gephi%20on%20Mavericks%20or%20Yosemite.pdf</a>
  * Troubleshooting Gephi installation on Windows: <a href="https://forum.gephi.org/viewtopic.php?f=3&t=3580&p=10712#p10712" target="_blank">https://forum.gephi.org/viewtopic.php?f=3&t=3580&p=10712#p10712</a>

2.3. Step 2.2 of the tutorial asks you to download three plugins. You will only need two to complete this lab: GeoLayout and Noverlap. If you receive an error message and cannot download and install these plugins automatically (i.e., using the Gephi Tools menu, the way Grandjean describes in the tutorial), you will need to download and install them manually. Here&#8217;s how to do that:

  * Go to <a href="https://marketplace.gephi.org/" target="_blank">Gephi marketplace</a> and search for each plugin: <a href="https://marketplace.gephi.org/plugin/geolayout/" target="_blank">GeoLayout</a>, <a href="https://marketplace.gephi.org/plugin/noverlap/" target="_blank">Noverlap</a>
  * Download each plugin from each plugin&#8217;s page, making sure to download the right plugin for your version of Gephi (probably 0.8.2).
  * Save the plugins to your desktop or somewhere else easily accessible.
  * In Gephi, go to Tools > Plugins > Downloaded.
  * Click on Add Plugins…, and select the files you have just downloaded. You can do both at once.
  * Click on Install, and follow the wizard.
  * This <a href="https://marketplace.gephi.org/faq/" target="_blank">FAQ page</a> also describes the manual plugin install process (under &#8220;To proceed manually&#8221;).

2.4. In step 2.3 of the tutorial, you are asked to download the sample datasets you will be using for the tutorial. You only need to download Dataset 1 for this lab. Download the two files associated with this dataset and save them to your desktop (or wherever you are saving work for this class on your computer). Depending on your browser, when you click on each file, it may open up in a new browser window. To save the file if this happens, go to File > Save Page As in your browser. Each file should save as a .csv (comma-separated values, can open in a spreadsheet) file.

2.5. Read and follow along with section 3 of the tutorial (Mapping Letters Over Europe) until the end of section 3.3. See step 2.7 for the souvenirs you need to save for your lab report. Some things to know as you complete the tutorial:

  * There are three tabs at the top of your Gephi window: Overview, Data Laboratory, Preview. Different parts of the tutorial take place in different tabs, but the first section (3.1) takes place in the Data Laboratory tab.
  * In section 3.2, you will apply different layouts to your graph. You do this by using the Layout panel in the Overview tab (below the Ranking panel). In order to set the parameters for the Force Atlas 2 layout, you may need to adjust the height of the Layout panel so that you can see the parameters.
  * In section 3.3, you are asked to sort the edges of your graph by weight. You do this by clicking on the Weight column once you&#8217;ve selected the Edges spreadsheet.
  * The Statistics panel (section 3.3) is located on the right side of your screen when you&#8217;re in the Overview tab.
  * In section 3.3., you will color the nodes of your graph according to the number of incoming edges (or links). Grandjean suggests that you color the nodes with a small number of connections with a dark color, and the nodes with a large number of connections with a light color. This makes the smaller nodes more visible. The default coloring scheme that Gephi offers is the opposite of this. To change this, click the small color palette icon to the right of the color slider, and choose Invert.

2.6. When you get to section 3.4 (Geographical Layout), only complete the network graph portion of that subsection. In other words, you do not need to download Inkscape and overlay your graph onto a map of Europe, unless you want to try it.

2.7. Create a folder on your desktop (or wherever you save work for this class) labeled &#8220;YourLastName-Lab5.&#8221; Save the following things as souvenirs for your lab report in this folder:

  * A pdf of your first graph from section 3.3 (the graph you complete after finishing the &#8220;Finalizing the graph&#8221; subsection). Save this graph like this: YourLastName-Graph1.pdf
  * A pdf of the second graph you create in section 3.3 (in the &#8220;Modularity&#8221; subsection). Take note of the resolution setting you used to run the graph. Save this graph like this: YourLastName-Graph2-ResolutionSetting.pdf
  * A pdf of the third graph you create in section 3.3 (in the &#8220;Betweenness Centrality&#8221; subsection). Save this graph like this: YourLastName-Graph3.pdf
  * A pdf of the graph you create in section 3.4. Again, as step 2.5 of this lab says, you do not have to overlay this graph on a map. Save this graph like this: YourLastName-Graph4.pdf

2.8. Next, open up the two .csv files you used for this lab (the ones provided in the tutorial). Try to understand the logic/format of these files. Then, using the tables you created for section 1 of this lab, create your own nodes and edges .csv files. The easiest way to do this is to create these files in a spreadsheet program, and then save the files as .csv. Finally, use your .csv files in Gephi to create a simple visualization. Export this visualization as a pdf file and save it in your Lab 5 folder like this: YourLastName-Graph5.pdf

2.9. Upload your entire Lab 5 folder to our class Box drive (in the Lab 5 folder).

2.10. Under section 2 of your Lab 5 post on our course site, write a report that reflects on what you&#8217;ve done in this lab and on network analysis more generally. Some questions you might consider as you write this report include:

  * What challenges did you face in completing this lab? How did you overcome these challenges? What did overcoming them teach you, if anything?
  * Compare the first four graphs you made for this lab (from the tutorial). What do these graphs depict? How are they different? What do these differences mean?
  * Considering the graph that you made (in step 6), what does this graph tell us about the literary work or portion of a work that you chose to graph?
  * More generally, what does network analysis _do_ for researchers in literary studies? Why might we want to do it? What kinds of questions does it allow us to answer?

You do not need to answer all of these questions in your post; focus on those about which you have the most to say. You do not need to have a central argument (although it’s fine if you have one). You should connect your reflections to course readings where appropriate.

Shoot for 500-750 words.