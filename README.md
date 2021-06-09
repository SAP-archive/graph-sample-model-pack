# SAP Graph Sample Model Pack

[![REUSE status](https://api.reuse.software/badge/github.com/SAP-samples/graph-sample-model-pack)](https://api.reuse.software/info/github.com/SAP-samples/graph-sample-model-pack)

## What is SAP Graph

The SAP Graph API is the single interface for unified access to interconnected data across SAP products.

SAP Graph is a network of connected data objects that are stored and owned across different SAP solutions and technologies. The data objects that are made accessible through SAP Graph in an interconnected data model can be consumed through an HTTP-based API, which exposes data from multiple SAP systems in a unified schema.

SAP Graph’s API exposes a unified graph-like model of business objects (entities) and relationships. SAP Graph uses open standards, such as OData v.4 and OAuth, thus allowing you to easily build applications and extensions for the SAP Intelligent Enterprise. In short, SAP Graph API handles the connectivity to the correct data in the correct systems through a single interface.

## About the Sample Model Pack

You can determine the shape of the model that will be exposed by your SAP Graph tenant. SAP provides a starting point, the SAP One Domain Model, and a set of corresponding translations, which is how SAP Graph implements SAP One Domain Model on top of the `dataSources` that you activated when you configured your `landscape`.

The `model` contains translation files that define the entities exposed in the SAP Graph API. SAP Graph provides a `sample model pack` that include the following six translation files of SAP One Domain Model entities:

**Note: In this beta release, non-productive translation files are provided.**

<table>
  <thead>
    <tr>
      <th>ODM Entity</th>
      <th colspan="2">Corresponding Source Entity</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td></td>
      <td><b>SAP S/4HANA Cloud<b></td>
      <td><b>SAP Sales Cloud</b></td>
    </tr>
    <tr>
      <td>BusinessPartner</td>
      <td>A_BusinessPartner</td>
      <td></td>
    </tr>
    <tr>
      <td>Customer</td>
      <td>A_BusinessPartner</td>
      <td></td>
    </tr>
    <tr>
      <td>CustomerOrder</td>
      <td>A_SalesOrder</td>
      <td></td>
    </tr>
    <tr>
      <td>CustomerQuote</td>
      <td></td>
      <td>SalesQuoteCollection</td>
    </tr>
    <tr>
      <td>Product</td>
      <td>A_Product</td>
      <td></td>
    </tr>
    <tr>
      <td>Supplier</td>
      <td>A_BusinessPartner</td>
      <td></td>
    </tr>
  </tbody>
</table>

In addition, the `sample model pack` contains templates to extend the SAP Graph model. 

1. A template to extend the model by a custom entity (see translations/template/CustomEntity.1.0.0.ext.jsonc.template)
2. Templates to extend ODM entities by custom attributes (see for example, s4/sap/odm/product/Product.0.75.0.ext.jsonc)

For more information, see [Configure the SAP Graph Tenant](https://explore.graph.sap/docs/beta/configure/configure-graph)

## Known Issues

The samples are provided on an "as-is" basis. Currently, there are no known issues for the `sample model pack`.

## How to obtain support

[Create an issue](https://github.com/SAP-samples/graph-sample-model-pack/issues) in this repository if you find a bug or have questions about the content.

For additional support, [ask a question in SAP Community](https://answers.sap.com/questions/ask.html).

## License

Copyright (c) 2021 SAP SE or an SAP affiliate company. All rights reserved. This project is licensed under the Apache Software License, version 2.0 except as noted otherwise in the [LICENSE](LICENSES/Apache-2.0.txt) file.
