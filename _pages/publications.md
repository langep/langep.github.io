---
layout: page
permalink: /publications/
title: publications
description: <a href="#books-and-chapters">[Books and Chapters]</a> <a href="#articles">[Articles]</a> <a href="#theses">[Theses]</a> <a href="#patents">[Patents]</a> <a href="#reports">[Reports]</a>
---

<h3 id="books-and-chapters" class="category">Books and Chapters</h3>
{% bibliography -f papers -q @incollection %}

<h3 id="articles" class="category">Articles</h3>
{% bibliography -f papers -q !@incollection %}

<h3 id="theses" class="category">Theses</h3>
{% bibliography -f theses %}

<h3 id="patents" class="category">Patents</h3>
{% bibliography -f patents %}

<h3 id="reports" class="category">Reports</h3>
{% bibliography -f misc %}