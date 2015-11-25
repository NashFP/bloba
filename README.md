# BLOBA
Using FP to build the BLOBA (Boring Line-of-Business Application)

## The motivation
Here we will use powerful functional programming languages to build a BLOBA (Boring Line-of-Business Application). Some criticisms that dirty punks often hurl at functional programming are "FP is not practical” and “you can’t solve large, real world-problems with FP”. _Hogwash!_ Other more curious and civilized folk have requested examples of using FP to build the kinds of application OO developers are tasked with solving day-to-day. Here we set out to provide evidence to the doubters, and a helping hand to those who are trying to migrate to FP.

Few things in software are more practical, real-world, large, or more boring than ERP systems (Enterprise Resource Planning). So now that we’ve identified our quarry; let’s go...

## The parts
* *User interface:* web, mobile, desktop, CLI. It’s your pick (as long as it’s FP). Tasty ideas: Elm or ClojureScript for web front-end; F# + Xamarin for Mobile
* *Security:* we will need to authenticate against something (a stub module to begin with, but extra points for Active Directory, OAuth,…) and we will eventually need to support hierarchical roles.
* *Data:* data in an ERP is usually stored in a relational database. Prove to the world that your FP language can in fact read and write to a crusty RDBMS such as MySql, SQL Server, or Oracle.
* *Management portal or dashboard:* provide at-a-glance view of KPIs (key performance indicators) relevant to a particular objective or business process and a director won’t be able to resist the charms of your FP language
* *Modularity:*  ERP Systems claim modularity. Sadly this has little to do with "software seams" or interoperability. It’s more akin to layaway for enterprise capital budgets that are insufficiently massive to buy the whole system. Modules are where the business value comes, and here is where we will really prove FP’s effectiveness. Below are common modules from Wikipedia:

## Contributing 
For this playground, build whatever parts you find fun and use your functional language of choice. Contribute your solution by adding a folder named {your twitter handle}+{your language} such as: /bryan_hunter+elixir

You can push your changes, but it's more fun to submit your solution via pull-request. Time to play!

## ERP Modules (our _boring_ playground)
An ERP system covers the following common functional areas. In many ERP systems these are called and grouped together as ERP modules:

* Financial accounting: 
  * General ledger, 
  * fixed asset, 
  * payables including vouchering, 
  * matching and payment, 
  * receivables cash application and collections, 
  * cash management, 
  * financial consolidation
* Management accounting: 
  * Budgeting, 
  * costing, 
  * cost management, 
  * activity based costing
* Human resources: 
  * Recruiting, 
  * training, 
  * rostering, 
  * payroll, 
  * benefits, 
  * 401K, 
  * diversity management, 
  * retirement, 
  * separation
* Manufacturing: 
  * Engineering, 
  * bill of materials, 
  * work orders, 
  * scheduling, 
  * capacity, 
  * workflow management, 
  * quality control, 
  * manufacturing process, 
  * manufacturing projects, 
  * manufacturing flow, 
  * product life cycle management
* Order Processing: 
  * Order to cash, 
  * order entry, 
  * credit checking, 
  * pricing, 
  * available to promise, 
  * inventory, 
  * shipping, 
  * sales analysis and reporting, 
  * sales commissioning.
* Supply chain management: 
  * Supply chain planning, 
  * supplier scheduling, 
  * product configurator, 
  * order to cash, 
  * purchasing, 
  * inventory, 
  * claim processing, 
  * warehousing (receiving, putaway, picking and packing).
* Project management: 
  * Project planning, 
  * resource planning, 
  * project costing, 
  * work breakdown structure, 
  * billing, 
  * time and expense, 
  * performance units, 
  * activity management
* Customer relationship management: 
  * Sales and marketing, 
  * commissions, 
  * service, 
  * customer contact, 
  * call center support
