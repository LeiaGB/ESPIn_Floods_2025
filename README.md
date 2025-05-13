# ESPIn_Channel_Evolution_Group_2025

<img src="Example-Images-of-ESPIn-Project-Notebook.png" alt="PriorityFloodFlowRouter-Derived Drainage Area" width="500"/>

Contributors (listed in the alphabetic order of last name): 
- **Ekta Aggarwal**              *(University of Southhampton, UK)*
- **Leia Barnes**                *(Lehigh University, Bethlehem, PA)*
- **Morgan Carrington**          *(The University of Texas at Austin, Austin, TX)*
- **Caroline Mierzejewski**      *(Texas State University, San Marcos, TX)*
- **Prakash Pokhrel**            *(University of Glasgow, UK)*

This is an ESPIn Repository for the ESPIn 2025 Channel Routing and Evolution (formerly known as the Floods Group) team project: <br>
Precipitation aids in eroding landscapes creating new channels and causing others to migrate across floodplains. When discharge increases in the channel, due to frequent rainfall events, sediment transport will increase until the flow velocity decreases, changing the evolution of the channels.

By default, Landlab directs flow and accumulates it using FlowDirectors and FlowAccumulator. The downside to the above components is that they rely on the shallow water equation, something important to note when dealing with large precipitation events that lead to flooding. 

This notebook is meant to introduce how LandLab can be used for landscape evolution in response to fluvial erosion, especially made for audiences new to numerical modelling and/or landscape evolution (i.e., undergraduate students, LandLab crash course workshop, etc.). It covers a wide, but broad, example of how to achieve this in simulated or real landscapes and aims to show how one component can be investigated alone (lateral migration) or multiple can be incorporated to see combined effects (precipitation/rainfall, infiltration, incision).

References: <br>
Barnes, R., 2017. Parallel non-divergent flow accumulation for trillion cell digital elevation models on desktops or clusters. Environmental Modelling & Software 92, 202–212. doi: 10.1016/j.envsoft.2017.02.022

Campforts B., Shobe C.M., Steer P., Vanmaercke M., Lague D., Braun J. (2020) HyLands 1.0: a hybrid landscape evolution model to simulate the impact of landslides and landslide-derived sediment on landscape evolution. Geosci Model Dev: 13(9):3863–86.

NASA Shuttle Radar Topography Mission (SRTM) (2013). Shuttle Radar Topography Mission (SRTM) Global. Distributed by OpenTopography. https://doi.org/10.5069/G9445JDF. Accessed: 2022-11-18.

Singer, M., Michaelides, K., Hobley, D. (2018). STORM 1.0: a simple, flexible, and parsimonious stochastic rainfall generator for simulating climate and climate change. Geoscientific Model Development 11(9), 3713-3726. https://dx.doi.org/10.5194/gmd-11-3713-2018
