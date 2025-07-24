---
title: "USCS Genome Browser: Understanding gene models"
teaching: 10
exercises: 2
---

:::::::::::::::::::::::::::::::::::::: questions 

- What tools and public datasets are available in the UCSC genome browser?

::::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::: objectives

  - Explore features of particular chromosomal regions
  - Investigate specific genes as well as collections of genes
  - Search for locations of sequences and markers
  - Retrieve annotation information for specific regions or genome-wide
  - View your own data in context of other annotations
  - Compare a region of one genome to genomes of other species

::::::::::::::::::::::::::::::::::::::::::::::::

## Gene model representation

![The typical structure of a gene as represented in the UCSC genome browser](episodes/fig/04UCSCGeneModels_gene_model.png)

## NTRK2

First we are going to familiarise ourselves with the gene model representation of the different transcripts of NTRK2.

#### 1. Navigate to the NTRK2 gene position in GRCh38 and view the gene models. 

You can navigate to a different region of the genome by typing in the position box.

::: tab

### Genomic location

If you know the specific location you are interested in, type in the location (e.g. **chr9:84,665,760-85,030,334**)

### Gene name

If you have a gene of interest, you can type in the gene name (e.g. **NTRK2**). 

Note the autocompleted suggestions that appear when you start typing. 
You can select from one of the suggestions or click `go` and select from a wider range of options.

:::

#### 2. Hide all tracks 

Select the `Hide all` button below the genome view.

#### 3. Turn on only the **Gencode V36** Genemodels in ‘full’ viewing mode

Select from the blue bar group labelled **Genes and Gene predictions*’.

#### 4. Turn on the **Conservation** track to ‘full’

Don’t forget to click `refresh`

#### 5. Zoom out and scroll across the whole gene

When you have navigated to the NTRK2 gene, zoom out until you can view all of the 
5’ UTRs and 3’ UTRs for all transcript variants for this gene. Then drag the view 
left and right to center (like in Google maps) or *drag and select* the region to center 
the gene in the Genome view.

![You should now see something like this](episodes/fig/04UCSCGeneModels_NTRK2_GENCODE_V36.png)

::: challenge

## CHALLENGE 1

Which strand is the gene encoded on / transcribed from? (+ or - strand)

:::

::: challenge

## CHALLENGE 2

Identify the exons, introns and UTRs.

Do regions of conservation only occur were there are coding regions?

:::

::: challenge

## CHALLENGE 3

How many different transcripts variants are there for this gene?

How do they differ?

:::

Select a coding region (full height boxes) towards the 3’UTR of the gene.


::: challenge

## CHALLENGE 4

Zoom in to the region until you can see the letters of the amino acid sequence.

Why are some amino acid boxes red or green?

:::

::: challenge

## CHALLENGE 5

Zoom in again until you can see each amino acid number.

Why do different transcripts have different amino acid numbers?

:::

::: callout

## NOTE

Note that one of the transcript names is in white text with a black background: 
this is the transcript you selected from the autocompleted list or the search results.

:::

#### 6. Change the **view settings** for the track 

Right click on the track grey bar 
in the left of the genome window to access view settings. 
Switch between `dense` ,  `squish` ,  `pack` ,  and  `full`  
to see how it changes the representation of the models.

#### 7. Reveal the Ensembl ID for each transcript

Go to the configuration page for the **GENCODE V36** track and change check the 
box to also reveal the **Ensembl ID** in the label.

The transcript names are now too long to fit on the screen. You can use the 
configuration page (like you did to chane the font size at the beginning of the workshop) 
and change the number of characters in the label so that you can see the entire transcript label.

### Check your understanding

::::::::::::::::::::: challenge 

## Question 1

Which transcript encodes the shortest amino acid sequence?

![](episodes/fig/04UCSCGeneModels_quizQ1)

::: solution 

## Answer

**ENST00000352327.5**

This transcript does not include one of the large coding regions and the coding region in the terminal exon is also slightly shorter.

:::

## Question 2

Which transcript has the longest 3'UTR?

![](episodes/fig/04UCSCGeneModels_quizQ2)

::: solution 

## Answer

**ENST00000396976.6**

Although the last two exons of ENST00000396972.2 are UTR rather than coding sequence, 
it is still not as long as the 3'UTR of ENST00000396976.6

:::

## Question 3

Which transcripts appear to encode the same protein product?

![](episodes/fig/04UCSCGeneModels_quizQ3)

::: solution 

## Answer

**ENST00000420986.6, ENST00000280352.13 and ENST00000393047.8**

Notice the height of the boxes for the first three exons: ENST00000532163.5 
appears to encode a different CDS from the other transcripts.

:::

## Question 4

Which transcript has the longest 5'UTR?

![](episodes/fig/04UCSCGeneModels_quizQ4)

::: solution 

## Answer

**ENST00000532681.5**

This transcript is encoded on the reverse strand.

:::

## Question 5

Which transcript has the longest CDS?

![](episodes/fig/04UCSCGeneModels_quizQ5)

::: solution 

## Answer

**ENST00000253801.7**

This transcript is encoded on the forward strand.

:::

## Question 6

Which transcript has the longest 5'UTR?

![](episodes/fig/04UCSCGeneModels_quizQ6)

::: solution 

## Answer

**ENST00000589334.5**

This transcript is encoded on the reverse strand.

:::
::::::::::::::::::::::::::::::::::::::::::::::::

## BDNF

::::::::::::::::::::::::::::::::::::: keypoints 

![The typical structure of a gene as represented in the UCSC genome browser](episodes/fig/04UCSCGeneModels_gene_model.png)

::::::::::::::::::::::::::::::::::::::::::::::::
