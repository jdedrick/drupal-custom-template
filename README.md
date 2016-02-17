# drupal-custom-template
Drupal module for allowing content editors to choose a page template for a node on an individual case by case basis.
This module can be always be extended to allow for multiple type templates (e.g. node, page, etc.)

# Installation

### This section describes how to install the module and get it working.

- Include the contents of this module in your drupal installation modules directory
- Enable the module.
- Navigate to "Configuration" > "Content Authoring > Custom Node Template Settings"
- Add a relative directory as the working directory for where the custom templates live.  (e.g. sites/all/themes/<yourtheme>/customTemplates
- If there are no page templates found in the directory chosen, the node settings for this module will be disabled.
- Node edit forms should now have an additional (sidebar) setting of "Template Settings"

