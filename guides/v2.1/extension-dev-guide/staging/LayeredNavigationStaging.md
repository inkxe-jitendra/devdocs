---
layout: default
group: extension-dev-guide
subgroup: 7_Staging
title: Staging in Magento 2 EE
menu_title: LayeredNavigationStaging
menu_order: 2
version: 2.1
level3_menu_node: level3child
level3_subgroup: staging_modules
github_link: extension-dev-guide/staging/LayeredNavigationStaging.md
---

![Magento EE logo]({{site.baseurl}}common/images/ee-only_large.png)

<h2>Contents</h2>

* TOC
{:toc}

## Magento_LayeredNavigationStaging module

## Overview

The Magento_LayeredNavigationStaging module is a part of the staging functionality in Magento EE.
It restricts functionality of the Magento_LayeredNavigationStaging module in the staging preview mode.

## Implementation details

The Magento_LayeredNavigationStaging module disables the Magento_LayeredNavigation module functionality in the staging preview mode.

## Dependencies

You can find the list of modules that have dependencies on the Magento_LayeredNavigationStaging module in the `require` section of the `composer.json` file. The file is located in the root directory of the module.

## Extension points

Extension points enable extension developers to interact with the Magento_LayeredNavigationStaging module. [The Magento dependency injection mechanism](http://devdocs.magento.com/guides/v2.1/extension-dev-guide/depend-inj.html) enables you to override the functionality of the Magento_LayeredNavigationStaging module.

### Layouts

You can extend and override layouts in the `Magento/LayeredNavigationStaging/view/frontend/layout/` directory.
For more information about layouts, see the [Layout documentation](http://devdocs.magento.com/guides/v2.1/frontend-dev-guide/layouts/layout-overview.html).

## Additional information

You can track [backward incompatible changes made in a Magento EE mainline after the Magento 2.0 release](http://devdocs.magento.com/guides/v2.0/release-notes/changes/ee_changes.html).