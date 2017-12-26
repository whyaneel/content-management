# Content Management System (CMS)
CMS helps creating and managing digital content. Typically the life-cycle of digital content undergoes creating, managing, publishing, archiving. In the market there are many acronyms which extends content management, few are Enterprise Information Management (EIM), Enterprise Content Management (ECM), Web Content Management (WCM), Digital Asset Management (DAM) etc.
Here our focus is more on WCM and we discuss about **OpenText TeamSite, LiveSite** which is one of the tools provides solutions on Content Management System. Latest version available in the market is 16.x.


## Getting Started
As OpenText is a proprietary software, getting the knowledge of this product is either through on-project or through the product community which may take ample amount of time. Here, You can learn fundamentals which are must for a beginner, as well as advanced practicals with some best practices. If you've already have the access to product, you can learn along with the practicals Otherwise you can still grasp the concepts with preview snapshots.

TeamSite and LiveSite are again divided into various modules.
### FormsPublisher
It's all about structuring the data, which makes the data processing easy. FormsPublisher enables business authors to make use of user-friendly forms which are derived to meet the requirements. The data collected in these forms will be transformed to either well-formed XMLs or saved in Databases. Developers has to build data capture template (DCT) which in turn shown as a form. This section talk about how to create DCT from the business requirements.

### FormAPI
This script module helps validating the data entered in fields of the forms created by FormsPublisher. Also have ability to make synchronous/ asynchronous calls to file system to fetch data dynamically, write or generate new files, modify Metadata of files with or without extending jQuery. This section talks about primarily on how to write validations and creating or updating Metadata (this will be used in LSCS).

### Workflows
While creating the valid content becomes easy with above modules, Workflows give opportunity to publish the digital content. Workflows simplifies the deployments by integrating people with content. This will also enforce the mechanism of maker, checker gateways besides the deployments. By default with the product installation, we get Publish LiveSite Content (PLC) workflow. In this section we will talk about how we can customize this PLC workflow to meet business needs.

### OpenDeploy
It's all about how frequently we deploy content. Deploying content becomes easier and faster with this OpenDeploy module. It makes sure the digital content/ files copied from one server to another server.

### SitePublisher
We can create re-usable components, templates, pages with SitePublisher. A component is a combination of Appearance XML, Content XML and Appearance XSL. A template is a group of components, where few components are always used together. A page contains components, templates. Usually the page outputs HTML to the browser, content can be static or dynamic which can be controlled from components. The skeleton of HTML can be rigid with the help of fixed layouts. If we need a page to give different outputs like JSON, RSS feeds can be achieved through page-type config. This section talks about how to create components, templates, pages and preview them.

### LiveSite Display Services - LSDS
LSDS is a parser to render the content of the pages created, on websites. This section talks about how the pages render on a website.

### LiveSite Content Services - LSCS
LSCS a RESTful service with which the content can be queried/ searched. A component can take advantage of LSCS, where dynamic websites can be developed.

### Good To Know
- Fixed Layouts
- Page Type Config
- Page Tokens


## Prerequisites
If you know these basics, it will boosts your learning.
* HTML
* JavaScript
* XSLT
* XML
* Core Java Programming


## Topics Progress
- [x] FormsPublisher Basic
- [ ] FormsPublisher Advanced
- [ ] FormsPublisher Tutorials

## Authors
* **Anil Kumar GOTTAM** - *FormsPublisher*



## Acknowledgments
* These tutorials help you to learn OpenText TeamSite, LiveSite
