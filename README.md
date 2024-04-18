# Challenge: Ancient Tree Inventory (ATI) Analysis

## Instructions

This coding challenge is meant to evaluate how a software engineer specializing in data collection and processing approaches a problem and works through it. You must use Python, but can otherwise utilize any resources you would normally use to do your job (Google, Stack Overflow, documentation, etc.). The only disallowed action is looking up the exact problem (as applicable) and copy/pasting a solution. The challenge is intended to span 30-60 minutes, and the focus is not on whether you have a complete working solution in the time period, but instead on how you worked through the problem.

### Requirements

* Python

### Data

The data for this challenge is a collection of ancient trees located in the United Kingdom, and was retrieved from the Woodland Trust Open Data Portal here [https://opendata-woodlandtrust.hub.arcgis.com/datasets/cd7f5390ebde4312a53154432cf490b3/explore?showTable=true](https://opendata-woodlandtrust.hub.arcgis.com/datasets/cd7f5390ebde4312a53154432cf490b3/explore?showTable=true).

The dataset is provided in `.csv`, `sqlite`, and `.geojson` formats, but all three options contain the same data, so you can use the option of your choosing for the challenge.

## Challenge

### Part I

Part I of this challenge focuses on ingestion, processing, and enrichment of the provided data using Python. 

1. Ingest the ATI data into Python objects using whichever data format you prefer.
2. Output the key metrics about the data, including (but not necessarily limited to) the following:
   * Count/size
   * Number of fields
3. Normalize the data, including (but not necessarily limited to) the following:
   * Convert dates/times to ISO 8601 format (`YYYY-MM-DDThh:mm:ss`)
   * Convert numbers to floats with the correct number of decimal places (including trailing zeroes)
   * Convert comma-separated field values to lists of values.

### Part II

Part II of this challenge focuses on analysis and derivation of insights of the provided data using Python.

1. Output a list of all *unique* ancient tree species. 
2. Create histograms showing the humber of ancient trees per:
   * County
   * Country
3. Output what percentage of ancient trees are both alive *and* standing.
4. Determine which species of tree has the largest average girth.
