# Solving common bioinformatic challenges using GenomicRanges

# Instructor(s) name(s) and contact information

Michael Lawrence (michafla <at> gene <dot> com)

# Workshop Description

We will introduce the fundamental concepts underlying the
GenomicRanges package and related infrastructure. After a structured
introduction, we will follow a realistic workflow, along the way
exploring the central data structures, including GRanges and
SummarizedExperiment, and useful operations in the ranges
algebra. Topics will include data import/export, computing and
summarizing data on genomic features, overlap detection, integration
with reference annotations, scaling strategies, and
visualization. Students can follow along, and there will be plenty of
time for students to ask questions about how to apply the
infrastructure to their particular use case. Michael Lawrence
(Genentech).

## Pre-requisites

* Solid understanding of R
* Basic familiarity with GRanges objects
* Basic familiarity with packages like S4Vectors, IRanges,
  GenomicRanges, rtracklayer, etc.

## Workshop Participation

Describe how students will be expected to participate in the workshop.

## _R_ / _Bioconductor_ packages used

* S4Vectors
* IRanges
* GenomicRanges
* rtracklayer
* GenomicFeatures
* SummarizedExperiment
* VariantAnnotation
* GenomicAlignments

## Time outline

| Activity                     | Time |
|------------------------------|------|
| Intro slides                 | 30m  |
| Workflow(s)                  | 1hr  |
| Remaining questions          | 30m  |

# Workshop goals and objectives

## Learning goals

 * Understand how to apply the *Ranges infrastructure to real-world
   problems
 * Gain insight into the design principles of the infrastructure and
   how it was meant to be used

## Learning objectives

* Manipulate GRanges and related objects
* Use the ranges algebra to analyze genomic ranges
* Implement efficient workflows based on the *Ranges infrastructure
