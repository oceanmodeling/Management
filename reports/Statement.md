# MOTIVATION 

Ocean & Coastal physical processes play a significant role in many aspects of human life. Ocean currents, Tides, storm surges and subsequent flooding, erosion and sea level rising, among other factors, have a significant impact in the risk associated with both assets and people.

**Headlines**

•	Most humans live in coastal areas.

•	Climate change will affect the coastal areas with sea level rise and storm surge inundations.

•	High quality data, in terms of resolution and accuracy, are needed for evaluating the impact of coastal physical processes.

•	Dynamic monitoring and forecasting could inform policies for mitigation and adaptation. 

•	A coordinated approach to data collection and large-scale integrated ocean modelling can provide added value to all stake holders.



## MODELLING 

Global sea level modelling is currently within our capabilities. However, the problem is inherently multi-scaled. Evaluating the mean sea level at a global resolution of 1-5 km near the shoreline, with variable resolution for open seas, although challenging, is achievable. Global bathymetric data are available for providing the necessary input for this computation. 

Utilising unstructured grids and High Performance Computing (HPC) in large scale we could simulate global oceans in 4D under High Resolution (HR) configurations. There are chalenges inherent to scaling up to this level though and additional considerations when the coastal area is also included.

Modelling the inundation of the coastal area including possibly also river runoffs, poses the biggest obstacle since it requires an accurate representation of the coastal region. The resolution at which this study will be done can be crucial for the accuracy of the prediction. Other parameters play a role as well, such as beach type, land use, etc. Not to be underestimated is the temporal evolution of the coast as a result of physical and man-made processes. The latter implies that a ‘static’ evaluation based on averaged quantities will not suffice to analyse an ever-changing coastal morphology.

Addressing this problem in a dynamical forecasting mode is not trivial and requires efficiencies and integrations in large scales.

## DATA

There are a number of sources that can provide continuous data relevant to ocean modelling. These fall into two categories, namely in-situ stations and Earth Observation (EO) measurements. 

However, these are generally intermittent with different frequency, range, accuracy, quality and time reference. Therefore, combining these datasets into a seamless unified set is not trivial. The case of an integrated topobathy (the integration of bathymetric data from the sea and topographic data from the land) highlights this challenge. The available data are produced by two different scientific communities that have traditionally used different references (datums) and techniques (remote sensing, sonar, etc.), requiring special treatment before integration. More importantly, there is a tendency to avoid the interface between land and water, due to the specific distinction between them, that most of the times, prompts different modelling considerations. It is however exactly at the coastal region where the focus is needed.


## DEVELOPMENT

Thus, there is a need to develop a reproducible workflow for estimating, to the highest possible accuracy, a consistent and seamless model of global oceans including coastal processes at resolutions that facilitate dynamic impact studies and provide up-to-date situational awareness. Such workflows could be continuously updated with new information as it becomes available. The resulting framework needs to allow for enhanced participation and community endorsement, suggesting that the algorithms used should be portable, transparent and open-source. A comprehensive quality control procedure should also be developed. Dealing with such an inherently multiscale problem would require multiple solvers and numerical modules integrated in the most effective manner.


## MISSION STATEMENT 

The need for an integration strategy has been recognised already by major organisations around the world. There is an effort to address the issue through common research programs. However, the approach still remains inconsistent and with inherent constrains.

More importantly siloed programs lead to duplication and loss of added value. It is argued that a closer collaboration and co-development under an independent organisation with the active participation and support of many stake holders can be beneficial.  

This paradigm is already proven to work within the research community with projects such as [pydata](https://pydata.org/) and [pangeo](https://pangeo.io/). 

The integration of multiple independent solvers under a common interface is under way in the United States (US) with projects such as [ESMF](https://earthsystemmodeling.org/) and [UFS](https://ufscommunity.org/). Similar ombrella projects such as [EE](https://www.extremeearth.eu/) and [DestinE](https://digital-strategy.ec.europa.eu/en/policies/destination-earth) are sponsored within the European Union (EU). 

However these are large scale initiatives with much larger scope and challenges in terms of frameworks but mostly constrained by political and budgetary viewpoints.

We intend to deal only with the ocean component but go global and deeper in the collaboration/integration/development aspect. In particular, we want to address the software development cycle and engage the actual developers in an effort to integrate the solutions from the ground up. This implies that there is no exclusion of currently available solutions but rather an effort to bring together the development paradigm with integration as a prerequisite rather than an afterthought.

With the advent of data analytics and Machine Learning (ML), it can also be argued that there is a corresponding paradigm shift. The data cubes are the object and the various algorithms, be that a python function or a sophisticated global 3D unstructured grid numerical solver, operates on these data on demand. This requires appropriate APIs and code development especially when scaling up to the requirements of HR analysis. More so, the code needs to work transparently from the laptop to HPC and Cloud services.  
   
Tackling the problem in a concise and sustainable way requires input from many scientific communities with different approaches and perspectives. 

Our goal is to 

•	Provide a comprehensive analysis of the problem at hand.

•	Take stock of the available research, datasets & numerical models.

•	Bring together all relevant scientific communities in an effective and productive way.

•	Promote interoperability and integration by supporting open source co-developement.

•	Champion reproducibility, data provenance and documentation requirements.  

•	Identify and address gaps.

•	Inform research planning and funding at an inter-organisational global level for maximum coordination.

•	Research and demonstrate best practices in code management.

•	Support state-of-the-art numerical models and frameworks.

•	Enhance community participation with maximum uptake.

•	Bridge the gap between Research and Operations.

•	Participate in relevant initiatives.







