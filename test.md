## FHIR Search Parameter examples:

Search parameter name: | Description 
 --- | --- 
GET Resource by **title** | title parameter returns the resource with this title
<br>

| Example |
| --- |
| `https://api.cb.zynx.com/dev-v0/fhir-a/baseDstu3/PlanDefinition?title=Asthma+-+Admission+to+ICU` |
<br>



Search parameter name: | Description 
 --- | --- 
GET Resource by **title multi** | title parameter returns the comma separated resources
<br>

| Example |
| --- |
| `https://api.cb.zynx.com/dev-v0/fhir-a/baseDstu3/PlanDefinition?title=Asthma+-+Admission+to+ICU%2CHeart+Failure+-+Home+Health` |
<br>



Search parameter name: | Description 
 --- | --- 
GET Resource by **date** | date parameter returns the resource based on the date this was last changed
<br>

| Example |
| --- |
| `https://api.cb.zynx.com/dev-v0/fhir-a/baseDstu3/PlanDefinition?date=2017-06-21` |
<br>



Search parameter name: | Description 
 --- | --- 
GET Resource by **_identifier** | _identifier returns the resource matching it
<br>

| Example |
| --- |
| `https://api.cb.zynx.com/dev-v0/fhir-a/baseDstu3/PlanDefinition?_identifier=ZynxOS-795` |
<br>



Search parameter name: | Description 
 --- | --- 
GET Resource by **publisher** | publisher parameter returns resource(s) with this publisher name
<br>

| Example |
| --- |
| `https://api.cb.zynx.com/dev-v0/fhir-a/baseDstu3/PlanDefinition?publisher=Zynx+Health` |
<br>



Search parameter name: | Description 
 --- | --- 
GET Resource by **status** | status parameter returns resource(s) of the following values  draft | active | retired | unknown
<br>

| Example |
| --- |
| `https://api.cb.zynx.com/dev-v0/fhir-a/baseDstu3/PlanDefinition?status=draft` |
<br>



Search parameter name: | Description 
 --- | --- 
GET Resource by **version** | version parameter returns resourse(s) mathing the version
<br>

| Example |
| --- |
| `https://api.cb.zynx.com/dev-v0/fhir-a/baseDstu3/PlanDefinition?version=30` |
<br>



