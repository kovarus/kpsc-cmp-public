# KPSC Cloud Management Platform (CMP) Public Artifact Repository
This repository hosts all public blueprints for the various cloud management platforms hosted within the Kovarus Proven Solutions Center (KPSC).

## VMware Cloud Automation Services (CAS)
Cloud Assembly blueprints that are available for use in various projects. The name of the blueprint will be the folder, with a single file under each folder named *blueprint.yaml*. 

## VMware vRealize Automation (vRA) 7.x 
All blueprints published to this repository will have four (4) core elements:

	1. Blueprint: This will be presented as both a .zip file available to import into another vRealize Automation instance (_blueprint.zip_), as well as decompressed in a folder name 'blueprint' so each component of the blueprint can be reviewed individually.
	2. Custom Form: This is the form that gets presented when a user goes to request the blueprint in vRA; the file name will be form.yml
	3. Style Sheet: This is the CSS style sheet to adjust how certain elements with the custom form ; the file name will be form.css
	4. Icon: the selected icon / logo that is presented in the service catalog for the blueprint