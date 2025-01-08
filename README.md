# 3BB
**by Amanda Woolsey**

## Abstract
_“Dealing with extinction in this way- taking it seriously, not rushing to overcome it- might be the most important and ethical work of our time”_ - Thom Van Dooren, field philosopher

Undisputedly, we are living in a time of tremendous and unprecedented ecological loss. Various forms of life on earth are disappearing at a rate unheard of in human history, with a growing amount of evidence suggesting that we are in a period of mass biodiversity loss and extinction. This extinction event is marked by a series of environmental catastrophes that vary in acceleration, intensity, and impact, such as climate-change driven weather events wiping out an endemic island species, to habitat loss and fragmentation leading to the slow death of a once-common species. One such piece of supporting evidence is Rosenberg et al.'s widely cited 2019 paper _Decline of the North American avifauna_, estimating a net loss of nearly 3 billion birds since 2019. Anthropogenic causes of biodiversity loss are well documented, however, less present in this dialogue is the “landscape of damage we carry inside of us”; the collective sense of grief felt by humans in response to the deterioration of nature. 

“Extinction studies” arises from the multi-dimensional entanglement of ecological losses, with “hope, biodiversity loss, extinction, and grieving complexly intertwined through topological, temporal flows”. Central to this field of study is the understanding that extinction is a multispecies, biocultural phenomenon with cascading effects on humans and non-humans alike. Grounded in the tenets of extinction studies, “3BB” examines the power of a slowed approach to ecological mourning in the form of a data visualization representing 3 billion lost birds as stars in the sky. By engaging in slow ecological mourning through data storytelling and aesthetics, this piece seeks to demonstrate that a thoughtful engagement with grief in the context of biodiversity loss is not only insightful on its own, but ethically necessary to inform structural change to build a better world.

## Technical Specifications
This project was created in Jupyter Notebook using the open-source Python libraries Holoviews and Bokeh to create the interactive data visualization. To run the plot generation Jupyter Notebook code (finalcode.ipynb) in the "project_files" folder, HuggingFace must be installed in a Python virtual environment. 


## This repository contains:

*[docs](#docs): files for the deployed site
*[project_files](#project_files): supporting files for the project including:
  *[birdlossdataset.xlsx](birdlossdataset.xlsx): Excel file showing source data from Rosenberg et al. 2019
  *[determining_coordinates.xlsx](determining_coordinates.xlsx): Excel file showing determination of dummy X and Y coordinates for plotting
  *[finalcode.ipynb](finalcode.ipynb): Bokeh plot generation code
  *[plot_final.html}(plot_final.html): HTML file of generated plot from finalcode.ipynb
  *[plotting_process.ipynb](plotting_process.ipynb): Jupyter Notebook file showing function development and visualization process using Bokeh and Holoviews
  *[test_points.csv](test_points.csv): CSV with species name, assigned key, and dummy X and Y coordinates for plotting
