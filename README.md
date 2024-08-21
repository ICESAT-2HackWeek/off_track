# Off Track 
_Exploring what's between ICESat-2 reference tracks_


## Introduction

ICESat-2 has done an amazing job measuring elevations on its reference tracks, but what if you're interested in someplace that isn't covered?  In this project, we'll use the tools developed to create the ICESat-2 gridded products to generate a custom gridded elevation-change product for your favorite location.  We'll work on developing techniques to use data from the SlideRule online processing service to make elevation and elevation-change maps, and will work on tuning parameters in the algorithm to match conditions for the locations we're mapping.


### Collaborators

If you're interested in helping with this project, please add your name and goal below, then put in a PR.

| Name | Personal goals | Can help with | Role |
| ------------- | ------------- | ------------- | ------------- |
| Michael Studinger | I am interested in this project for a number of reasons. Tracking ice divides is one potential application. | Adding airborne data in between ICESat-2 tracks, in particular ATM. | Helper |
| Sierra Melton | I am interested in learning how to use ICESat-2 data and other altimetry data to study ice front elevation changes. | Outlet glacier knowledge | Participant |
| Ben Smith | I'd like to help users use my tools for elevation-change estimation, and learn what needs to be done to make them broadly useful | Data discovery, editing, and fitting | Project lead |
| Ayman Ahajjam | Learn to integrate cloud computing in my work process;Learn how to use ICESat-2 data products; Collaborate with others | Data science; Visualization, inSAR data from Alaska | Participant |   
| Ali Hossaini | I am interested in this project to develop my skills in machine learning workflows and hadnling elevation data such as ArcticDEM and ICESat-2. | PGC DEM Data aquistion, workflow development | Participant |



### The problem

ICESat-2 makes great measurements on its repeat tracks, but data can be sparse in between.  In this project, we're going to work on gridding techniques to fill in the gaps between ICESat-2 tracks.  We have participants interested in:

- Divide-scale elevation change in Greenland
- Ice-front-scale elevation change in Helheim glacier
- Permafrost change in Alaska

We'll try to find the best collection of techniques for each.


## Data and Methods

### Data

We'll get data from SlideRule, with the option to get additional DEM data from the Polar Geospatial Center's REMA and ArcticDEM arcives.


### Proposed methods/tools

One of the goals of this project is to make the tools that generate ATL14/15 more that are more useful to the community.  This includes the code in the main ATL14/15 repository, and the code in the more general-purpose LSsurf repository

-- https://github.com/SmithB/ATL1415

-- https://github.com/SmithB/LSsurf

Please see notebooks/make\_sim\_data.ipynb for a cartoon demo of the techniques and code we can explore.

<!--- # ### Additional resources or background reading

# Optional: links to manuscripts or technical documents providing background information, context, or other relevant information. --->

## Project goals and tasks

### Project goals

* Document grid-fitting algorithms
* Adapt grid-fitting scripts to SlideRule processing output
* Tune grid-fitting parameters to selected field locations

### Tasks

TBD


<!--- * Task 1 (all team members will learn to use GitHub)
* Task 2 (team members will use the scikit-learn python library)
  * Task 2a (assigned to team member A)
  * Task 2b (assigned to team member B)
* Task 3
* ... --->

## Project Results

TBD
