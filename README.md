# Port of Portland GIS Open Data

Port of Portland GIS data is updated every Monday at 5:00am PST (if the file has changed from the previous upload). Metadata for each dataset is provided below.

If you're restricted to ArcGIS and need a Shapefile you can use the __JSON to Features__ tool in the Conversion Toolbox in ArcMap (or better, just convert it in QGIS). If you don't know what a Shapefile is... probably best to turn the other way and run. 

## Data Disclaimer

Port of Portland geospatial data is gathered, maintained and primarily used for 
internal reference and analysis, and is only updated as resources permit. Geospatial 
data refers to data and information referenced to a location on the Earth's surface 
such as maps, charts, air photos, satellite images, cadastre and land and water 
surveys, in digital or hard copy form.

Geospatial data may be gathered and maintained by more than one person or department 
within the Port, and data distributed by one person or department may not reflect the 
most recent data available from the Port or from other sources. Port geospatial data 
is not intended for survey or engineering purposes or to describe the authoritative 
or precise location of boundaries, fixed human works, or the shape and contour of 
the earth.

The Port makes no warranty of any kind, expressed or implied, including any warranty 
of merchantability, fitness for a particular purpose, or any other matter with 
respect to its geospatial data.

The Port is not responsible for possible errors, omissions, misuse, or 
misrepresentation of its geospatial data.

Port geospatial data is not intended as a final determination of such features as 
existing or proposed infrastructure, conservation areas, or the boundaries of 
regulated areas such as wetlands, all of which are subject to surveying or 
delineation and may change over time. No representation is made concerning the 
legal status of any apparent route of access identified in geospatial data.

<hr>

## PoP Tax Lot

Port of Portland owned tax lots layer. Port tax lots were derived from Multnomah county tax lot data. You can find more information at https://www.portlandmaps.com/metadata/index.cfm?action=DisplayLayer&LayerID=52065 


<hr>

## PoP Property Boundary 

The Port of Portland's boundary of ownership and operations. 

Properties:

* __"FMEArea"__ = area in square ft. 

* __"FACILITY"__ = Port facilty short-hand name

* __"NAME"__ = full name of Port facility 

<hr>

## PDX Floor Plan 1st

The 1st floor floorplans are a generalized model of the layout of PDX terminal. They are styled as Apple's Indoor Mapping Data Format (IMDF) and show public access rooms and walkways along with transportation modes such as elevators, escalators and moving walkways.

Properties:

* __"LEVEL_ID"__ = floor level

* __"CATEGORY"__ = floor use/type

* __"RESTRICTED"__ = restricted access area 

<hr>

## PDX Floor Plan 2nd

The 2nd floor floorplans are a generalized model of the layout of PDX terminal. They are styled as Apple's Indoor Mapping Data Format (IMDF) and show public access rooms and walkways along with transportation modes such as elevators, escalators and moving walkways.

Properties:

* __"LEVEL_ID"__ = floor level

* __"CATEGORY"__ = floor use/type

* __"RESTRICTED"__ = restricted access area 

<hr>

## PDX Floor Plan 3rd

The 3rd floor floorplans are a generalized model of the layout of PDX terminal. They are styled as Apple's Indoor Mapping Data Format (IMDF) and show public access rooms and walkways along with transportation modes such as elevators, escalators and moving walkways.

Properties:

* __"LEVEL_ID"__ = floor level

* __"CATEGORY"__ = floor use/type

* __"RESTRICTED"__ = restricted access area 

<hr>

## PDX Noise Contours 1982 (FAR Part 150)

This data comes from Noise Exposure Maps developed as part of FAA FAR Part 150 Noise Compatibility Studies for PDX. The FAA required that they weere developed with the use of the Integrated Noise Model (INM).

Day-Night Average Sound Level (DNL) is the noise metric the FAA and EPA suggest airport proprietors use in judging land use compatibility with aircraft noise. By federal guidelines residential, scholastic, religious and some other uses are incompatible with levels at or above 65 dB DNL.

Properties:

* __"DNLcontour"__ = Day-Night Average Sound Level noise metric in dB

* __"AREASQMI"__ = area in square miles

* __"FMEArea"__ = area in square feet

<hr>

## PDX Noise Contours 1990 (FAR Part 150)

This data comes from Noise Exposure Maps developed as part of FAA FAR Part 150 Noise Compatibility Studies for PDX. The FAA required that they weere developed with the use of the Integrated Noise Model (INM).

Day-Night Average Sound Level (DNL) is the noise metric the FAA and EPA suggest airport proprietors use in judging land use compatibility with aircraft noise. By federal guidelines residential, scholastic, religious and some other uses are incompatible with levels at or above 65 dB DNL.

Properties:

* __"DNLcontour"__ = Day-Night Average Sound Level noise metric in dB

* __"AREASQMI"__ = area in square miles

* __"FMEArea"__ = area in square feet

<hr>

## PDX Noise Contours 1994 (FAR Part 150)

This data comes from Noise Exposure Maps developed as part of FAA FAR Part 150 Noise Compatibility Studies for PDX. The FAA required that they weere developed with the use of the Integrated Noise Model (INM).

Day-Night Average Sound Level (DNL) is the noise metric the FAA and EPA suggest airport proprietors use in judging land use compatibility with aircraft noise. By federal guidelines residential, scholastic, religious and some other uses are incompatible with levels at or above 65 dB DNL.

Properties:

* __"DNLcontour"__ = Day-Night Average Sound Level noise metric in dB

* __"AREASQMI"__ = area in square miles

* __"FMEArea"__ = area in square feet

<hr>

## PDX Noise Contours 2008 (FAR Part 150)

This data comes from Noise Exposure Maps developed as part of FAA FAR Part 150 Noise Compatibility Studies for PDX. The FAA required that they weere developed with the use of the Integrated Noise Model (INM).

Day-Night Average Sound Level (DNL) is the noise metric the FAA and EPA suggest airport proprietors use in judging land use compatibility with aircraft noise. By federal guidelines residential, scholastic, religious and some other uses are incompatible with levels at or above 65 dB DNL.

Properties:

* __"DNLcontour"__ = Day-Night Average Sound Level noise metric in dB 

* __"AREASQMI"__ = area in square miles

* __"FMEArea"__ = area in square feet

<hr>

## Mitigation Sites

Mitigation and enhancement sites that are either owned or managed by the Port of Portland. These sites are managed as natural areas to maintain site ecology and improve wildlife habitat.  

Properties:

* __"port_facility"__ = Port of Portland property name 

* __"mitigation_type_cd"__ = the type of mitigation site

* __"coe_permit"__ = Corp of Engineers permit number 

* __"dsl_permit"__  = Department of State Lands permit number

* __"other_permits"__ = Permits not related to COE or DSL

* __"FMEArea"__ = area in square feet

* __"coe_date"__ = date of the jurisdictional determination for the COE

* __"dsl_date"__ = date of concurrence for DSL

<hr>

## Natural Resource Inventory

A natural resources mapping and inventory dataset that characterizes and maps Port properties in terms of existing land cover, wildlife habitat, and vegetation. It was completed using geographic information systems (GIS) and on-the-ground observations of Port property to define existing resource habitat type.

Properties:

* __"regClass_cd"__ = Regional Classification 

* __"localClass_cd"__  = Local Classification 

* __"permeability_cd"__ = the permeability of surface (pervious or impervious)

* __"acres"__ = area in acres

<hr>

## Port Stormwater Data: 

### Manholes, Catch Basins, Outfalls, Pipes, Vaults, Misc Features

The Port’s open stormwater collection system dataset includes points and lines representing the following features: manholes, catch basins, outfalls, and pipes. Each of these features are available to download individually above. Please contact Port staff for more information about the stormwater data.

<hr>

## Wetlands

Boundary of known jurisdictional wetlands on Port of Portland property either field delineated or identified using remote sensing (i.e., aerial photo or LiDAR interpretation). Updated as new wetland data on Port property becomes available.

Properties:

* __"facility_cd"__	 = Port of Portland property name 

* __"FMEArea"__	 = area in square feet

* __"DSL_JD_NUM"__ = File number assigned to the delineation report by the Oregon Department of State Lands.

* __"Acreage"__	= area in acres

* __"POLY_S_ID"__	 = Wetland polygon ID in original data

* __"DATA_S_YR"__	 = Source and year of original data

* __"CREAT_YR"__	= Creator and year of polygon if different than DATA_S_YR

* __"data_s_typ_cd"__	 = Data source type

* __"data_meth_cd"__	= how the data was collected/created

* __"data_accu_cd"__	= accuracy of data

* __"COWAR_S_YR"__	= Source and year of Cowardin data if different than DATA_S_YR

* __"hgm_cd"__	

* __"HGM_S_YR"__	= Source and year of HGM if different than DATA_S_YR

* __"coe_submit_cd"__	 = Was the delineation submitted to a federal regulatory agency--US Army Corps of Engineers? Yes/No

* __"coe_jurisd_cd"__	 = Federal jurisdiction under US Army Corps of Engineers

* __"COE_JD_NUM"__ = File number assigned to the delineation by the COE (may be the same as the permit number)

* __"dsl_submit_cd"__	= Was the delineation submitted to a state regulatory agency--Oregon Department of State Lands? Yes/No

* __"dsl_jurisd_cd"__	 = State jurisdiction under Oregon Department of State Lands.

* __"FIELD_OBS"__	= was the wetland boundary field verified?

* __"SITENAME"__	= name of wetland

* __"DSL_JD_DAT"__	= Date of concurrence that initiates the 5 year period on which the DSL permit is valid.

* __"COE_JD_DAT"__	= Date that the jurisdictional determination was issued by the COE

* __"SITE_ID"__ = ID of wetland

<hr>
