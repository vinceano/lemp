## FHIR Search Parameter examples:

Search parameter name: | Description 
 --- | --- 
GET Resource | returns just the resource itself not a bundle
<br>

| Example |
| --- |
| `https://api.cb.zynx.com/dev-v0/fhir-a/baseDstu3/PlanDefinition/ZynxOS-795?_format=json` |
<br>

Search parameter name: | Description 
 --- | --- 
GET Resource _history all | _history without any parameters returns all records:
The history interaction retrieves the history of either a particular resource, all resources of a given type, or all resources supported by the system. These three variations of the history interaction are performed by HTTP GET command as shown:
  GET [base]/[type]/[id]/_history{?[parameters]&_format=[mime-type]}
  GET [base]/[type]/_history{?[parameters]&_format=[mime-type]}
  GET [base]/_history{?[parameters]&_format=[mime-type]}
<br>

| Example |
| --- |
| `https://api.cb.zynx.com/dev-v0/fhir-a/baseDstu3/PlanDefinition/ZynxOS-795/_history?_format=json` |
<br>

Search parameter name: | Description 
 --- | --- 
GET Resource _history _count | returns n amount of  historic versions of the resource starting from latest :
_count : integer	single	Number of return records requested. The server is not bound to return the number requested, but cannot return more
<br>

| Example |
| --- |
| `https://api.cb.zynx.com/dev-v0/fhir-a/baseDstu3/PlanDefinition/ZynxOS-795/_history?_count=3` |
<br>

Search parameter name: | Description 
 --- | --- 
GET Resource _history _since | returns all the historic versions records _since=zulu time:
_since : instant	single	Only include resource versions that were created at or after the given instant in time
<br>

| Example |
| --- |
| `https://api.cb.zynx.com/dev-v0/fhir-a/baseDstu3/PlanDefinition/ZynxOS-795/_history?_since=2017-05-23T13:38:23.085Z` |
<br>

Search parameter name: | Description 
 --- | --- 
GET Resource _history _at | returns resource versions current _at=dateTime
_at : dateTime	single	Only include resource versions that were current at some point during the time period specified in the date time value (may be more than one)
<br>

| Example |
| --- |
| `https://api.cb.zynx.com/dev-v0/fhir-a/baseDstu3/PlanDefinition/ZynxOS-795/_history?_at=2017-06-21` |
<br>

Search parameter name: | Description 
 --- | --- 
GET Resource _history 1 | returns one specific resource version:
<br>

| Example |
| --- |
| `https://api.cb.zynx.com/dev-v0/fhir-a/baseDstu3/PlanDefinition/ZynxOS-795/_history/2?_format=json` |
<br>

Search parameter name: | Description 
 --- | --- 
GET Resource  _id ZynxOS-795 | the search with parameter _id returns a bundle with the requested resource:
<br>

| Example |
| --- |
| `https://api.cb.zynx.com/dev-v0/fhir-a/baseDstu3/PlanDefinition?_id=ZynxOS-795` |
<br>

Search parameter name: | Description 
 --- | --- 
GET Resource  _lastUpdated | The search parameter _lastUpdated can be used to select resources based on the last time they were changed:
 GET [base]/PlanDefinition?_lastUpdated=gt2017-10-01
<br>

| Example |
| --- |
| `https://api.cb.zynx.com/dev-v0/fhir-a/baseDstu3/PlanDefinition?_lastUpdated=gt2017-06-20&_lastUpdated=lt2017-06-22` |
<br>

Search parameter name: | Description 
 --- | --- 
GET Resource by _content | _content parameter searches the entire content of the resource:
<br>

| Example |
| --- |
| `https://api.cb.zynx.com/dev-v0/fhir-a/baseDstu3/PlanDefinition?_content=Peak+Expiratory+Flow+Monitoring` |
<br>

