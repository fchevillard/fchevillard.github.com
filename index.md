---
layout: page
title: Introduction
tagline: Supporting tagline
---

## Background scenario
You just arrived in a very promising startup, <i>molinspiration</i>, specialized in the prediction <a href="http://en.wikipedia.org/wiki/In_silico"><i>in-silico</i></a> of small compounds bioactivities. This startup is known for its rigor and expertise in this field. The director is famous since he wrote the main algorithm of <i>molinspiration</i>, which is one of the most used software regarding the prediction of bioactivities.

## Your main goal
You will start from an existing drugs and try to improve its potency regarding its target. The criteria we will use as reference, is the <a href="http://www.molinspiration.com/docu/miscreen/druglikeness.html">bioactivity score</a> from molinspiration.
Nowadays, the drug targets can be separated in 6 classes:

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
<li><b>Imitrex</b>: target the GPCRs, used for the treatment of migrain headaches.</li>
<li><b>Norvasc</b>: target the Ion channel modulator, used for the treatment of angina.</li>
<li><b>Glivec</b>: target the Kinase Inhibitor, used for the treatment of multiple cancers.</li>
<br/>
<table>
<tr>
<td><img src="/img/gleevec.jpg" width="160" height="140"/></td>
<td><img src="/img/imitrex.jpg" width="160"/></td>
<td><img src="/img/norvasc.jpg" width="160" height="140"/></td>
</tr>
</table>
Using differente chemoinformatics tools, such as similarity search, clustering, or the prediction of ADMET properties, you will chose a drug and suggest up to 3 compounds that you think they might be better. Those compounds will be then studied closely by your a team of pharmaceutics experts from <i>molinspiration</i> for a later improvement (or not)...

## General Guideline

Your project will be divided into three different parts:
<li><b>Part 1 - Ligand preparation</b></li>
In this part you will familiarize yourself with the drug you want to improve. Drawing its structure, getting the SMILES code, the bioactivity score, ...

<li><b>Part 2 - Datasets preparation</b></li>
Once you have the structure of the drugs, you will look for similar compounds into differente databases. There you will familiarize yourself with the notion of similarity, fingerprint, ...
<li><b>Part 3 - Ligand Optimization</b></li>
Using the information within the different dataset, you will explore the similar compounds of your drug and suggest new compounds for pharmaceutical study, with the help of clustering and prediction of ADMET properties.
