---
layout: page
title: Introduction
tagline: Supporting tagline
---

## Before starting
<li>Most of the softwares you will use today are java-based tools. Please quickly check whether java is correctly installed on your computer <a href="http://www.java.com/en/download/testjava.jsp" target="_blank">here</a>.</li>
<li>You might need a text editor along this tutorial to write down some stuff...</li>
<br/>

## Background scenario
You just arrived at a very promising startup, <i>molinspiration</i>, specialized in the <a href="http://en.wikipedia.org/wiki/In_silico" target="_blank"><i>in silico</i></a> prediction of small-compound bioactivities. This startup is known for its rigor and expertise in this field. The director is famous since he wrote the main algorithm of <i>molinspiration</i>, which is one of the most used softwares in the field of prediction of bioactivities.

## Your goal
You will be part of a project that aims at improving existing drugs. To do so, you will use the fundamental theory in chemoinformatics which stipulates that <i>"small molecules with similar structure have similar functional (binding) properties"</i>. Therefore, you will explore compounds similar to a given drug. The foundation of your work will be the <a href="http://www.molinspiration.com/docu/miscreen/druglikeness.html" target="_blank">bioactivity score</a> from <i>molinspiration</i>, which allows you to predict the target which a given compound is likely to bind to. The aforementioned software distinguishes 6 classes of drug targets:

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
<li><b>Imitrex</b>: targets <i>GPCRs</i>; used for the treatment of migraine headaches.</li>
<li><b>Viracept</b>: targets <i>Proteases</i>; used for the treatment of HIV.</li>
<li><b>Glivec</b>: targets <i>Kinases</i>; used for the treatment of multiple cancers.</li>
<br/>
<table>
<tr>
<td><img src="/img/gleevec.jpg" width="160" height="140"/></td>
<td><img src="/img/imitrex.jpg" width="160"/></td>
<td><img src="/img/nelvir.jpg" width="160" height="140"/></td>
</tr>
</table>
Using different chemoinformatics tools, such as similarity searching, clustering, or the prediction of ADMET properties, you will choose a drug, explore similar compounds of this one and suggest up to 3 compounds that you think might be better. Those compounds will then be studied closely by a team of medicinal chemistry experts from <i>molinspiration</i> for later improvement (or not)...

## General Guideline

Your project will be divided into three different parts:
<li><b><a href="/part1.html">Part 1 - Ligand preparation</a></b></li>
In this part you will familiarize yourself with the drug you want to improve. Drawing its structure, getting the SMILES code, the bioactivity score, ...

<li><b><a href="/part2.html">Part 2 - Dataset preparation</a></b></li>
Once you have the structure of the drug, you will look for similar compounds in different databases. There you will familiarize yourself with the notion of similarity, fingerprint, ...

<li><b><a href="/part3.html">Part 3 - Ligand Optimization</a></b></li>
Using the information within the different datasets, you will explore similar compounds of your drug and suggest new compounds for pharmaceutical studies with the help of clustering and prediction of ADMET properties.

<a href="/part1.html">Let's jump to <b>Part 1</b></a>
<br/>
<br/>
