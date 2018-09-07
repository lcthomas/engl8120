---
id: 135
title: Lab 4
date: 2015-12-26T18:19:26+00:00
author: lindsaythomas
layout: page
guid: http://lindsaythomas.net/engl8120/?page_id=135
ample_page_layout:
  - no_sidebar_full_width
---
<a href="http://lindsaythomas.net/engl8120/wp-content/uploads/sites/12/2015/12/Lab-4-ENGL-8120-S16.pdf" rel="">PDF version of this assignment</a>.

### **Lab 4: Topic Modeling**

Thanks to Alan Liu for the <a href="http://english197s2015.pbworks.com/w/page/93936740/Practicum%20Assignments#practicum5" target="_blank">original version</a> of this lab.

The goal of this lab is to experiment with both pre-packaged tools for topic modeling, and with the most popular topic modeling tool, MALLET.

#### 1: Topic Modeling with Pre-Packaged Tools

1.1 Experiment with David Mimno&#8217;s online <a href="http://mimno.infosci.cornell.edu/jsLDA/" target="_blank">In-Browser Topic Modeling</a>, which works with a pre-set document corpus consisting of State of the Union addresses.

1.2 Create a post on our course site for Lab 4 (categorize your post under &#8220;Lab 4&#8221;). Create two headings in your Lab 4 post (like I have with this page):

  * 1: Topic Modeling with Pre-Packaged Tools
  * 2: Topic Modeling with MALLET

1.3. Then download the <a href="https://code.google.com/p/topic-modeling-tool/" target="_blank">Topic Modeling Tool</a>, which is a Java-based implementation of the well-known MALLET topic modeling tool. Try it on the mini-corpus you collected for Lab 1 (or on a portion of that corpus). Include some souvenirs of your experiments in section 1 of your Lab 4 post. If you&#8217;re not sure what I mean by &#8220;souvenirs,&#8221; take a look at what students at UCSB in Alan Liu&#8217;s undergraduate digital methods class have done <a href="http://english197s2015studentwork.pbworks.com/w/browse/#view=ViewFolder&param=Practicum%205%20-%20Topic%20Modeling" target="_blank">here</a>.

1.4. You should try to explain/describe in your own words what each souvenir that you post means. For example, if you include a screenshot of a list of topics, you should try to explain, as concisely as possible, what this list represents/means/describes. These explanations/descriptions do not need to be long (1-3 sentences is fine); they should simply describe what is going on in each souvenir that you leave, in your own words. Make sure to save your post.

1.5. This step is meant to prepare you for working with MALLET (see next section), which requires you to work with the command line. Read and follow along with <a href="http://praxis.scholarslab.org/scratchpad/bash/" target="_blank">this basic command line tutorial</a> from the Praxis Lab at the University of Virginia.

#### 2: Topic Modeling with MALLET

For the rest of this lab, you will follow along with the excellent Programming Historian tutorial &#8220;<a href="http://programminghistorian.org/lessons/topic-modeling-and-mallet" target="_blank">Getting Started with Topic Modeling and MALLET&#8221;</a> by Shawn Graham, Scott Weingart and Ian Milligan.

2.1. Follow along with the Windows/Mac instructions (depending on which you use) in the tutorial for downloading and installing MALLET.

  * Mac users (this applies somewhat to Windows users as well, although it&#8217;s easier for Windows because mallet will be in your c: directory): You will need to be at least somewhat familiar with file path names and how to use them in the command line in order to use MALLET successfully. <a href="http://www.mactips.info/2011/11/how-to-read-and-write-a-filepath" target="_blank">Read through this information about absolute file paths</a> if you&#8217;re not familiar with the concept. I recommend you set up mallet in its own folder, named &#8220;mallet&#8221; and located in your /user/ directory. This will help you to follow along more easily with the tutorial. My username on my Mac is lindsaythomas, so the absolute file path for mallet on my machine looks like this: /Users/lindsaythomas/mallet (you do not have to include Macintosh HD as part of the file path). You will need to know this file path in order to import and export files in MALLET.
  * As you can see in the screenshot below, I&#8217;ve highlighted my mallet folder in Finder. This allows me to see its absolute file path because I&#8217;ve turned the &#8220;Show Path&#8221; feature on in Finder. To turn this feature on, open up a Finder window, then go to View > Show Path Bar.
  * <a href="http://lindsaythomas.net/engl8120/wp-content/uploads/sites/12/2015/12/mallet-filepath.png" rel="attachment wp-att-138"><img class=" wp-image-138 aligncenter" src="http://lindsaythomas.net/engl8120/wp-content/uploads/sites/12/2015/12/mallet-filepath-300x148.png" alt="mallet filepath" width="531" height="262" srcset="http://lindsaythomas.net/engl8120/wp-content/uploads/sites/12/2015/12/mallet-filepath-300x148.png 300w, http://lindsaythomas.net/engl8120/wp-content/uploads/sites/12/2015/12/mallet-filepath-768x378.png 768w, http://lindsaythomas.net/engl8120/wp-content/uploads/sites/12/2015/12/mallet-filepath-1024x504.png 1024w" sizes="(max-width: 531px) 100vw, 531px" /></a>In order to run mallet commands, you need to first navigate to your mallet folder via the terminal. You must be &#8220;in&#8221; your mallet folder in order to run mallet.

2.2. Create a folder on your desktop (or wherever you keep work for this course on your machine) and title it like this: YourLastName-Lab4. This is where you will keep souvenirs of your work on this lab to upload to our class Box drive once you&#8217;ve completed the lab.

2.3. Read and follow along with the rest of the <a href="http://programminghistorian.org/lessons/topic-modeling-and-mallet" target="_blank">Programming Historian MALLET tutorial</a>. Make sure to work through each step as it&#8217;s described in the tutorial (Except one: you DO NOT need to increase your heap space &#8212; described in the section &#8220;Issues with Big Data&#8221; &#8212; unless you get the error message described there). Take note of two things about the code windows provided in the tutorial: many of them have horizontal scroll bars; and you will need to include your specific file path in many of the commands. Please note that they are also organized by operating system. Mac users, remember that Macs use backslashes ( / ), not forward slashes ( \ ), in file paths. Mac users, remember also that MALLET commands on a Mac **must** begin with ./bin/mallet (for Windows machines, it&#8217;s bin\mallet).

2.4. Upload your own files into MALLET and produce your own topic model, based on the steps described in the Programming Historian tutorial. Use the mini-corpus you created for Lab 1 (or a portion of that corpus).

Save the following souvenirs in your Lab4 folder:

  * Your keys file (make sure to save it with a different file name so you can tell the tutorial_keys file apart from this  keys file)
  * Your composition file (again, make sure you can tell the tutorial_composition file apart from this composition file)

2.5. Upload your Lab4 folder to our class Box drive (upload it to the &#8220;Lab 4&#8221; folder).

2.6. Under section 2 of your Lab 4 post, write a report that begins to interpret the topic model you made in step 2.4 of this lab and that reflects on this interpretive process itself. Some questions you might consider as you compose your report include:

  * Which texts did you model for step 4 of section 2 this lab? How many topics did you choose to model? Why did you choose that number?
  * What challenges did you face in modeling your own corpus?
  * Which topics appear to be most coherent? Why are these topics coherent?
  * Which topics appear to be less coherent or are confusing at first glance?
  * What does topic modeling tell us about your corpus?
  * What does topic modeling _do_ for researchers in literary studies? Why might we want to do it? What kinds of questions does it allow us to answer?

You do not need to answer all of these questions in your post; focus on those about which you have the most to say. You do not need to have a central argument (although it’s fine if you have one). You should connect your reflections to course readings where appropriate.

<span style="line-height: 1.5;">Shoot for 500-750 words.</span>