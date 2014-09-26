# Service Quoting Achievements

## Hackathon

### Top-Level

* **Base Configurator** can scope and cost a generic PS, non-program engagement with firm-fixed pricing
* **3 New WebApps in DEV**
* **8 new RESTful Endpoints**
* **1,341 Lines of Code** [Note: this is low since it doesn't count several branches that haven't been merged yet]
* **First Margin Bangger** in WWT history

### RESTful APIs

* **Travel API** [created](https://www-dev.wwt.com/travel-api/) to expose reference data about travel
  * **Mileage Rate** exposed as a web API
  * **Place** search, including search on city, state and zip
  * **Airport** geospatial search to find airports with airfaire near a given place
* **PS Roles and Rates API** to get generic non-program roles and rates from ERP
* **Service Quote API** to save, load and search Service Quotes and perform calculations

### Other Bits

* **Calculation Pipeline** to calculate Service Quote cost, built to easily adopt new rules
* **Per Diem** automatically retrieved from GSA

### Technical Achievements

* **Mongo Geospacial Indexes** proves out an extra use case for this new technology
* **Advanced MongoDB & GORM** usage, including custom types which can hold other custom types
* **RAML** API documentation gives our APIs an extra degree of usability
* **SalesForce via REST**, via Grails, makes accessing SalesForce easier for a larger number of developers
* **Money!** Real Money implementation supporting multiple currencies with safe handling of floating-point math
 
### Team Achievements
* **3 New Grails Developers**
* **3 New Angular Developers**
* **1 New Analyst Training as a Developer**
* **4 Contributions to Custom Apps Shared Projects**. One in `mortar-proxy`, one in `grunt-mortar`, two in UI Playbook.
* **1 Team Member Promoted** to Development Manager in the first month of the project
* **Whole Team, End to End Understanding** of our business partners and the problems we're trying to solve from new project startup approach
