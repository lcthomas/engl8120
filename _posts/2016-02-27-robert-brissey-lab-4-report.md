---
id: 289
title: 'Robert Brissey Lab #4 Report'
date: 2016-02-27T17:34:16+00:00
author: Rob
layout: post
guid: http://lindsaythomas.net/engl8120/?p=289
permalink: /2016/02/27/robert-brissey-lab-4-report/
ample_page_layout:
  - default_layout
categories:
  - Lab 4
---
Robert Brissey
  
Lab #4 Report
  
English 8120 – Dr. Lindsay Thomas
  
2/27/16

I chose to use the entirety of my corpus from Lab 1, quite intentionally. I wanted to see what types of topics could be produced by a rather diverse corpus, both in terms of the lengths of the texts and in the format (poetry, short story, novel) etc. To further complicate things, I ran two separate topic models, one with 20 topics, the second with 30 topics. My concern after running the first topic model was that I was seeing topics that clearly only pertained to one text. Therefore, any correlation between any other specific text would be skewed. Of course, these seemingly text-specific topics were mostly in the form of names. And of course, as the dominant texts, Dracula and The Count of Monte Cristo were the two most clearly indicated by any individual topic. By dominant, I mean that these two represent the longest of the texts, and therefore they seemed to receive favor in the form of more words taken from their texts, as compared to shorter texts like Walden or The Cask of Amontillado. I think that, for future use, texts of a similar length or cut into similar lengths would be useful for creating more meaningful topics, as per our discussion in class.
  
The numbers, or correlation averages as I see them, were quite interesting, despite the disparity in text length. Of course, one of the strongest correlations came in form of the metadata included by Project Gutenburg, represented by topic 3 primarily, but with perhaps some overflow reaching topic 7. Otherwise, the highest correlations came from topics 28, 25, and 16, as these had the highest numerical correlations (not including the metadata topic), and were seemingly the least text specific. By this I mean that these three topics specifically seemed to be generalized so as to be able to be applied to all the texts in a meaningful way. The lowest coefficients apply to topics 19, 24, and 11. Of these, only topic 11 seems to be textually specific, in that the words in the topic seem to be specific to Dracula. I decided to play with the numbers by calculating average correlation coefficients, with some rather odd results. Across all 30 topics, each text seemed to have an average of 0.033 correlation, which seemed unlikely, although I suppose if topic distribution is fair, this makes perfect sense.
  
My corpus was, after running the topic models, perhaps too ungainly. Or rather, my corpus was the equivalent of running an unbalanced load in an old washing machine. For future use, I would perhaps remove the longer texts, break everything into similarly sized chunks, or replace the shorter texts with texts of a comparable length to the longest ones. One of the few discernable attributes that I can gather based on the topics returned by Mallet is that my texts seem to be decidedly masculine, in that the most correlated topic features the word “man,” and as all of the texts are by a male writer, and the main characters of each seems to be a man, this is not surprising. So, based on that topic, I might be able to discern a certain level of sexism of the corpus, intentional or not. And to my understanding, that’s precisely how topic modelling might serve literary scholarship. We can find the topics that are, to human readers, inscrutable, and use that knowledge to generate claims based both on empirical evidence as well as the interpretation of the scholar at work.