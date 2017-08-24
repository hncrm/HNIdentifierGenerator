# HN Identifier Generator
#### A flexible Unique Identifier generator for Dynamics 365 

### Features
* Supports multiple Identifier generation methods
  * Sequential or auto-number
  * Random - Numeric and alpha-numeric 
* Supports generation of Identifer from client-side i.e before record is created
* Support workflow based generation of Unique Identifier
* Supports the ability to append Prefix and Suffix
* Supports client-side generation
* Supports custom and out of the box entities

### Getting Started

Using the Identifier Generator for your custom and out of the box entities is simple.  Simply create a configuration item for the identifier and apply the configuration item against the required attribute in the entity that requires to generate the Identifer.  

#### 1. Configure Identifier settings

Each unique Identifier requires a separate identifier configuration setting. 

To create an identifier configuration setting, open the Identifier entity via **Settings --> HN Extentions --> Identifer** from the Dynamics Custom Sitemap

Sequential | Random | Random Numeric
----------   ------   --------------
 |  | 
 |  |



#### 2. Utilise Identifier Generator with your entities
  