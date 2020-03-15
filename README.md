OpenApi Redoc UI Converter

This module provides an Redoc Converter which will convert your Open Api file into an valid document format. It provides a functionality where you can show your Open Api document formatted style on the Page, along with your node data.

1. Install module using drush or using Drupal UI

2. For this you need to add redoc  tag in you page while adding/editing a node.

3. The format of the field should be full html to support the redoc tag, it will not work with any other format if not supported.

4. The format of the tag should be like below:-

<redoc spec-url="testapipath/testname.json">
</redoc>

url is the open Api valid url or the valid file path. The format of the file should be json or yml. If any other format is used than the module will not work as expected.
