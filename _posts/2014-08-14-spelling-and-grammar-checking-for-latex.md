---
layout: post
title: Spelling and Grammar Checking for Latex
date: '2014-08-14T09:18:00.000-07:00'
author: Glen B
tags:
- Latex
- Spelling
- Grammar
modified_time: '2014-08-14T09:32:04.852-07:00'
blogger_id: tag:blogger.com,1999:blog-2030049895335802245.post-7820913277942717329
blogger_orig_url: http://fracturedplane.blogspot.com/2014/08/spelling-and-grammar-checking-for-latex.html
---

One of the hurdles of starting to use Latex for document creation after getting used to Word is "is there spelling <b>AND</b> grammar checking?" I am happy to say there is a solution to this problem.<br /><br />There are a few Latex editors already that have support for spell checking but grammar checking is another issue all together. In this post I am going to give a quick guide on a great Latex editor and how you can add grammar checking as well.<br /><br /><a href="http://texstudio.sourceforge.net/" target="_blank">TexStudio</a> is becoming a very popular latex editor. It works across many platforms including Windows, Linux and Mac. TexStudio also has built in support for being able to compile and display the document being worked on.<br /><br /><a href="https://www.languagetool.org/" target="_blank">LangaugeTool</a> is a very interesting tool that can be used as stand alone grammar checker. It works as a server on your computer and any system can send HTTP requests to it to ask if there are any grammar issues.<br /><br />Here are the steps to get everything setup:<br /><br /><ol><li>Download the version of TexStudio that will work for your operating system.</li><li>Install TexStudio </li><li>Download LangaugeTool. It uses java so you will need Java available on you computer already.</li><li>Unpack Language tool into some directory</li><li>In TexStudio Configure TXS first, by using <b>Options &gt; Configure TexStudio… &gt; Grammar</b> like this:<br /><img alt="http://languagetool.wdfiles.com/local--files/checking-la-tex-with-languagetool/texstudio262.png" class="decoded" src="http://languagetool.wdfiles.com/local--files/checking-la-tex-with-languagetool/texstudio262.png" /></li><li>If TexStudio is configured to use inline grammar checking (which is the default, see <b>Options &gt; Configure TexStudio… &gt; Editor &gt; Inline Checking &gt; Grammar</b>), you should see grammar checks immediately:</li><li>After setting this up you should automatically start seeing grammer highlighting in your documents. </li></ol><br /><br /><br />As a side note you can easily grab more spelling dictionaries for TexStudio.<br /><br />Best of Luck. <br /><br />References<br /><ol><li>http://wiki.languagetool.org/checking-la-tex-with-languagetool#toc4</li></ol>