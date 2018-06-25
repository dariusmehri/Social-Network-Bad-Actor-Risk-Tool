### This analysis uses social network analysis to develop a risk tool to improve building safety

The Department of Buildings issues approximately 300,000 building permits a year, a number of these permits will result in illegal work. The idea behind this project was to use network measures to categorize construction permits as high and produce a list of building to audited or inspected.

Each construction permit contains the names of the actors working on the project. These include the owner, architect or engineer, contractor and filing representative. Each permit produces a network of actors working at a building in New York City.

A bad actor list is generated based on previous illegal work or dispositions. 

This project had two steps. 1) Among the list of known bad actors, creating a ranking system from very bad to bad. 2) Rank the most recent permits as high or low risk based on risk tool (see below measures)

### Risk Tool Measures: 
#### Transactional
Total number of ties: Total number of ties each actor has in the network \
Total number of bad ties: Total number of bad ties to each actor \
Bad tie density: Total number of bad ties/Total number of ties 

#### Bad Actor Work Relationships 
Total number of unique ties: Total number of ties each actor has in the network \
Total number of unique bad ties: Total number of bad ties to each actor \
Bad unique tie density: Total number of unique bad ties/Total number of unique ties 

#### Influence in the industry 
Total Number of BINs: Total number of buildings they worked on \
Unique Number of BINs: Unique number of buildings they worked on, each BIN is counted only once 

#### Membership in “bad” community (community detection analysis) 
Community Membership: The name of the community in which they belong \
Community Bad Density Unique = # Bad Unique in Community/# Number Unique in Community


### Network analysis example:

Graph of the top 20 bad actors. The most central actor in the network (Shmiel Firth) recently received violation for building collapse. Yellow nodes are bad actors, white nodes are uknown bad actors.

![badactor20network](https://user-images.githubusercontent.com/11237613/41874034-b3a7dcd0-7894-11e8-8d7c-b7db34c9e729.png)




Example of community detection, clusturing of bad actor communities:

















