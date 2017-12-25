# Content Management System (CMS)
CMS helps creating and managing digital content. Here we discuss about OpenText TeamSite, LiveSite which is one of the tools provides solutions on Content Management System. Latest version available in the market is 16.x.


## Getting Started
As OpenText is a proprietary software, getting the knowledge of this product is either through on-project or through the product community which may take ample amout of time. Here, You can learn fundamentals which are must for a beginner, as well as advanced practicals with some best practices. If you've already have the access to product, you can learn along with the practicals Otherwise you can still grasp the concepts with preview snapshots.

TeamSite and LiveSite are again divided into various modules.
### FormPublisher
It's all about structuring the data, which makes the data processing easy. FormPublisher enables business authros to make use of user-friendly forms which are derived to meet the requirements. The data collected in these forms will be transformed to either well-formed XMLs or saved in Databases. Developers has to build data capture template (DCT) which inturn shown as a form. This section talk about how to create DCT from the business requirements.

### FormAPI
This script module helps validating the data entered in fields of the forms created by FormPublisher. Also have ability to make synchronous/ asynchronous calls to file system to fetch data dynamically, write or generate new files, modify metadata of files with or without extending jQuery. This section talks about primarily on how to write validations and Metadata (this will be used in LSCS).

### Workflows
While creating the valid content becomes easy with above modules, Workflows give opportunity to publish the content by integrating people with content. Also we can enforce the mechanism of maker, checker along with the deployments.

### OpenDeploy
Deploying content becomes easier and faster with this OpenDeploy module. It's all about copying content/ files from one server to another server.

### SitePublisher
We can create re-usable components, templates, pages with SitePublisher. A component is a combination of Appearance XML, Content XML and Appearance XSL. A template is a group of components, where few components are always used together. A page contains components, templates. Usually the page outputs HTML to the browser, content can be static or dynamic which can be contolled from components. If we need a page to give different outputs like JSON, RSS feeds can be achieved through page layouts. This section talks about how to create components, templates, pages and preview them.

### LiveSite Display Services - LSDS
LSDS is a parser for the pages created to render content on websites. This section talks about how the pages render on a website. 

### LiveSite Content Services - LSCS
LSCS a RESTful service with which the content can be queried/ searched. A component can take advantage of LSCS, where dynamic websites can be developed.


## Prerequisites
If you know these basics, it will boosts your learning.
* HTML
* JavaScript
* XSLT
* Core Java Programming



## Authors

* **Anil Kumar GOTTAM** - *FormPublisher*
* **Anil Kumar GOTTAM** - *FormAPI*


## Acknowledgments

* These tutorials help you to learn OpenText TeamSite, LiveSite
