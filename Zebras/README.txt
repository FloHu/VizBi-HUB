README

This data file is published by the Movebank Data Repository (www.datarepository.movebank.org). As of the time of publication, a version of the published animal tracking data set can be viewed on Movebank (www.movebank.org) in the study "Migratory Burchell's zebra (Equus burchellii) in northern Botswana (Bartlam-Brooks et al. 2013)". Individual attributes in the data files are defined below and in the Movebank Attribute Dictionary, available at www.movebank.org/node/2381.

This data package includes the following data files:
Migratory Burchell's zebra (Equus burchellii) in northern Botswana.csv
Migratory Burchell's zebra (Equus burchellii) in northern Botswana-reference data.csv

Bartlam-Brooks, H.L.A., Beck, P.S.A., Bohrer, G., Harris, S., 2013, In search of greener pastures—using satellite images to predict the effects of environmental change on zebra migration: Journal of Geophysical Research: Biogeosciences, v. 188, p. 1–11. doi:10.1002/jgrg.20096

Data package citation
Bartlam-Brooks, H.L.A., Harris, S., 2013, Data from: In search of greener pastures—using satellite images to predict the effects of environmental change on zebra migration: Movebank Data Repository. doi:10.5441/001/1.f3550b4f

-----------

Terms of Use
This data file is licensed by the Creative Commons Zero (CC0 1.0) license. The intent of this license is to facilitate the re-use of works. The Creative Commons Zero license is a "no rights reserved" license that allows copyright holders to opt out of copyright protections automatically extended by copyright and other laws, thus placing works in the public domain with as little legal restriction as possible. However, works published with this license must still be appropriately cited following professional and ethical standards for academic citation.

We highly recommend that you contact the data creator if possible if you will be re-using or re-analyzing data in this file. Researchers will likely be interested in learning about new uses of their data, might also have important insights about how to properly analyze and interpret their data, and/or might have additional data they would be willing to contribute to your project. Feel free to contact us at support@movebank.org if you need assistance contacting data owners.

See here for the full description of this license
http://creativecommons.org/publicdomain/zero/1.0

-----------

Data Attributes
These definitions come from the Movebank Attribute Dictionary, available at www.movebank.org/node/2381.

animal ID: An individual identifier for the animal, provided by the data owner. This identifier can be a ring number, a name, the same as the associated tag ID, etc. If the data owner does not provide an Animal ID, an internal Movebank animal identifier may sometimes be shown.
	example: 91876A, Gary
	same as: individual local identifier

animal life stage: The age class or life stage of the animal at the beginning of the deployment. Can be years or months of age or terms such as "adult", "subadult" and "juvenile". Units should be defined in the values (e.g. "2 years").
	example: juvenile, adult
	units: Any units should be defined in the remarks.

attachment type: The way a tag is attached to an animal. Values are chosen from a controlled list:
	collar: The tag is attached by a collar around the animal's neck.
	glue: The tag is attached to the animal using glue.
	harness: The tag is attached to the animal using a harness.
	implant: The tag is placed under the skin of the an animal.
	tape: The tag is attached to the animal using tape.
	other: user specified

deploy off timestamp: The timestamp when the tag deployment ended.
	example: 2009-10-01 12:00:00.000
	format: yyyy-MM-dd HH:mm:ss.sss
	units: UTC (Coordinated Universal Time) or GPS time, which is a few leap seconds different from UTC
	same as: deploy off date

deploy on timestamp: The timestamp when the tag deployment started.
	example: 2008-08-33 18:00:00.000
	format: yyyy-MM-dd HH:mm:ss.sss
	units: UTC (Coordinated Universal Time) or GPS time, which is a few leap seconds different from UTC
	same as: deploy on date

duty cycle: Remarks associated with the duty cycle of a tag during the deployment, describing the times it is on/off and the frequency at which it transmits or records data.
	example: it turns off during the night
	units: Any units should be defined in the remarks.

event ID: An identifier for the set of information associated with each record or event in a data set. A unique event ID is assigned to every time-location or other time-measurement record in Movebank.
	example: 6340565
	units: none

latitude (decimal degree): The geographic longitude of a location along an animal track as estimated by the processed sensor data. Positive values are east of the Greenwich Meridian, negative values are west of it.
	example: -121.1761111
	units: decimal degrees, WGS84 reference system
	same as: location lat

latitude (UTM): The geographic longitude of the geographic center of a location along an animal track as estimated by the processed sensor data.
	example: 3628361.84012295
	units: meters, WGS84 reference system
	same as: utm northing

life stage: The age class or life stage of the animal at the beginning of the deployment. Can be years or months of age or terms such as "adult", "subadult" and "juvenile". Units should be defined in the values (e.g. "2 years").
	example: juvenile, adult
	units: Any units should be defined in the remarks.

local timestamp: The date and time a sensor measurement was taken in the time zone of the study reference location.
	example: 2008-08-14 15:31:00.000
	format: yyyy-MM-dd HH:mm:ss.sss
	units: specific to the study time zone
	same as: study local timestamp

longitude (decimal degree): The geographic longitude of a location along an animal track as estimated by the processed sensor data. Positive values are east of the Greenwich Meridian, negative values are west of it.
	example: -121.1761111
	units: decimal degrees, WGS84 reference system
	same as: location long

longitude (UTM): The geographic longitude of the geographic center of a location along an animal track as estimated by the processed sensor data.
	example: 756243.7836
	units: meters, WGS84 reference system
	same as: utm easting

manually marked outlier: An event marked manually as an outlier, typically using the Event Editor in Movebank. Allowed values are TRUE or FALSE.

sensor type: The type of sensor with which data were collected. Values are chosen from a controlled list:
	Argos Doppler Shift: The sensor is using Argos Doppler shift for determining position.
	GPS: The sensor uses GPS to find location and stores these.
	solar geolocator: The sensor uses measure for sunset and sunrise for determining position.
	radio transmitter: The sensor is a classical radio transmitter.
	bird ring: The animal is identified by a ring that has a unique ID.
	natural mark: The animal is identified by a natural marking.
	acceleration: The sensor collects acceleration data.
	other: The sensor is a type other than those described above.

sex: The sex of the biological individual(s) represented in the Occurrence. Values are from a controlled list:
	m: male
	f: female

study: The name of the study in Movebank in which data are stored.

study time zone: The time zone at the study reference location.
	example: Mountain Standard Time
	units: none

tag ID: A unique identifier for the tag, provided by the data owner. If the data owner does not provide a tag ID, an internal Movebank tag identifier may sometimes be shown.
	example: 2342, ptt_4532
	same as: tag local identifier

tag manufacturer name: The company or person that produced the tag.
	example: Holohil
	same as: manufacturer

tag mass: The mass of the tag.
	example: 24
	units: grams

tag model: The model of the tag.
	example: T61
	same as: model

taxon: The scientific name of the species on which the tag was deployed, as defined by the Integrated Taxonomic Information System (ITIS, www.itis.gov). If the species name can not be provided, this should be the lowest level taxonomic rank that can be determined and that is used in the ITIS taxonomy. Additional information can be provided using the term taxon detail.
	example: Buteo swainsoni
	same as: species, animal taxon, individual taxon canonical name

taxon detail: A more specific name and/or reference for the taxon name provided by the taxon term. This can be used, for example, to specify a subspecies or other taxonomic category not supported by the ITIS.
	example: Calonectris diomedea borealis (Cory, 1881)
	same as: animal taxon detail

timestamp: The date and time a sensor measurement was taken.
	example: 2008-08-14 18:31:00.000
	format: yyyy-MM-dd HH:mm:ss.sss
	units: UTC (Coordinated Universal Time) or GPS time, which is a few leap seconds different from UTC

UTM zone: The UTM zone, selected based on the location of each event, used to convert locations from decimal degrees to UTM.
	example: 14N
	units: none

visible: Determines whether an event is visible on the Movebank Search map. Values are calculated automatically, with FALSE indicating that the event has been marked as an outlier by manually marked outlier or algorithm marked outlier. Allowed values are TRUE or FALSE.

-----------

More Information
For more information about this repository, see the FAQ at www.movebank.org/node/2220 or contact us at support@movebank.org.