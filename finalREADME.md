# FP01-mars-seismo
**Group Members:** Chloe Locke (@chloelocke), Grace Galvin (@gracegalvin12), Paige Dompier (@pdompier)

**Project Summary** In this project we will be analyzing seismic data from Mars and Earth. Our goal is to successfully interpret and represent the data in order to compare and contrast how quakes behave on the two different planets. We will use our findings to identify geological/geophysical similarities and differences between the two planets.  The data from Mars comes from the Elyse station, and the data from Earth comes from The Little Thumb Seismic Station in Yellowstone.

**How to use this repository** 

**Introduction** When gathering data from two seperate planets we wanted to find the most similar geological locations on each planet possible. The data from Mars came from the Elyse station; which is the landing spot for the Mars InSight mission that landed in 2018 and deployed a seismometer to study the planet's interior structure and seismic activity. The landing area, also known as Elysium Planitia, is a field with multiple volcanic constructs. Using this information, and the following topographic map, we begin to look for a location on Earth with similar features. 

<img src="https://www.dlr.de/content/en/images/2018/2/the-landing-site-for-the-insight-mission-in-elysium-planitia_30417.jpg?__blob=normal&v=20__ifc1920w" width="500" height="400">

The data utilzed from Earth was found at Yellowstone and gathered by the Little Thumb Seismic Station. This station sits on the Yellowstone Caldera, which is a volcanic caldera and a hotspot for geothermal activity. 
<img src="https://lh3.googleusercontent.com/0P_uBRDIG-t4RjUEtLNsXAy8Wh4m9zyKP4vdingpa6aLOOefOv-rcWZRTSm2Cs8YtJoi-kf1tL8TWKtY0IQgQg1vTvJjXazl5-b2owCW" width="500" height="400">

It was important to collect our datasets from areas of similar geophysical to 

**Tools and packages used**  
    We have utilized a handful of packages to run our code in JupyterLab, including numpy, xarray, matplotlib, and obspy.  Obspy is a package specifically used for plotting and displaying seismic data. (Website used for learning Obspy formatting included in references section below)

**Project methodology/approach**  
    For this project, our first task was to acquire accessible seismic data from a location on Mars, as this data proved to be the most difficult to find, access, and read into our code.  Once we acquired a few different Mars seismic data files, we began the process of converting those files into a readable format to determine what variables we were looking at.  After a brief analysis of the data, we were able to determine what variables were being measured and which seismic tools were used to acquire said data.  With this information in mind, we then began looking for seismic data files from Earth with the same variables and parameters.  Another factor that weighed into our decision of which Earth data set to use was the topographic and geological makeup of the locations, as we wanted the area for the data on Earth to resemble the area for the data on Mars as much as possible.  For this reason, we chose to analyze a seismic data set from Yellowstone, a geothermal hotspot and volcanic caldera, to match the highly volcanic area of the Elysium Planitia on Mars that we were assessing.  
    The coding for our project came with a bit of a learning curve, as we had never interpreted or plotted this type of data before, and therefore had to learn our way around a new package known as Obspy.  To accomplish this task, we first had to do some research and look at examples of seismic interpretations using Obspy, as well as utilize the Obspy website where they outline key functions to call in order to plot seismic data.

**Summary of the results**  
(Description of graphs similarities and differences)

Through our observations of the seismic events being fairly similar on each planet, we can conclude that the geological/geophysical features on the two planets most likely resemble one another. And while there is currently no difinitive evidence of there being a magma chamber under the surface of Mars, using our knowledge of the fact that volcanic activity can cause an increase in earthquakes in the surrounding area, we can infer that the increase of seismic activity around the Elysium Planitita is linked to the presence of a magma chamber under the region. 

**Contributions**

**References**  
“Waveform Plotting Tutorial.” Waveform Plotting Tutorial - ObsPy 1.4.0 Documentation, 21 Nov. 2022, https://docs.obspy.org/tutorial/code_snippets/waveform_plotting_tutorial.html. 
Yellowstone Topography Data
https://apps.nationalmap.gov/downloader/
Mars Topography Data
https://astrogeology.usgs.gov/search/map/Mars/Topography/HRSC_MOLA_Blend/Mars_HRSC_MOLA_BlendDEM_Global_200mp_v2
https://usgs.maps.arcgis.com/apps/webappviewer/index.html?id=fc004c3d21b64c398ed5458580ab7c58
Mars/Earth Seismic data
https://service.iris.edu/fdsnws/dataselect/docs/1/builder/
http://www.fdsn.org/pdf/SEEDManual_V2.4_Appendix-A.pdf
