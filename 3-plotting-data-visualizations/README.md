**Data Analysis Using Python: A Beginner’s Guide Featuring NYC Open Data**

Part 3: Plotting and Visualizations

*Mark Bauer*


Table of Contents
=================

   * [1. Importing Libraries](##1-Importing-Libraries)
       
       
   * [2. Merging Datasets](#2-Merging-Datasets)
       * [2.1 Building Footprints Dataset](##-21-Building-Footprints-Dataset)
       * [2.2 Pluto Dataset](##-22-Pluto-Dataset)
       
       
   * [3. Seaborn Library](#3-Seaborn-Library)
       * [3.1 Distribution Plots](#3-1-Distribution-Plots)
           * [3.1.1 Histograms](#3-1-1-Histograms)
           * [3.1.2 Kernel Density Estimate (KDE) Plot](#3-1-2-Kernel-Density-Estimate-%28KDE%29-Plot)
           * [3.1.3 Empirical Cumulative Distribution Functions (ECDF)](###3-1-3-Empirical-Cumulative-Distribution-Functions-%28ECDF%29)
           * [3.1.4 Distribution Plots onto a FacetGrid](#314-Distribution-Plots-onto-a-FacetGrid)
       * [3.2 Relational Plots](###-32-Relational-Plots)
           * [3.2.1 Line Plots](###-321-Line-Plots)
           * [3.2.2 Scatter Plot](###-322-Scatter-Plot)  
           * [3.2.3 Relational Plots onto a FacetGrid](###-323-Relational-Plots-onto-a-FacetGrid)
       * [3.3 Joint Grids](##-43-Joint-Grids) 
           * [3.3.1 Scatter Plot](###-331-Scatter-Plot)
           * [3.3.2 Hexagonal Bin Plots](###-332-Hexagonal-Bin-Plots)  
           * [3.3.3 Kernel Density Estimate (KDE) Plot](###-334-Kernel-Density-Estimate-%28KDE%29-Plot)
       * [3.4 Visualizing Pairwise Relationships in a Dataset](##-34-Visualizing-Pairwise-Relationships-in-a-Dataset)
       * [3.5 Heat Map](##-35-Heat-Map)
       * [3.6 Categorial Plots](##-36-Categorial-Plots)
           * [3.6.1 Count Plots](###361-Count-Plots)
           * [3.6.2 Bar Plots](###-362-Bar-Plots)
           * [3.6.3 Scatter Plots](###363-Scatter-Plots)
           * [3.6.4 Swarm Plots](###-364-Swarm-Plots)
           * [3.6.5 Box Plots](###-365-Box-Plots)
           * [3.6.6 Boxen Plots](###-366-Boxen-Plots)
           * [3.6.7 Violin Plots](###-367-Violin-Plots)
           * [3.6.8 Point Plots](###-368-Point-Plots)
           * [3.6.9 Facets](###369-Facets)  
   
   
   * [4. pandas and Matplotlib Libraries](#4-Pandas-and-Matplotlib-Libraries)
       * [4.1 Line Plot](##-41-Line-Plot)
       * [4.2 Bar Plot](##-42-Bar-Plot)
       * [4.3 Histogram](##-43-Histogram)
       * [4.4 Box Plot](##-44-Box-Plot)
       * [4.5 Kernel Density Estimate (KDE) Plot](##-45-Kernel-Density-Estimate-%28KDE%29-Plot)
       * [4.6 Area Plot](##-46-Area-Plot)
       * [4.7 Scatter Plot](##-47-Scatter-Plot)
       * [4.8 Hexagonal Bin Plot](##-48-Hexagonal-Bin-Plot)
       * [4.9 Pie Plot](##-49-Pie-Plot)
       
       
   * [5. Conclusion](#-4-Conclusion)


# 3. Seaborn Library

## 3.1 Distribution Plots

### 3.1.1 Histograms

![bar-plot-1](figures/3-1-1-a.png)

![bar-plot-3](figures/3-1-1-b.png)

![bar-plot-4](figures/3-1-1-c.png)

![bar-plot-1](figures/3-1-1-d.png)

![bar-plot-4](figures/3-1-1-e.png)

![bar-plot-3](figures/3-1-1-f.png)

![bar-plot-4](figures/3-1-1-g.png)

![bar-plot-1](figures/3-1-1-h.png)

![bar-plot-3](figures/3-1-1-i.png)

![bar-plot-4](figures/3-1-1-j.png)

![bar-plot-3](figures/3-1-1-k.png)

### 3.1.2 Kernel Density Estimate (KDE) Plot

![bar-plot-1](figures/3-1-2-a.png)

![bar-plot-3](figures/3-1-2-b.png)

![bar-plot-4](figures/3-1-2-c.png)

![bar-plot-1](figures/3-1-2-d.png)

![bar-plot-3](figures/3-1-2-e.png)

![bar-plot-4](figures/3-1-2-f.png)

![bar-plot-1](figures/3-1-2-g.png)

![bar-plot-3](figures/3-1-2-h.png)

![bar-plot-4](figures/3-1-2-i.png)

### 3.1.3 Empirical Cumulative Distribution Functions (ECDF)

![bar-plot-1](figures/3-1-3-a.png)

![bar-plot-3](figures/3-1-3-b.png)

![bar-plot-4](figures/3-1-3-c.png)

![bar-plot-1](figures/3-1-3-d.png)

![bar-plot-3](figures/3-1-3-e.png)

### 3.1.4 Distribution Plots onto a FacetGrid

![bar-plot-1](figures/3-1-4-a.png)

![bar-plot-3](figures/3-1-4-b.png)

![bar-plot-4](figures/3-1-4-c.png)

![bar-plot-1](figures/3-1-4-d.png)

![bar-plot-3](figures/3-1-4-e.png)

![bar-plot-4](figures/3-1-4-f.png)

![bar-plot-1](figures/3-1-4-g.png)

![bar-plot-3](figures/3-1-4-h.png)

![bar-plot-4](figures/3-1-4-i.png)

## 3.2 Relational Plots

### 3.2.1 Line Plots

![bar-plot-1](figures/3-2-1-a.png)

![bar-plot-3](figures/3-2-1-b.png)

![bar-plot-4](figures/3-2-1-c.png)

![bar-plot-1](figures/3-2-1-d.png)

![bar-plot-3](figures/3-2-1-e.png)

![bar-plot-4](figures/3-2-1-f.png)

![bar-plot-1](figures/3-2-1-g.png)

![bar-plot-3](figures/3-2-1-h.png)

![bar-plot-4](figures/3-2-1-i.png)

### 3.2.2 Scatter Plot

![bar-plot-1](figures/3-2-2-a.png)

![bar-plot-3](figures/3-2-2-b.png)

![bar-plot-4](figures/3-2-2-c.png)

![bar-plot-1](figures/3-2-2-d.png)

![bar-plot-3](figures/3-2-2-e.png)

![bar-plot-4](figures/3-2-2-f.png)

![bar-plot-1](figures/3-2-2-g.png)

![bar-plot-3](figures/3-2-2-h.png)

![bar-plot-4](figures/3-2-2-i.png)

![bar-plot-3](figures/3-2-2-j.png)

![bar-plot-4](figures/3-2-2-k.png)

![bar-plot-4](figures/3-2-2-l.png)

### 3.2.3 Relational Plots onto a FacetGrid

![bar-plot-3](figures/3-2-3-a.png)

![bar-plot-4](figures/3-2-3-b.png)

![bar-plot-4](figures/3-2-3-c.png)


## 3.3 Joint Grids

### 3.3.1 Scatter Plot

![bar-plot-3](figures/3-3-1-a.png)

### 3.3.2 Hexagonal Bin Plots

![bar-plot-3](figures/3-3-2-a.png)

### 3.3.3 Kernel Density Estimate (KDE) Plot

![bar-plot-3](figures/3-3-3-a.png)

![bar-plot-4](figures/3-3-3-b.png)

![bar-plot-4](figures/3-3-3-c.png)

![bar-plot-3](figures/3-3-3-d.png)

## 3.4 Visualizing Pairwise Relationships in a Dataset

![bar-plot-3](figures/3-4-a.png)

![bar-plot-4](figures/3-4-b.png)

## 3.5 Heat Map

![bar-plot-3](figures/3-5-a.png)

![bar-plot-4](figures/3-5-b.png)

## 3.6 Categorial Plots

### 3.6.1 Count Plots

![bar-plot-3](figures/3-6-1-a.png)

![bar-plot-4](figures/3-6-1-b.png)

![bar-plot-4](figures/3-6-1-c.png)

![bar-plot-3](figures/3-6-1-d.png)

![bar-plot-4](figures/3-6-1-e.png)

![bar-plot-4](figures/3-6-1-f.png)

![bar-plot-3](figures/3-6-1-g.png)

![bar-plot-4](figures/3-6-1-h.png)

![bar-plot-4](figures/3-6-1-i.png)

![bar-plot-3](figures/3-6-1-j.png)

![bar-plot-4](figures/3-6-1-k.png)

### 3.6.2 Bar Plots

![bar-plot-3](figures/3-6-2-a.png)

![bar-plot-4](figures/3-6-2-b.png)

![bar-plot-4](figures/3-6-2-c.png)

![bar-plot-3](figures/3-6-2-d.png)

![bar-plot-4](figures/3-6-2-e.png)

![bar-plot-4](figures/3-6-2-f.png)

![bar-plot-3](figures/3-6-2-g.png)

### 3.6.3 Scatter Plots

![bar-plot-3](figures/3-6-3-a.png)

![bar-plot-4](figures/3-6-3-b.png)

![bar-plot-4](figures/3-6-3-c.png)

### 3.6.4 Swarm Plots

![bar-plot-3](figures/3-6-4-a.png)

![bar-plot-4](figures/3-6-4-b.png)

![bar-plot-4](figures/3-6-4-c.png)

### 3.6.5 Box Plots

![bar-plot-3](figures/3-6-5-a.png)

![bar-plot-4](figures/3-6-5-b.png)

![bar-plot-4](figures/3-6-5-c.png)

### 3.6.6 Boxen Plots

![bar-plot-3](figures/3-6-6-a.png)

### 3.6.7 Violin Plots

![bar-plot-3](figures/3-6-7-a.png)

![bar-plot-4](figures/3-6-7-b.png)

![bar-plot-4](figures/3-6-7-c.png)

![bar-plot-3](figures/3-6-7-d.png)

![bar-plot-4](figures/3-6-7-e.png)

![bar-plot-4](figures/3-6-7-f.png)

![bar-plot-3](figures/3-6-7-g.png)

![bar-plot-4](figures/3-6-7-h.png)

![bar-plot-4](figures/3-6-7-i.png)

### 3.6.8 Point Plots

![bar-plot-3](figures/3-6-8-a.png)

![bar-plot-4](figures/3-6-8-b.png)

![bar-plot-4](figures/3-6-8-c.png)

### 3.6.9 Facets

![bar-plot-3](figures/3-6-9-a.png)

![bar-plot-4](figures/3-6-9-b.png)


# 4. pandas and Matplotlib Libraries

## 4.1 Line Plot

![bar-plot-3](figures/4-1-a.png)

![bar-plot-4](figures/4-1-b.png)

![bar-plot-4](figures/4-1-c.png)

![bar-plot-3](figures/4-1-d.png)

## 4.2 Bar Plot

![bar-plot-3](figures/4-2-a.png)

![bar-plot-4](figures/4-2-b.png)

![bar-plot-4](figures/4-2-c.png)

![bar-plot-3](figures/4-2-d.png)

![bar-plot-4](figures/4-2-e.png)

## 4.3 Histogram

![bar-plot-1](figures/4-3-a.png)

![bar-plot-3](figures/4-3-b.png)

![bar-plot-4](figures/4-3-c.png)

![bar-plot-3](figures/4-3-d.png)

![bar-plot-4](figures/4-3-e.png)

![bar-plot-4](figures/4-3-f.png)

## 4.4 Box Plot

![bar-plot-3](figures/4-4-a.png)

![bar-plot-4](figures/4-4-b.png)

![bar-plot-4](figures/4-4-c.png) 


## 4.5 Kernel Density Estimate (KDE) Plot

![kde-plot-1](figures/4-5-a.png)

## 4.6 Area Plot

![box-plot-1](figures/4-6-a.png)

![box-plot-3](figures/4-6-b.png)

![bar-plot-3](figures/4-6-c.png)

## 4.7 Scatter Plot

![scatter-plot-1](figures/4-7-a.png)

![scatter-plot-2](figures/4-7-b.png)

![scatter-plot-3](figures/4-7-c.png)

![scatter-plot-4](figures/4-7-d.png)

## 4.8 Hexagonal Bin Plot

![hexbin-plot-2](figures/4-8-a.png)

![hexbin-plot-3](figures/4-8-b.png)

![bar-plot-3](figures/4-8-c.png)

## 4.9 Pie Plot

![area-plot-1](figures/4-9-a.png)

![area-plot-3](figures/4-9-b.png)



