# NC Clear Path: One-Pager for All Things Open 

As part of the [Datapalooza pitch competition](http://ncopenpass.com/blog/teams-are-selected-for-next-step-in-datapalooza-open-data-competition/) at [All Things Open](https://allthingsopen.org/), each selected team was required to fill out a one-page document providing an overview of the project and detailing the progress made since [Civic Camp](http://ncopenpass.com/blog/civic-camp-hackathon-concludes-with-open-data-competition-kickoff/).

## NC Clear Path One-Pager

**Who are we?**

We are a group of open-data advocates motivated by important civic applications formed at Civic Camp.

**What are we working on?**

NC Clear Path seeks to provide safe and accessible trip planning on pedestrian ways for those with limited mobility. The current scope includes gathering and generating sidewalk data to integrate with existing map resources and to combine the functionality of multiple existing open source projects. To achieve this goal, we are working to create a map and trip planner that would clearly show sidewalk and curb ramp information as well as advanced filters such as sidewalk steepness, barriers, and temporary hazards to help make cities more accessible and easy to navigate. 

**Open Data sources used and/or created**

We are collecting data from many sources to obtain a complete picture of sidewalk accessibility:
 - OpenStreetMap & OpenSidewalk
 - National Elevation Dataset from USGS
 - Durham and Cary GIS data for sidewalks and curb cuts (waiting to hear from other cities)

In addition, we will be creating new open data sources:
 - OpenStreetMap sidewalk data for North Carolina
 - User-reported hazards that can be directly reported to city 311 systems
 - Open documentation that teaches users how to input sidewalk data that can be used by AccessMap; this would allow other cities to easily offer trip planning services for people with limited mobility

**What have you done during the competition period (September 22 to October 22)?**

We researched existing projects and city initiatives related to pedestrian accessibility concerns. As part of our research, we met with the developer of OpenSidewalks and AccessMap, Nick Bolten, and we discussed forming a partnership. With Nick’s help, we developed a much clearer path forward for our project. We also reached out to city governments and successfully obtained shapefiles containing sidewalk and curb cut GIS data from two cities: Durham and Cary. We also spent time learning how to use OpenStreetMap, how to add sidewalks manually, and how to host a map-a-thon. In addition, we started work on creating a version of Chi Safe Path that works for Raleigh, which can currently display issues. 

**What else do you intend to do before the finale on November 8?**
 - Plan a mapathon for Durham
 - Start importing GIS sidewalk data into OpenStreetMap

**Describe specifically what functionality is currently implemented.**

Because our project will integrate with AccessMap, which has already been released for Seattle, much of the required functionality already exists. Our challenge will be adding sidewalk data for North Carolina in order to use this existing functionality locally. Specifically, current features include trip planning, routing based on user-specified maximum steepness, routing that requires curb ramps, and map settings for wheelchairs, powered chairs, or those with canes and/or limited walking abilities.
