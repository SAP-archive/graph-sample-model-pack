# SAP Graph Sample Model Pack

The SAP Graph `sample model pack` can be used to configure an SAP Graph tenant. It contains translation files for the following ODM entities:

<table>
  <thead>
    <tr>
      <th>ODM Entity</th>
      <th colspan="2">Corresponding Source Entity</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td></th>
      <td><b>S/4 HANA Cloud<b></td>
      <td><b>Sales Cloud (C4C)</b></td>
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
      <td>A_SalesQuoteCollection</td>
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

For more information on how to configure SAP Graph, see [Documentation](https://explore.graph.sap/docs/beta/configure/configure-graph)

## Known Issues

The samples are provided on the "as-is" basis. Currently, there are no known issues for the `sample model pack`.

## How to obtain support

[Create an issue](https://github.com/SAP-samples/graph-sample-model-pack/issues) in this repository if you find a bug or have questions about the content.

For additional support, [ask a question in SAP Community](https://answers.sap.com/questions/ask.html).

## License

Copyright (c) 2021 SAP SE or an SAP affiliate company. All rights reserved. This project is licensed under the Apache Software License, version 2.0 except as noted otherwise in the [LICENSE](LICENSES/Apache-2.0.txt) file.
