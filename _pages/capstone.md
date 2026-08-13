---
permalink: /capstone/
title: "Capstone Connection"
author_profile: true
---

<!--
  ============================================================================
  SECTION 4: CAPSTONE CONNECTION  (20 points)  |  Suggested length: 200–300 words
  ============================================================================
  A concise, professional summary of how you applied bioinformatics to your
  capstone project. This draws from your Assignment 2 work — it is a
  professional-context summary, NOT a repeat of the assignment.

  INCLUDE:
    - A 2–4 sentence description of your capstone project (assume a general
      audience who is not in your program)
    - The bioinformatics tool, dataset, or method you applied in Assignment 2,
      and why it was relevant
    - What you found or produced, described in plain language
    - 1–2 sentences on how this bioinformatics component strengthened your capstone
    - (Optional) embedded images or output figures — see the guide for how to
      add an image

  HOW TO EDIT:
    - Replace the placeholder text below with your own.
    - Delete these grey instruction notes before you submit.
  ============================================================================
-->

## My Capstone Project

Heavy-metal contamination from industrial runoff, ore mining/ processing, spills/ dumping, and agricultural land treatments presents long-term risks to environmental and human health. Metals such as lead (Pb), nickel (Ni), and zinc (Zn) can accumulate in soils and often require costly monitoring and remediation. Conventional detection methods are accurate but typically require specialized equipment and trained personnel. Aspergillus niger is a filamentous fungus capable of tolerating heavy-metal stress. Previous studies have reported reductions in fungal growth and colony diameter under exposure to Pb, Ni, and Zn. The aim is to make a cheap and available bioindicator of soil stress. 

## The Bioinformatics Component

The Excel file was converted to CSV, and using a custom R script, generated plot information to update data if more intermediate measurements were obtained. The plots compared diameter growth over time, with sections by sets of varied concentrations for each metal. Nickel was a primary focus for observing quality replicas.  A simple line graph, bar graph, and scatter plot were the focus to compare data visually.

Response: 
Initial fungal growth followed the expected inhibition-concentration trend, but this reversed as stressed fungi matured rapidly and produced spores. At higher concentrations, the diameter-to-concentration relationship became consistent again. Aspergillus niger responded measurably to exposure to Pb, Zn, and Ni. Nickel had the greatest impact on fungal growth among the metals tested. Increasing Nickel concentration resulted in a clear dose-dependent reduction in colony diameter. Complete growth inhibition was observed at the highest nickel concentration tested. Colony diameter measurements may provide a low-cost preliminary method for assessing heavy-metal stress.  

## Why It Strengthened My Capstone

The bioinformatics data enabled real-time updates to the quality plots from the Excel pages we prepared. The script is reproducible, so problems can be discovered step by step. What would have taken a very long time took only a moment to search up new information and to apply a new quality onto the plot without the use of complex ribbon or troubleshooting learning. Versions are easy to see for credibility, and RStudio recommends ways to improve the process.

<!--
  OPTIONAL — to embed an image or figure you produced:
  1. Upload the image file to the images/ folder in your repository.
  2. Add a line like this where you want it to appear (remove the leading
     grey-comment marks):

     ![Short description of the figure](/biot74000-portfolio/images/your-figure.png)

  Make sure the path matches your repository name.
-->
