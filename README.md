# Off Track 
_Exploring what's between ICESat-2 reference tracks_


## Introduction

ICESat-2 has done an amazing job measuring elevations on its reference tracks, but what if you're interested in someplace that isn't covered?  In this project, we'll use the tools developed to create the ICESat-2 gridded products to generate a custom gridded elevation-change product for your favorite location.  We'll work on developing techniques to use data from the SlideRule online processing service to make elevation and elevation-change maps, and will work on tuning parameters in the algorithm to match conditions for the locations we're mapping.


### Collaborators

If you're interested in helping with this project, please add your name and goal below, then put in a PR.

| Name | Personal goals | Can help with | Role |
| ------------- | ------------- | ------------- | ------------- |
| Michael Studinger | I am interested in this project for a number of reasons. Tracking ice divides is one. | Adding airborne data, in particular ATM | Helper |


### The problem

Provide a few sentences describing the problem are you going to explore. If this is a technical exploration of software or data science methods, explain why this work is important in a broader context and specific applications of this work.

## Data and Methods

### Data

We'll get data from SlideRule, with the option to get additional DEM data from the Polar Geospatial Center's REMA and ArcticDEM arcives.


### Proposed methods/tools

One of the goals of this project is to make the tools that generate ATL14/15 more accessible to the community.  This includes the code in the main ATL14/15 repository, and the code in the more general-purpose LSsurf repository

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
