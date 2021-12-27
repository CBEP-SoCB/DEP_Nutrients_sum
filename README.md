# DEP_nutrients

<img 
    src="https://www.cascobayestuary.org/wp-content/uploads/2014/04/logo_sm.jpg"
    style="position:absolute;top:10px;right:50px;" />
    
Analysis of data from Maine DEP on nutrients, especially nitrogen, in Casco 
Bay, Maine

# Introduction
Maine's Department ogf Environmental Protection has been collecting data on
water quality in Casco Bay for many years.  Much of the agency's interest
focuses on nutrients and related water quality issues because of the direct
connection between nutrient levels and wastewater treatment discharges, and thus
discharge permit limits.  DEP sampling tends to be episodic, driven by
short-term interest in addressing specific questions, but the agency has
invested significant resources in understanding conditions in Casco Bay over the
past few years.

Data included here are derived from multiple studies, conducted over many years.
Because studies were undertaken for a variety of purposes by different people,
methods vary.  Data was provided to CBEP in fully QA/QC'd form, but we conducted
our own review, and dropped some data or samples that we di not trust.  Details
are omitted here, but are available in a companion 
[GitHub repository](https://github.com/CBEP-SoCB-Details/DEP_Nutrients.git).

Data should be interpreted with the understanding that it is
drawn from multiple studies, using sometimes different methods.  

# Statement of Purpose
CBEP is committed to the ideal of open science.  Our State of the Bay data
archives ensure the science underlying the 2020/2021 State of Casco Bay report
is documented and reproducible by others. The purpose of these archives is to
release  data and data analysis code whenever possible to allow others to
review, critique, learn from, and build upon CBEP science.

# Archive Structure
CBEP 2020/2021 State of the Bay data analysis summaries contain a selection of 
data,  data analysis code, and visualization code as used to produce 
results shared via our most recent State of Casco Bay report. Usually, these
archives are organized into two or three folders, including the following:

- `Data`  folder.  Contains data in simplified or derived form as used in our
data  analysis.  Associated metadata is contained in related Markdown documents,
usually `DATA_SOURCES.md` and `DATA_NOTES.md`.

- Analysis.  Contains one or more R Notebooks proceeding through the principal
data analysis steps that underpin SoCB reporting. To simplify the archives,
much preliminary analysis, and many analysis "dead ends" have been omitted. 

- Graphics.  Contains R Notebooks stepping through development of graphics, and
also copies of resulting graphics, usually in \*.png and \*.pdf formats.  These
graphics may differ from graphics as they appear in final State of the Bay
graphical layouts. Again, most draft versions of graphics have been omitted for 
clarity.

# Summary of Data Sources
All data was provided to CBEP by