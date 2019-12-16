This folder includes:
	-	a folder, ADE, that contains the xsd-file for the created CityGML 3.0 ADE
	-	a folder, CityGML-3, that contains CityGML 3.0 xsd-files that was modified to be used on a local computer
	-	a folder, config, that contains the configuration files for ShapeChange. StandardNamespace.xml was modified for this test. Search paths to the local CityGML 3.0 xsd-files were added.
	-	a configuration file that include the configuration parameters for running ShapeChange, BY_CityGML-ADE.xml
	-	the UML application schema used for creating the xsd-file for the CityGML 3.0 ADE (here zipped to CityGML3_ADE_v4_EAP.zip since the original file is too large for GitHUB).
	
To run ShapeChange and create the xsd-file: "C:\Program Files (x86)\Java\jre1.8.0_191\bin\java" -jar ShapeChange-2.3.0.jar -Dfile.encoding=UTF-8 -c BY_CityGML-ADE.xml
