---
layout: default
group: extension-dev-guide
subgroup: 7_Staging
title: Staging in Magento 2 EE
menu_title: GiftMessageStaging
menu_order: 2
version: 2.1
level3_menu_node: level3child
level3_subgroup: staging_modules
github_link: extension-dev-guide/staging/GiftMessageStaging.md
---

![Magento EE logo]({{site.baseurl}}common/images/ee-only_large.png)

<h2>Contents</h2>

* TOC
{:toc}

## Magento_GiftMessageStaging module

## Overview

The Magento_GiftMessageStaging module is a part of the staging functionality in Magento EE. It extends the Magento_GiftMessage module functionality to be used in the Schedule Update form.

## Implementation details

The Magento_GiftMessageStaging module enables you to stage the "Allow Gift Message" flag in the "Gift Options" field set in the "Schedule Update" form of the product.

## Dependencies

You can find the list of modules that have dependencies on the Magento_GiftMessageStaging module in the `require` section of the `composer.json` file. The file is located in the root directory of the module.

## Extension points

[The Magento dependency injection mechanism](http://devdocs.magento.com/guides/v2.0/extension-dev-guide/depend-inj.html) enables you to override the functionality of the Magento_GiftMessageStaging module.

## Additional information

You can track [backward incompatible changes made in a Magento EE mainline after the Magento 2.0 release](http://devdocs.magento.com/guides/v2.0/release-notes/changes/ee_changes.html).