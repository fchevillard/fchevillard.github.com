---
layout: page
title: Introduction
tagline: Supporting tagline
---

## Before starting
<li>Most of the softwares you will use today are java-based tools. Please quickly check if java is correctly installed on your computer <a href="http://www.java.com/en/download/testjava.jsp" target="_blank">here</a>.</li>
<li>You might need a text editor along this tutorial to write down some stuffs...</li>
<br/>

## Background scenario
You just arrived in a very promising startup, <i>kolbinspiration</i>, specialized in the prediction <a href="http://en.wikipedia.org/wiki/In_silico" target="_blank"><i>in-silico</i></a> of small compounds bioactivities. This startup is known for its rigor and expertise in this field. The director is famous since he wrote the main algorithm of <i>molinspiration</i>, which is one of the most used software regarding the prediction of bioactivities.

## Your goal
You will be part of a project that aims to improve existing drugs. To do so, you will explore similar compounds of a given drug. The fundation of your work will be the <a href="http://www.molinspiration.com/docu/miscreen/druglikeness.html" target="_blank">bioactivity score</a> from <i>molinspiration</i>, which allows to predict on which target a compound is likely to bind. The aforementionned software distinguish 6 classes of drug target:

<table style="width: 100%;">
<tr>
<td><li>GPCR Ligand</li></td>
<td><li>Ion Channel Modulator</li></td>
<td><li>Kinase Inhibitor</li></td>
</tr>
<tr>
<td><li>Nuclear Receptor Ligand</li></td>
<td><li>Protease Inhibitor</li></td>
<td><li>Enzyme Inhibitor</li></td>
</tr>
</table>
<br/>

At the moment, 3 drugs are the main focus of <i>molinspiration</i>:
<li><b>Imitrex</b>: targets the <i>GPCRs</i>, used for the treatment of migrain headaches.</li>
<li><b>Norvasc</b>: targets the <i>Ion Channel Modulator</i>, used for the treatment of angina.</li>
<li><b>Glivec</b>: targets the <i>Kinase Inhibitor</i>, used for the treatment of multiple cancers.</li>
<br/>
<table>
<tr>
<td><img src="/img/gleevec.jpg" width="160" height="140"/></td>
<td><img src="/img/imitrex.jpg" width="160"/></td>
<td><img src="/img/norvasc.jpg" width="160" height="140"/></td>
</tr>
</table>
Using different chemoinformatics tools, such as similarity search, clustering, or the prediction of ADMET properties, you will chose a drug, explore similar compounds of this one and suggest up to 3 compounds that you think they might be better. Those compounds will be then studied closely by a team of pharmaceutic experts from <i>molinspiration</i> for a later improvement (or not)...

## General Guideline

Your project will be divided into three different parts:
<li><b><a href="/part1.html">Part 1 - Ligand preparation</a></b></li>
In this part you will familiarize yourself with the drug you want to improve. Drawing its structure, getting the SMILES code, the bioactivity score, ...

<li><b><a href="/part2.html">Part 2 - Datasets preparation</a></b></li>
Once you have the structure of the drugs, you will look for similar compounds into differente databases. There you will familiarize yourself with the notion of similarity, fingerprint, ...

<li><b><a href="/part3.html">Part 3 - Ligand Optimization</a></b></li>
Using the information within the different dataset, you will explore the similar compounds of your drug and suggest new compounds for pharmaceutical study, with the help of clustering and prediction of ADMET properties.

<a href="/part1.html">Let's jump to <b>Part 1</b></a>
<br/>
<br/>
