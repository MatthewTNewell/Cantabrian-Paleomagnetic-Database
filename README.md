# Cantabrian Paleomagnetic Database

*Last Updated: October 2021*

The database is available for viewing [here](https://matthewtnewell.github.io/Cantabrian-Paleomagnetic-Database/) and download in several different formats to allow ease of use in a range of spreadsheets and database management systems.

This compilation of paleomagnetic data contains all currently published paleomagnetic rotation control points from the Cantabrian Zone of North Western Iberia (as of October 2021). It was originally compiled in 2019 as part of an MSc Resources and Exploration Geology thesis at Cardiff University looking at the kinematics and formation mechanism of the Cantabrian orocline. 

The database has been restricted to the Cantabrian Zone of North Western Iberia as it contains the vast majority of available paleomagnetic measurements. This is a consequence of its key location at the core of the larger Ibero-Amorican Arc, where the greatest change in structural trends is observed. On top of this the relative lack of metamorphism, well below Curie temperature for the main two ferromagnetic minerals haematite and magnetite and low internal strain in the rocks result in higher levels of integrity of the paleomagnetic vectors with respect to the more internal Variscan units *(Hirt et al., 1992; Brime et al., 2001)*. 

The data contained here came from 12 studies *(Bonhommet et al., 1981; Hirt et al. 1992; Pares et al., 1994; Ries et al., 1980; Schott and Peres, 1987; Stewart, 1995; Van der Voo et al., 1997; Weil et al., 2013; Weil et al., 2010; Weil, 2006; Weil et al. 2001; Weil et al., 2000)* as well as new currently unpublished data from the Villamanin area collected by Professor Thomas Blenkinsop (Cardiff University) and Tania Mochales (Instituto Geologico y Minero de Espana) during the summers of 2015 and 2016 at 13 sites across the Lancara, San Emiliana, La Vid, Barcallente and Barrios Formations. Overall 423 sites sampled for paleomagnetic investigation from Paleozoic redbeds and carbonates are presented here. Data was extracted from papers using the freely available software Tabula and has been laid out to be similar to the Pyrenean paleomagnetic database *(Lopez et al., 2008)*. The data fields try to assemble the information necessary to quantify the amount of vertical axis rotation the rocks have experienced, as well as evaluate the reliability and quality of the data based on the requirements laid out by Van der Voo (1990), allowing future overviews of the Cantabrian dataset. The data fields are explained below:

### General Information

Site/Profile = Site code used in publication  
Year = Year of sampling or if not available, year of publishing   
Main_Author = 1st named author  
Ref = Reference in Harvard style  
University = Institute of main author  
DOI = Digital Object Identifier  
M/R = Distinguish rotation control points (R) from magnetostratigraphic profiles (M) which are planned to be added in the future.  

### Geographic Information 

Latitude_N = Latitude (WGS 1984)  
Longitude_W = Longitude (WGS 1984)  
Q/Geo = 1 - Coordinates provided by author  
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; = 2 - Coordinates deduced by georeferencing maps of publications with scales <1:50,000  
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; = 3 - Coordinates deduced by georeferencing maps of publications with scales >1:50,000  
      
### Stratigraphic Information

Rock_Type = Rock type  
Formation = Rock formation  
Stratigraphic = Published stratigraphic age  

### Structural Information

Unit = Tectonostratigraphic unit using clasification of Julivert (1971)  
Structural = Fold/thrust or nappe name  
Strike = Strike of bedding in degrees (using right hand rule unless overturned)  
Dip = Dip of bedding in degrees (if overturned >90)  
DD = Dip direction (using right hand rule unless overturned)  
Ov = Y - Overturned  
&nbsp; &nbsp; &nbsp; = N - Right way up  
Q/Str = 1 - Bedding oreintation provided by author  
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; = 2 - Bedding oreintation gathered from nearby stuctual data on map sheets *(IGME, 1971-1990)*  
Structure = Type or name of structure described by the following trend and plunge  
Trend = Trend of local structures  
Plunge = Plunge of local structures  

### Paleomagnetic Information

In the majority of studies on the region two major magnetic components are identidifed: a late Carbonifeous C component and a late Stephanian - early Permian B component *(Weil et al., 2000)*. For simplcity instead of giving the unlocking temperatures or coercitivites to describe the magnetic components they have been seperated into the C and B catagories, any magnetisation that doesn't fall into this clasification have the ages identified within the comments section.

UnblockT = Temperature or temperature range of unblocking component considered
n = Number of samples used in analysis  
N = Number of samples collected  
D(bac) = Magnetic declination (before any correction)  
I(bac) = Magnetic inclination (before any correction)  
D(abc) = Magnetic declination (after bedding correction) or any other form of structural correction  
I(abc) = Magnetic inclination (after bedding correction) or any other form of structural correction  
a(bac) = Cone of 95% confidence about mean direction before bedding or structural correction  
k(bac) = Precision parameter before bedding or structural correction  
Pol = +  Normal polarity  
&nbsp; &nbsp; &nbsp; = -  Reverse polarity  
&nbsp; &nbsp; &nbsp; = +/-  Mostly normal polarity  
&nbsp; &nbsp; &nbsp; = -/+  Mostly reverse polarity  

## References

Bonhommet, H., Cobbold, N. and Perroud, P. (1981). Paleomagnetism and cross-folding in a key area of the Asturian Arc (Spain). *Journal of Geodynamics*, 86, pp. 1873-1887.

Brime, C., García-López, S. Bastida, F., Luz Valín, M., Sanz-López, J. and Aller, J. (2001). Transition from Diagenesis to Metamorphism Near the Front of the Variscan Regional  Metamorphism (Cantabrian Zone, Northwestern Spain). *The Journal of Geology*, 109(3), pp. 363-379. 

Hirt, A., Lowrie, W., Julivert, M. and Arboleya, M. (1992). Paleomagnetic results in support of a model for the origin of the Asturian arc. *Tectonophysics*, 213(3-4), pp. 321-339.

IGME (1971-1990). Geologic map of Spain at scale 1/50,000. *Geologic and Mining Institute of Spain*. Madrid. 

Julivert, M. (1971). Decollement Tectonics in the Hercynian Cordillera of Northwest Spain. *American Journal of Science*, 270, pp. 1-29.

López, M., Oliván, C., Oliva, B. and Puedo, E. (2008). Pyrenean Paleomagnetic databases. *Geo-Themes*, 10, pp. 1219-1222. 

Parés, J., Van der Voo, R., Stamatakos, J and Pérez-Estaún, A. (1994). Remagnetisations and postfolding oroclinal rotations in the Cantabrian Asturian Arc, Northern Spain.  *Tectonics*, 13(6), pp. 1461-1471. 

Ries, A., Richardson, A. and Shackleton, R. (1980). Rotation of the Iberian Arc: Paleomagnetic results from Northern Spain. *Earth and Planetary Science Letters*, 50, pp. 301-310. 

Schott, J. and Peres, A. (1987). Paleomagnetism of Permo-Triassic Redbeds from the Asutrias and Cantabric Chain (northern Spain): evidence for strong lower Tertiary    remagnetizations. *Tectonophysics*, 140, pp. 179-191. 

Stewart, S. (1995). Paleomagnetic analysis of fold kinematics and implications for geological  models of the Cantabrian/Asturian arc, north Spain. *Journal of Geophysical Research*,  100, pp. 20079-20094. 

Van der Voo, R. (1990). The reliability of paleomagnetic data. *Tectonophysics*, 184, pp. 1-9. 

Van der Voo, R., Stamatakos, J. and Pares, J. (1997). Kinematic constraints of thrust-belt curvature from syndeformational magnetisations in the Lagos del Valle Syncline in the Cantanrian Arc, Spain. *Journal of Geophysical Research*, 102(B5), pp. 10105-10119. 

Weil, A. (2006). Kinematics of Orocline Tightening in the Core of an Arc: Paleomagnetic Analysis of the Ponga Unit, Northern Spain. *Tectonics*, 25(3). 

Weil, A., Gutierrez-Alonzo, G. and Conon, J. (2010). New time constraints on lithospheric-scale oroclinal bending of the Ibero-Ibero-American Arc: a paleomagnetic study of the earliest Permian rocks from Iberia. *Journal of the Geological Society of London*, 167(1), pp. 127-143.

Weil, A., Gutierrez-Alonso, G. and Wicks, D. (2013). Investigating the kinematics of local thrust sheet rotation in the limb of an orocline: A paleomagnetic and structural analysis of the Elsa tectonic unit, Cantabrian-Austurian Arc, NW Iberia. *International Journal of Earth Science*, 102(1), pp. 43-60. 

Weil, A., Van der Voo, R. and Van der Pluijm, B. (2001). Oroclinal bending and evidence against the Pangea megashear: The Cantabria-Asturias arc (northern Spain). *Geology*, 29(11), pp. 991-994.

Weil, A., Van der Voo, R., Van der Pluijm, A. and Parés, J. (2000). The formation of an orocline by multiphase deformation: a paleomagnetic investigation of the Cantabrian- Asturias Arc (northern Spain). *Journal of Structural Geology*, 22(6), pp. 735-756.




