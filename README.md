# Port of Portland GIS Open Data

Port of Portland GIS data is updated on a weekly basis (every Monday at 5:00am PST). Metadata for each dataset is provided below.

If you're restricted to ArcGIS and need a Shapefile you can use the __JSON to Features__ tool in the Conversion Toolbox. If you don't know what a Shapefile is... probably best to turn the other way and run. 

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

Properties:

* __"regClass_cd"__ = Regional Classification 

* __"localClass_cd"__  = Local Classification 

* __"permeability_cd"__ = the permeability of surface (pervious or impervious)

* __"acres"__ = area in acres

<hr>

## Stormwater Pipes

Properties:

* __"subtype_resolved"__	= type/function of feature

* __"owner_cd_resolved"__	= owner of feature i.e. Port of Portland, or City of Portland

* __"loc_survey_quality_cd_resolved"__	= location survey quality of feature

* __"facility_cd_resolved"__	= Port of Portland property name 

* __"lifecycle_status_cd_resolved"__	= lifecycle status of feature i.e. removed, or active

* __"sewer_type_cd_resolved"__	= sewer feature's type/function

* __"loc_survey_quality_date"__	 = date of location survey quality of feature

* __"material_cd_resolved"__	= material of feature


<hr>

## Wetlands

Properties:

* __"facility_cd"__	 = Port of Portland property name 

* __"FMEArea"__	 = area in square feet

* __"DSL_JD_NUM"__

* __"Acreage"__	= area in acres

* __"POLY_S_ID"__	

* __"DATA_S_YR"__	

* __"CREAT_YR"__	

* __"data_s_typ_cd"__	

* __"data_meth_cd"__	= how the data was collected/created

* __"data_accu_cd"__	

* __"COWAR_S_YR"__	

* __"hgm_cd"__	

* __"HGM_S_YR"__	

* __"coe_submit_cd"__	

* __"coe_jurisd_cd"__	

* __"COE_JD_NUM"__

* __"dsl_submit_cd"__	

* __"dsl_jurisd_cd"__	

* __"lifecycle_status_cd"__	

* __"FIELD_OBS"__	

* __"SITENAME"__	= name of wetland

* __"DSL_JD_DAT"__	

* __"COE_JD_DAT"__	

* __"SITE_ID"__ = ID of wetland

<hr>
