# FP01-mars-seismo 

**Group Members:** Chloe Locke (@chloelocke), Grace Galvin (@gracegalvin12), Paige Dompier (@pdompier) 

**Project Summary** 
<<<<<<< HEAD
=======
   
   In this project we will be analyzing seismic data from Mars and Earth. Our goal is to analyze the geological differences between the planets and successfully interpret and represent seismic data in order to compare and contrast how quakes behave on the two different planets. We will use our findings to identify geological/geophysical similarities and differences between the two planets. The data from Mars comes from the Elyse station (Elysium Planitia), and the data from Earth comes from The Little Thumb Seismic Station in Yellowstone. 
>>>>>>> 7dd0d4718a171850603d7d18152c92872a42bed2

  In this project we will be analyzing seismic data from Mars and Earth. Our goal is to analyze the geological differences between the planets and successfully interpret and represent seismic data in order to compare and contrast how quakes behave on the two different planets. We will use our findings to identify geological/geophysical similarities and differences between the two planets. The data from Mars comes from the Elyse station (Elysium Planitia), and the data from Earth comes from The Little Thumb Seismic Station in Yellowstone. 

**How to use this repository** 

   To use this repository, begin by reading this entire file to understand the purpose of the repository and what kind of data it holds. Make sure to have all of the packages downloaded that are listed in the MarsSeismo.yml file. All of the code needed to recreate the results of this repository is located in the finalSeismo.ipynb file. The code contains a function that can easily be recreated with your own data sets! However, if you would like to use our data, it can all be found in the DATA folder. If there is any confusion about where certain things are located, the DirTree.pdf contains directions to all files in the repository.

**Introduction**  

   When gathering data from two seperate planets we wanted to find similar geological locations on each planet. The data from Mars came from the Elyse station; which is the landing spot for the Mars InSight mission that landed in 2018 and deployed a seismometer to study the planet's interior structure and seismic activity. The landing area, also known as Elysium Planitia, is a field with multiple volcanic constructs. Using this information, and the following topographic map, we begin to look for a location on Earth with similar features.  
 
   The data utilzed from Earth was found at Yellowstone and gathered by the Little Thumb Seismic Station. This station sits on the Yellowstone Caldera, which is a volcanic caldera and a hotspot for geothermal activity.  

  It was important to collect our datasets from areas with similar geology to be able to accurately compare two quakes; along with that we chose two quakes of similar magnitude. The average magnitude for a marsquake is 1-3, with that in mind we decided to analyze an earthquake of magnitude 1.9. Once we found our desired datasets from each planet our goal was to manipulate the data inorder to produce figures to be able to better understand each of the quake and analyze their differences.  

**Datasets** 

The data sets can be found in the datafile and at the links below 

[Yellowstone Topography Data](https://apps.nationalmap.gov/downloader/) 

[Mars Topography Data](https://astrogeology.usgs.gov/search/map/Mars/Topography/HRSC_MOLA_Blend/Mars_HRSC_MOLA_BlendDEM_Global_200mp_v2) 

[Geological Map of Mars](https://usgs.maps.arcgis.com/apps/webappviewer/index.html?id=fc004c3d21b64c398ed5458580ab7c58) 

[Mars/Earth Sesismic Data](https://service.iris.edu/fdsnws/dataselect/docs/1/builder/) 

[SEEDmanuel](http://www.fdsn.org/pdf/SEEDManual_V2.4_Appendix-A.pdf) 

[InSight Seismic Data Downloader](https://github.com/UMD-InSight/InSight-seismic-data-downloader) 

**Tools and packages used**   

   We have utilized a handful of packages to run our code in JupyterLab, including numpy, xarray, matplotlib, and obspy.  Obspy is a package specifically used for plotting and displaying seismic data. (Website used for learning Obspy formatting included in references section below)   

   Other packages: 
   - cartopy.crs 
   - tifffile 
   - imagecodecs 

**Project methodology/approach**   

   For this project, our first task was to acquire accessible seismic data from a location on Mars, as this data proved to be the most difficult to find, access, and read into our code.  Once we acquired a few different Mars seismic data files, we began the process of converting those files into a readable format to determine what variables we were looking at.  After a brief analysis of the data, we were able to determine what variables were being measured and which seismic tools were used to acquire said data.  With this information in mind, we then began looking for seismic data files from Earth with the same variables and parameters.  Another factor that weighed into our decision of which Earth data set to use was the topographic and geological makeup of the locations, as we wanted the area for the data on Earth to resemble the area for the data on Mars as much as possible.  For this reason, we chose to analyze a seismic data set from Yellowstone, a geothermal hotspot and volcanic caldera, to match the highly volcanic area of the Elysium Planitia on Mars that we were assessing.   

   The coding for our project came with a bit of a learning curve, as we had never interpreted or plotted this type of seismic data before, and therefore had to learn our way around a new package known as Obspy.  To accomplish this task, we first had to do some research and look at examples of seismic interpretations using Obspy that we found online, as well as utilize the Obspy website wherein they outline key functions to call for plotting seismic data.  It took testing out some different plotting techniques and trying out a few different graphing methods to figure out what worked best for displaying and representing our data.  After compiling our code, we worked to clean up and add titles/labels to our data plots to tie together our final product. 


**Summary of the results**   

   The results of our research show that there are differences in the movement of quakes between the two planets. The quakes on Mars appear to travel more uniformly and faster than on Earth. We were able to make this discovery by analyzing the dayplots from both a marsquake and earthquake. We found that the activity in the dayplot for the earthquake lasted 9 minutes longer than marsquake activity. The Earth event began at approximately 9:31 and ends at approximately 10:49 with the peak occurring at approximately 9:43. While the martian event began at approximately 13:53 and ended at approximately 15:02 with the peak occurring at 14:04. More differences in the data are that, on Mars, the bigger spikes occur over a longer period of time, with a more even time distribution between spikes in amplitude, and on Earth, big spikes in seismic data occur over a small period of time with very small wave amplitudes towards the end of the event.  

   With more research we were able to identify that the marsquake having a shorter duration than the earthquake is due to Mars being less dense than Earth. The density of Earth is 2.6 g/cm^3 and the density of Mars is 2.5 g/cm^3. This difference is due to the compositions of the planets.  Another reason for marsquakes moving quicker is the thickness of the crusts. At the location of the Earth event the crustal thickness is 47-52km, whereas at the location of the Mars event the crustal thickness is 30-47km. Having a thiner crust on Mars means that the waves have a shorter distance to travel. The Martian crust is also more igneous, and volcanic rock tends to have a higher porosity, making it easier for the waves to travel through.  

   While there are differences betwwen the two planets, some of the similarites are that both crusts are mostly oxygen and silicon, making up 66% of the Mars crust, and 78% of the Earth crust. And although there is currently no difinitive evidence of there being a magma chamber under the surface of Mars, using our knowledge of the fact that volcanic activity can cause an increase in earthquakes in the surrounding area, we can infer that the increase of seismic activity around the Elysium Planitita is linked to the presence of a magma chamber under the region, which would be another similarity to Earth because Yellowstone is located atop a magma chamber.  
 

**Contributions** 

   As a group we all worked very well together. Each person brought different strengths to our project. Chloe Locke played a crucial role in obtaining our dataset for the Mars event, she was able to use personal connections to aquire data from the NASA Insight mission on Mars. Once we had our dataset, Paige Dompier successfully manipulated the data to get the data into the format that we desired. Chloe Locke did that same process for reading in the Earth data and produced the plots we needed. When we had plots from both Mars and Earth we all worked together to understand what each graph was showing. Chloe also produced a detailed topographic map for both Mars and the Yellowstone seismic station. Grace Galvin researched various geophysical and geological aspects from Earth and Mars to help explain the differences that we were seeing in the graphs. Chloe is responsible for making our final presentation slides and our enviroment.yml, Grace created and wrote the majority of the README, and Paige made our final jupyter notebook. We worked on all of our other tasks together.  

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
https://github.com/UMD-InSight/InSight-seismic-data-downloader 

Other 
https://bigthink.com/hard-science/mars-earthquake-marsquake/ 
https://www.researchgate.net/figure/Topographic-map-of-the-region-around-the-InSight-landing-site-NSY-showing-major_fig2_325998973 
https://www.lpi.usra.edu/education/IYPT/Mars.pdf 
https://www.usgs.gov/programs/earthquake-hazards/seismographs-keeping-track-earthquakes 
https://nssdc.gsfc.nasa.gov/planetary/factsheet/marsfact.html 

 
