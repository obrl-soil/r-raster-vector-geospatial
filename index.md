---
layout: lesson
root: .

maintainers:
- Leah Wasser
- Joseph Stachelek
- Tyson Swetnam
- Lauren O'Brien
- Janani Selvaraj
- Lachlan Deer
- Chris Prener
- Juan Fung
---

**Lesson Authors:** Leah A. Wasser, Megan A. Jones, Zack Brym, Kristina Riemer, Jason Williams, Jeff Hollister,  Mike Smorul, Joseph Stachelek

**Lesson Maintainers:** {{ page.maintainers | join: ', ' }}

The episodes in this lesson cover how to open, work with and plot vector and raster-format spatial data in R. Additional topics include working with spatial metadata (extent and coordinate reference systems), reprojecting spatial data, and working with raster time series data.

> ## Prerequisites
> Data Carpentry’s teaching is hands-on, so participants are encouraged to use 
> their own computers to ensure the proper setup of tools for an efficient 
> workflow. To most effectively use these materials, please make sure to download 
> the data and install everything before working through this lesson. 
> 
> ### R Skill Level
> This lesson assumes you have some knowledge of `R`. If you've never used `R` before, or need
> a refresher, start with our [Introduction to R for Geospatial Data](http://www.datacarpentry.org/r-intro-geospatial/) lesson.
>
> ### Geospatial Skill Level
> This lesson assumes you have some knowledge of geospatial data types and common file formats. If you
> have never worked with geospatial data before, or need a refresher, start with our [Geospatial Project Organization and Management](http://www.datacarpentry.org/organization-geospatial/) lesson.
>
> ### Install Software
> For installation instructions, see the [workshop homepage](http://www.datacarpentry.org/geospatial-workshop/setup/).
>
> ### Download Data
>
> * [airborne remote sensing data](https://ndownloader.figshare.com/files/3701578)
> * [site layout shapefiles](https://ndownloader.figshare.com/files/3708751)
>
> ### Setup RStudio Project
>
> Make sure you have set up a RStudio project for this lesson, as described in the <a href="{{ site.baseurl }}/setup/" target="_blank">setup instructions</a>.
>
> If you don't have an RStudio project, you will need to manually set the working directory with `setwd([your-directory-name])` so R can find the data files to load.
{: .prereq}
