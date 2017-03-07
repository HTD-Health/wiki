### FHIR
1. Created by Health Level Seven International  (http://www.hl7.org)
2. FHIR provide API:
	* RESTful endopoints
	* XML or JSON for data exchange
	* Atom for results
	* OAuth2 authentication
3. API vs document-centric approaches
4. Draft in February 2014
5. Open source reference impementations provided for variety of languages - e.g. HAPI-FHIR in Java
6. Cerner is currently in the process of implementin the FHIR (Millennium Web Services - current offering)
	• Open sandbox available - read only
Secure sandbox available (Oauth2)


### Clinical Document Architecture 
1. Created by Health Level Seven International  (http://www.hl7.org)
2. Adopted as ISO standard - ISO/HL7 27932:2009 (CDA Release 2)
3. Based on HL7 Reference Information Model (RIM) and the HL7 Version 3 Data Types
4. The CDA standard doesn't specify how the documents should be transported - it could be:
	* HL7 version 2 messages
	* HL7 version 3 messages
	* IHE protocols such as XDS
	* other mechanisms including: DICOM, MIME attachments to email, http or ftp
5. XML-based markup standard for clinical document exchange. It defines a clinical document as having the following six characteristics:
	* Persiste
	* Stewardship
	* Potential for authentication
	* Context
	* Wholeness
	* Human readability
6. In US and Candada a basis for Continuity of Care Document (CCD) specification
7. A CDA can contain any type of clinical notes. Typical CDA document types include Discharge Summary, Imaging Report, History & Physical, and Pathology Report. An XML element in a CDA supports unstructured text, as well as links to composite documents encoded in pdf, docx, or rtf, as well as image formats like jpg and png.
Document consist of mandatory textual parts (for humans) and structured optional parts (for software processing). 

### Related topics

## General
	* EPR (Electronic patient record)
	* Meaningful Use	
## Medical data exchange
	* Clinical Document Architecture (CDA)
	* Health Information Exchange (HIE)
## Concepts and semantics encoding
	* SNOMED
	* LOINC
	* Continuity of Care Record
## Products / technologies
	* Continuity of Care Document (CCD)
	* Gello Expression Language
	* SMART platform (http://smarthealthit.org)
