# CKEditor Templates
Drupal 8 custom module that implements Templates plugin in CKEditor.

## Installation
Install the module [as usual](https://www.drupal.org/documentation/install/modules-themes/modules-8). Extract the downloaded package to /modules in the Drupal root directory. Then navigate to **Administer > Extend** or http://examp.le/admin/module. Check the 'Enabled' box next to the module and then click the 'Save Configuration' button at the bottom.

Download Templates plugin from [CKEditor.com](http://ckeditor.com/addon/templates) and extract the package to `ckeditor_templates/js/plugins/`, so that `plugins.js` file will be located at `ckeditor_templates/js/plugins/templates/plugin.js`.

## Configuration
Navigate to **Administer > Configuration > Content authoring** or http://examp.le/admin/config/content/formats, then click 'Configure' on a text format which has CKEditor enabled. In the 'Toolbar configuration' section drag the Templates button from 'Available buttons' to 'Active toolbar'. Finally edit plugin settings specifying the name of your templates set, and the file path where templates are defined.
